# Task 1 - Vulnerability Assessment

## Objective

The objective of this project was to perform a vulnerability assessment of a web application using industry-standard security tools. The assessment focused on identifying potential security weaknesses, analyzing risks, and providing recommendations to improve the security posture of the target application.

---

## Target

**Target Website:** demo.testfire.net

---

## Tools Used

* Nmap
* OWASP ZAP
* Browser Developer Tools
* Kali Linux

---

## Methodology

### 1. Reconnaissance

Nmap was used to gather information about the target host and identify accessible services.

### 2. Passive Vulnerability Scanning

OWASP ZAP was used to perform passive analysis of HTTP requests and responses to identify potential security issues.

### 3. Security Header Analysis

Browser Developer Tools were used to inspect HTTP response headers and verify the implementation of common security controls.

### 4. Documentation

All findings were documented along with their potential impact and recommended mitigations.

---

## Project Deliverables

* Vulnerability Assessment Report
* Nmap Scan Results
* OWASP ZAP Scan Results
* Security Findings
* Recommendations
* Supporting Screenshots

---

## Folder Structure

```text
Task_1_Vulnerability_Assessment/
│
├── README.md
├── Vulnerability_Assessment_Report.pdf
└── Screenshots/
    ├── nmap_scan.png
    ├── zap_dashboard.png
    ├── zap_homepage.png
    ├── zap_alerts.png
    └── headers.png
```

---

## Key Findings

* Network filtering mechanisms were observed during reconnaissance.
* Security-related observations were identified through passive scanning.
* Recommendations were provided to improve application security.
* No intrusive testing was performed.

---

## Learning Outcomes

Through this project, the following concepts were explored:

* Vulnerability Assessment Methodology
* Network Reconnaissance
* Passive Web Application Security Testing
* Security Header Analysis
* Risk Assessment
* Security Documentation

---

## Disclaimer

This assessment was conducted strictly for educational and internship purposes. Testing activities were limited to authorized and intentionally vulnerable environments.
