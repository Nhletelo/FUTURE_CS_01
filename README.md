# Vulnerability Assessment Report

## Overview
This project contains a Vulnerability Assessment Report conducted on a live website as part of a cybersecurity task. The goal was to identify security weaknesses and provide recommendations to improve the website’s safety and reliability.

---

## Target Website
https://juice-shop.herokuapp.com

>  Note: This is an intentionally vulnerable application used for educational purposes.

---

## Scope of Assessment
- Read-only testing (no exploitation performed)
- Focus on identifying common web vulnerabilities
- No disruption to the live system

---

## Tools Used
- Nmap – Network scanning
- OWASP ZAP (Passive Scan) – Vulnerability detection
- Browser Developer Tools – Frontend inspection
- SecurityHeaders.com – Security header analysis

---

## Key Findings
- Missing Security Headers (High Risk)
- Information Disclosure (Medium Risk)
- Open Ports (Low Risk)
- Server Error – 503 Service Unavailable (Medium Risk)

---

## Recommendations
- Implement missing security headers
- Hide sensitive system information
- Close unused ports
- Keep software and systems updated
- Monitor website performance and uptime
- Perform regular security testing

---

---

##  Evidence
Screenshots and tool outputs are included in the **evidence/** folder to support the findings in the report.

---

##  Disclaimer
This assessment was conducted for educational purposes only. No exploitation or harmful actions were performed against the target website.

---

##  Author
- Name: *Nhletelo Shibambu*
- Course/Program: *CYBER SECURITY*

---

##  Acknowledgment
Security testing supported by Snyk API & Web tools.
