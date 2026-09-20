# URL-Threat-Scanner
A web-based URL threat scanner for detecting suspicious, phishing, and potentially malicious URLs.
## 🔍 Scope

This scanner performs **URL structure analysis only**. It does not fetch or inspect the live webpage because browser-based requests are limited by **CORS restrictions**.

The scanner checks URLs for indicators such as:

- Typosquatting patterns
- IP-address-based hosts
- Punycode / homograph encoding
- Credential-harvesting keywords
- Excessive subdomains
- Known URL shortener abuse patterns
- Suspicious or commonly abused TLD patterns

## ⚠️ Limitations

This project is intended as a **teaching and initial triage tool**.

It does not use a live threat-intelligence database and should not be treated as a replacement for services such as maintained reputation feeds, malware databases, or enterprise security tools.

A URL marked as safe may still be malicious, and a suspicious result does not automatically mean the URL is malicious.
