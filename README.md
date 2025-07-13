# FUTURE_CS_01 – Web Application Security Testing

## 🔍 Task Objective
This project involved identifying vulnerabilities in DVWA (Damn Vulnerable Web App) as part of my Cyber Security Internship with Future Interns.

## 🛠 Tools Used
- DVWA (via Docker)
- Burp Suite
- Firefox
- SQLMap (optional)

## 🚨 Vulnerabilities Discovered

### 1. SQL Injection
- **Payload:** `1' OR '1'='1`
- **Result:** Bypassed user authentication and dumped user info.
- **Severity:** High
- **Screenshot:** 'Screenshot_2025-07-13_16_57_22.png`

### 2. Stored Cross-Site Scripting (XSS)
- **Payload:** `<script>alert('XSS')</script>`
- **Result:** Alert box execution via injected script.
- **Severity:** Medium
- **Screenshot:** `/Screenshots/Screenshot_2025-07-13_16_59_09.png`

## 🧩 OWASP Top 10 Mappings
- A03: Injection ✅
- A07: XSS ✅

## 📄 Deliverables
- [Vulnerability_Report.pdf](./Vulnerability_Report.pdf)
- Screenshots
- OWASP Mapping Table
