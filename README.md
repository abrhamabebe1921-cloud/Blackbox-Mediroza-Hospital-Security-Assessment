  # Mediroza General Hospital — Penetration Testing Report

A black-box web application security assessment conducted as part of the Networkwalks Cybersecurity Internship, Week 4.

## Project Information

| Field | Details |
|---|---|
| Project | Mediroza General Hospital Security Assessment |
| Target | https://medirozahospital.com |
| Student | Abrham Abebe |
| Internship | Networkwalks Cybersecurity Internship |
| Batch | B084 |
| Week | Week 4 |
| Assessment Duration | 5 Days |
| Assessment Type | Black-box Penetration Testing |
| Operating System | Arch Linux |
| Testing Environment | Authorized Training Target |
| Report Format | PDF |
| Report Length | 16 Pages |


## Tools and Technologies

The following tools are referenced in the assessment report and testing workflow.

### Reconnaissance
- WHOIS
- nslookup
- Nmap
- WhatWeb
- WAFW00F

### Web Application Security Testing
- Burp Suite proffetional
- cURL
- SQLmap

### Password and PDF Analysis
- pdf2john
- John the Ripper
- Python
- pikepdf
- Hydra

### File and Evidence Analysis
- ExifTool
- file
- sha256sum
- wget

### Documentation and Reporting
- Markdown
- Git
- GitHub
- GitHub Pages

*Note: This is the combined list of tools referenced in the report and testing workflow. Not every listed tool has a confirmed execution result.*

## Assessment Scope

The assessment focused on the following areas:

- Website reconnaissance and information gathering
- Authentication mechanism analysis
- Input validation and SQL injection assessment
- Access control investigation
- Security header analysis
- Session cookie security
- Directory and backup exposure checks
- PDF encryption analysis
- Login security and rate-limiting observations

## Methodology

1. Reconnaissance and information gathering
2. Identification of exposed web application entry points
3. Authentication and session security assessment
4. Input-handling and access-control investigation
5. Security configuration and HTTP header analysis
6. Evidence collection and risk assessment
7. Recommendations and remediation documentation

## Report Contents

The full assessment report contains:

- Executive Summary
- Assessment Scope
- Findings Overview
- Technical Vulnerability Details
- Proof of Concept Evidence
- Risk Rating Summary
- Recommendations and Remediation
- Tools and Techniques Used

## Repository Structure

```text
Mediroza-Hospital-Security-Assessment/
│
├── README.md
└── black-box.pdf
```

## Full Assessment Report

The complete 16-page penetration testing report is available through the repository's PDF viewer.

## Disclaimer

This project was conducted as part of an authorized cybersecurity training engagement. Testing was limited to the agreed target and internship scope. Findings marked as pending verification require further confirmation.

