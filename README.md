# OWASP ZAP Vulnerability Assessment Lab

## Project Overview

This project demonstrates a hands-on web application vulnerability assessment using OWASP ZAP against the OWASP Juice Shop application running in Docker on Ubuntu Linux.

The objective was to gain practical experience in web application security testing, vulnerability identification, and security analysis using industry-standard tools.

---

## Environment

- Ubuntu Linux
- Docker
- OWASP ZAP 2.17
- OWASP Juice Shop
- Firefox

---

## Objectives

- Install Docker
- Deploy OWASP Juice Shop
- Configure OWASP ZAP
- Perform an automated vulnerability scan
- Review identified security findings
- Understand vulnerability severity and remediation

---

## Scan Target

```
http://localhost:3000
```

---

## Tools Used

- OWASP ZAP
- Docker
- OWASP Juice Shop
- Firefox
- Ubuntu Linux

---

## Findings

### Medium Risk

- Content Security Policy (CSP) Header Not Set

### Low Risk

- Cross-Domain Misconfiguration

### Informational

- Timestamp Disclosure
- Information Disclosure – Suspicious Comments
- Modern Web Application
- User Agent Fuzzer

---

## Example Vulnerability

### Content Security Policy (CSP) Header Not Set

**Risk:** Medium

A Content Security Policy (CSP) is a browser security feature that helps prevent Cross-Site Scripting (XSS) and other code injection attacks.

Without a CSP header, attackers may have an easier time executing malicious scripts if another vulnerability exists.

**Recommendation**

Configure the web server to send an appropriate Content-Security-Policy header to restrict trusted content sources.

---

## Skills Demonstrated

- Vulnerability Assessment
- Web Application Security
- OWASP ZAP
- Docker
- Ubuntu Linux
- Security Analysis
- Risk Assessment
- Vulnerability Management

---

## Screenshots

Include screenshots of:

- Ubuntu environment
- Docker container running
- OWASP Juice Shop
- OWASP ZAP scan
- Vulnerability findings
- CSP vulnerability details

---

## Lessons Learned

This lab provided practical experience in:

- Deploying a vulnerable web application
- Running automated vulnerability scans
- Understanding vulnerability severity
- Interpreting security findings
- Reviewing remediation recommendations

---

## Author

Tinashe Zacariah Nyandoro

Entry-Level Cybersecurity Analyst

ISC2 Certified in Cybersecurity (CC)

Google Cybersecurity Professional Certificate

IBM Cybersecurity Professional Certificate

Blue Team | SOC | Vulnerability Management | Linux | Network Security
