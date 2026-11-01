# 📧 Phishing Email Security Analysis

![Documentation](https://img.shields.io/badge/Documentation-Markdown-blue)
![Email Security](https://img.shields.io/badge/Email-Security-orange)
![Phishing](https://img.shields.io/badge/Phishing-Analysis-red)
![OSINT](https://img.shields.io/badge/OSINT-Enabled-green)
![SOC](https://img.shields.io/badge/SOC-Security%20Operations-blueviolet)

---

## 📌 Project Overview

This project demonstrates practical email security analysis involving 13 email samples, including suspicious and legitimate emails.

The objective was to examine email characteristics, identify potential phishing indicators, extract Indicators of Compromise (IOCs), assess risk levels, and document the findings in a structured technical report.

The analysis involved sender verification, email header inspection, email authentication checks, social engineering identification, and OSINT-based verification.

Selected samples also underwent URL and attachment-related checks using available threat intelligence and analysis services.

---

## 🎯 Objectives

- Analyse email headers and sender information.
- Verify SPF, DKIM, and DMARC authentication results.
- Identify phishing, impersonation, and Business Email Compromise (BEC) indicators.
- Extract relevant Indicators of Compromise (IOCs).
- Examine suspicious URLs and attachment-related indicators where applicable.
- Perform evidence-based risk classification.
- Document findings in a structured SOC-style technical report.

---

## 🛠️ Skills Demonstrated

- Email Security Analysis
- Email Header Analysis
- Phishing Detection
- Business Email Compromise (BEC) Identification
- IOC Extraction
- Email Authentication (SPF, DKIM, DMARC)
- URL Reputation Analysis
- Threat Intelligence Lookup
- OSINT Verification
- Risk Assessment
- Security Documentation

---

## 🔄 Analysis Workflow

```text
                 📩 Email Samples
                       │
                       ▼
              🔍 Email Header Analysis
                 (SPF • DKIM • DMARC)
                       │
                       ▼
             👤 Sender & Domain Verification
                       │
                       ▼
             🌐 URL & Attachment Checks
                 (Selected Samples)
                       │
                       ▼
             🧩 IOC Extraction & Validation
                 (IP • Domain • Hash • URL)
                       │
                       ▼
              🛡️ Threat Intelligence Lookup
             (VirusTotal / AbuseIPDB / WHOIS)
                       │
                       ▼
                 ⚖️ Risk Assessment
             (Benign / Suspicious / Malicious)
                       │
                       ▼
                📝 Technical Reporting
```

This workflow represents the structured approach used to analyse email samples, validate technical indicators, assess potential threats, and document findings.

---

## 🧰 Tools Used

- MXToolbox – Email header and authentication analysis
- VirusTotal – URL, domain, and file reputation checks
- urlscan.io – Website and URL analysis
- AbuseIPDB – IP reputation checks
- WHOIS – Domain registration information and verification

---

## 📊 Analysis Scope

The practical work covered the following areas:

| Analysis Area | Activities |
|---|---|
| Email Authentication | SPF, DKIM, and DMARC validation |
| Header Analysis | Sender information and email routing inspection |
| Phishing Detection | Identification of suspicious email characteristics |
| Social Engineering | Recognition of impersonation and deceptive messaging |
| IOC Analysis | Extraction and assessment of relevant indicators |
| URL Analysis | Reputation and destination checks on selected samples |
| Attachment Checks | Review of attachment-related indicators where applicable |
| Risk Classification | Assessment of email samples using technical evidence |

---

## 📁 Repository Structure

```text
Phishing-Email-Security-Analysis/
│
├── README.md
├── report/
│   └── SOC_Email_Threat_Investigation_Report.pdf
│
└── docs/
    ├── methodology.md
    ├── tools-used.md
    └── learning-outcomes.md
```

---

## 📚 Learning Outcomes

Through this practical work, I strengthened my understanding of how to:

- Analyse sender domains and email routing information.
- Interpret SPF, DKIM, and DMARC authentication results.
- Identify phishing and social engineering indicators.
- Examine suspicious URLs and attachment-related indicators.
- Extract and assess Indicators of Compromise (IOCs).
- Use threat intelligence services to support technical analysis.
- Classify email samples based on observed evidence.
- Document findings using a structured SOC-style report.

---

## 📂 Project Files

- 📄 [Final Email Threat Analysis Report](report/SOC_Email_Threat_Investigation_Report.pdf)
- 📖 [Analysis Methodology](docs/methodology.md)
- 🛠️ [Tools Used](docs/tools-used.md)
- 🎓 [Learning Outcomes](docs/learning-outcomes.md)

---

## ⚠️ Disclaimer

This repository contains my analysis and learning outcomes from a cybersecurity internship assignment. Any proprietary or confidential training materials from the internship provider are not included.

The work was conducted for educational purposes using the provided email samples and publicly available analysis resources.

---

## 👤 Author

**Samyuktha Saravanan**

Cybersecurity Graduate
