# 📧 Phishing Email Security Analysis

![Documentation](https://img.shields.io/badge/Documentation-Markdown-blue)
![SOC](https://img.shields.io/badge/SOC-Investigation-red)
![Email Security](https://img.shields.io/badge/Email-Security-orange)
![Digital Forensics](https://img.shields.io/badge/Digital-Forensics-purple)
![OSINT](https://img.shields.io/badge/OSINT-Enabled-green)

---

## 📌 Overview

This project demonstrates a SOC-style investigation of suspicious and legitimate emails. The objective was to analyze each email, identify phishing indicators, extract Indicators of Compromise (IOCs), classify the risk level, and document the findings in a professional incident report.

The investigation was performed using standard email analysis techniques, including sender verification, email authentication analysis, header inspection, social engineering detection, and OSINT-based verification.

---

## 🎯 Objectives

- Analyze email headers and sender information.
- Verify SPF, DKIM, and DMARC authentication.
- Detect phishing, impersonation, and Business Email Compromise (BEC) attempts.
- Extract Indicators of Compromise (IOCs).
- Perform risk classification based on technical evidence.
- Document findings in a SOC-style investigation report.

---

## 🛠️ Skills Demonstrated

- Email Security Analysis
- Email Header Analysis
- Phishing Detection
- Business Email Compromise (BEC)
- IOC Extraction
- Email Authentication (SPF, DKIM, DMARC)
- Threat Investigation
- Risk Assessment
- Security Documentation
- OSINT Verification

---

## 🔄 Investigation Workflow

```text
                 📩 Email Received
                        │
                        ▼
             🔍 Header Analysis
        (SPF • DKIM • DMARC)
                        │
                        ▼
          🌐 URL & Attachment Analysis
                        │
                        ▼
         🧩 IOC Extraction & Validation
        (IP • Domain • Hash • URLs)
                        │
                        ▼
       🦠 Threat Intelligence Lookup
      (VirusTotal / AbuseIPDB / WHOIS)
                        │
                        ▼
           ⚖️ Risk Assessment
      (Benign / Suspicious / Malicious)
                        │
                        ▼
          📝 Investigation Report

This investigation follows a structured SOC workflow, starting from email triage and header analysis through IOC validation, threat intelligence enrichment, risk assessment, and final reporting.
```
---

## 🧰 Tools Used

- MXToolbox
- VirusTotal
- urlscan.io
- AbuseIPDB

---

## 📁 Repository Structure

```
email-threat-investigation-analysis/
│
├── README.md
├── report/
│   └── SOC_Email_Threat_Investigation_Report.pdf
└── docs/
    ├── methodology.md
    ├── tools-used.md
    └── learning-outcomes.md
```

---

## 📚 Learning Outcomes

Through this project, I learned how to:

- Analyze sender domains and email routing.
- Verify SPF, DKIM, and DMARC authentication.
- Detect phishing and social engineering techniques.
- Identify suspicious links and attachments.
- Extract Indicators of Compromise (IOCs).
- Perform evidence-based risk classification.
- Document investigations in a professional SOC report.

---

## 📂 Project Files

- 📄 [Final SOC Investigation Report](report/SOC_Email_Threat_Investigation_Report.pdf)
- 📖 [Investigation Methodology](docs/methodology.md)
- 🛠️ [Tools Used](docs/tools-used.md)
- 🎓 [Learning Outcomes](docs/learning-outcomes.md)

---

## ⚠️ Disclaimer

This repository contains my analysis and learning outcomes. Any proprietary or confidential training materials from the internship provider are not included.
---

## 👤 Author

**Samyuktha Saravanan**

Cybersecurity Enthusiast | SOC Analyst Aspirant
