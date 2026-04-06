# Vulnerability Assessmenyt Report

## Project Overview

This project focuses on identifying security vulnerabilities in a web application (demo.testfire.net) using ethical hacking tools.

---

## Tools Used
- Nmap (Network scanning & reconnaissance)
- OWASP ZAP (Web vulnerability scanning)


---

## Vulnerability Identified

- Cross-Site Scripting (XSS) - High Risk
- SQL Injection - High Risk
- Missing Security Headers - Medium Risk

---


### Methodology

1. Reconnaissance using Nmap
2. Scanning using OWASP ZAP
3. Identifying vulnerabilities
4. Analyzing results
5. Reporting findings

---

## Security Recommendations
### For XSS:
- Validate and sanitize inputs
- Use output encoding
- Implement CSP

### For SQL Injection:
- Use parameterized queries
- Avoid dynamic SQL


### General:
- Regular vulnerability scanning
- Keep systems updated

---

## Author
Nagender Thokala
Cybersecurity Intern

---

## Project File
[Vulnerability Assessment Report] (./Vulnerability_Assessment_Report.pdf)
