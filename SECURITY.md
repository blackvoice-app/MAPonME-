# Security Policy for BlackVoice.tech (MAPonME)

BlackVoice is a privacy-first PWA focused on end-to-end encrypted communications and emergency features. Security is our top priority.

## Reporting a Vulnerability
If you discover a security vulnerability, please report it privately (do not create public issues).

- Email: contact@blackvoice.tech  
- PGP key available upon request (contact us first)  
- Expected response time: within 72 hours for initial acknowledgment

We will investigate promptly and keep you informed of progress.

## Supported Versions
Currently only the latest beta/production version is supported.

## Security Practices
- End-to-end encryption with PFS (Signal Protocol-inspired)
- AES-256-GCM, PBKDF2 100k iterations, Shamir's Secret Sharing
- Zero-Knowledge local notes (no server access)
- Dead Man's Switch for data protection
- Multi-layer anti-tracking (fake GPS)
- No ads, no tracking, no telemetry

## Audit Results
- Qualys SSL Labs: A+ (TLS 1.3, strong ciphers, HSTS)
- Internal Security Audit (Jan 10, 2026): 97/100 – EXCELLENT
  - 100% PASS on secrets, cookies, CSRF, rate limiting, auth
  - Reports available in /reports folder

## Known Minor Issues (from external scans)
- Missing Secure/HttpOnly flags on some cookies (GAESA/csrftoken) → fixed in progress
- Unsafe CSP for Google Maps → planning nonce/hashes or OSM pure migration

Thank you for helping keep BlackVoice secure!

Valentin Gheorghiu (YO9BX)
