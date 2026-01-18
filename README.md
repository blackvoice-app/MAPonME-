# BlackVoice.tech (MAPonME) Documentation

**Free, privacy-first Progressive Web App (PWA) for secure end-to-end encrypted communications, emergency response, and location privacy.**

Developed solo by **Valentin Gheorghiu (YO9BX)** in Frankfurt am Main, Germany.  
Targets users in high-risk or disrupted environments: hikers, activists, journalists, rescue teams, and individuals facing censorship or surveillance.

### Core Features
- **Private & Smart Chat** — E2EE messaging with Perfect Forward Secrecy (PFS) using Signal Protocol-inspired implementation (X3DH + Double Ratchet on P-256, AES-256-GCM, HKDF-SHA256), Dual AES-256-GCM fallback.
- **BlackPTT** — Encrypted voice PTT with AES-256-GCM, PFS verified, record-and-send mode.
- **SOS Emergency System** — <1s delivery, GPS capture, AML (WGS84 format), medical data (blood type, allergies, medications), emergency contacts, 112 auto-call, SMS+GPS compose with 10s countdown, visible on map as SOS icon.
- **Fake GPS Fortress** — Multi-layer location spoofing (10km to worldwide radius), 7-10 anti-tracking layers (WebRTC block, sensor masking, timezone/battery spoofing).
- **Zero-Knowledge Personal Notes** — PBKDF2 100k iterations + AES-256-GCM local encryption, master password never leaves device, no server access.
- **Dead Man's Switch** — Configurable inactivity timer (1–30 days); notifies emergency contacts with last known location and wipes local sensitive data.
- **Interactive Global Maps (MAPonME)** — Real-time Leaflet + OpenStreetMap, Garmin MapShare/APRS Ham Radio tracking, Live Tracking Links (temporary/revocable), group coordination (photo/location share, Rally point alerts, SOS alerts).
- **Group Functions** — Photo with location sharing, voice messages, Rally point alerts, share location, SOS alerts.

### Security Highlights
- Qualys SSL Labs: **A+**
- Internal Security Audit (Jan 10, 2026): **97/100 – EXCELLENT** (100% PASS on secrets/CSRF/rate limiting/auth)
- Pentest-Tools & HostedScan reports: Minor issues only (no critical/high vulns)
- Proprietary architecture: VortexMind™ v1.0 (6 subsystems), Obsidian Aegis Continuum™ v2.0 (8 subsystems), KeyFortress™ v1.1 (Shamir's Secret Sharing), etc.

**No ads, no tracking, fully free forever.**

### Current Status
- Beta
- Launching on Product Hunt: February 26, 2026
- Website: https://blackvoice.tech
- Product Hunt: https://www.producthunt.com/p/maponme-by-blackvoice-technologies

### Important
This repository contains **public documentation only**. The source code is proprietary and not available.

Feedback welcome! Join us on Product Hunt or email: contact@blackvoice.tech

Made with ❤️ by Valentin (YO9BX)
