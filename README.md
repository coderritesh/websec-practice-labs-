# Web Security Notes

Personal study notes and step-by-step practical guides from learning web application security with **PortSwigger Web Security Academy** and **DVWA (Damn Vulnerable Web Application)**.

> ⚠️ **Disclaimer:** Everything documented here was practised on free, intentionally vulnerable training platforms, run locally or on tools built for this exact purpose. These notes are for learning only — never use these techniques against any system you do not own or do not have explicit written permission to test.

---

## 📘 PortSwigger Web Security Academy

`PortSwigger_Beginner_Guide.docx`

A beginner's introduction to PortSwigger and its free Web Security Academy platform, covering:

- What PortSwigger and Burp Suite are
- How the Academy's labs work (Apprentice → Practitioner → Expert)
- The full range of lab categories (SQL injection, XSS, CSRF, access control, SSRF, JWT, API/GraphQL, and more)
- Where to find official hints and solutions for every lab
- A suggested beginner roadmap

🔗 [Web Security Academy](https://portswigger.net/web-security) · [All labs](https://portswigger.net/web-security/all-labs)

---

## 🛠️ DVWA (Damn Vulnerable Web Application)

`DVWA_Practical_Guide_Low_Security.docx`

A hands-on walkthrough of all 18 DVWA vulnerability modules at **Security Level: Low**, including:

- What each vulnerability is, in plain language
- Exact step-by-step exploitation instructions
- What happens and *why* the Low-security code allows it
- Basic mitigation notes for each issue
- Brute Force module covers **both** Hydra (CLI) and Burp Suite Intruder methods, with cookie/session troubleshooting

**Modules covered:** Brute Force · Command Injection · CSRF · File Inclusion · File Upload · Insecure CAPTCHA · SQL Injection · SQL Injection (Blind) · Weak Session IDs · XSS (DOM/Reflected/Stored) · CSP Bypass · JavaScript Attacks · Authorisation Bypass · Open HTTP Redirect · Cryptography · API Security

🔗 [DVWA GitHub repo](https://github.com/digininja/DVWA)

---

## 🎯 Why this repo exists

Tracking my own progress while learning common web vulnerability classes (OWASP Top 10 and beyond) through free, legal, hands-on labs — PortSwigger for guided theory + hosted labs, DVWA for a self-hosted app to practise with real tools like Burp Suite and Hydra.

## 📌 Tools used

- [Burp Suite Community Edition](https://portswigger.net/burp/communitydownload)
- [Hydra](https://github.com/vanhauser-thc/thc-hydra)
- [DVWA](https://github.com/digininja/DVWA)

---

*Last updated: November 2026*
