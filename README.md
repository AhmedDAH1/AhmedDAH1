# Ahmed Dahdouh

**SOC Analyst · Blue-Team Security Engineer** — building production-grade security tooling with real threat-intelligence integration.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/ahmed-dahdouh)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail)](mailto:adahdouh123@gmail.com)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-Profile-212C42?style=for-the-badge&logo=tryhackme)](https://tryhackme.com/p/AhmedDAH1)

---

## About

Software Engineering student specializing in cybersecurity, focused on the blue-team SOC workflow — alert triage, threat intelligence, log analysis, and incident response. I've built **five security tools**, **four of them deployed as live demos**, each with automated tests, Docker packaging, and CI/CD. Seeking an entry-level SOC Analyst role.

---

## 🚀 Featured: SOAR-Lite — Security Orchestration, Automation & Response

[![Live Demo](https://img.shields.io/badge/Live_Demo-Online-success?style=flat-square)](https://soar-lite.onrender.com)
[![Demo Video](https://img.shields.io/badge/▶_6min_Walkthrough-YouTube-red?style=flat-square&logo=youtube)](https://youtu.be/Wade9SSN-Ts)
[![Code](https://img.shields.io/badge/Code-GitHub-181717?style=flat-square&logo=github)](https://github.com/AhmedDAH1/soar-lite)
[![Tests](https://img.shields.io/badge/tests-53%20passing-brightgreen?style=flat-square)](https://github.com/AhmedDAH1/soar-lite/actions)
[![Coverage](https://img.shields.io/badge/coverage-84%25-brightgreen?style=flat-square)](https://github.com/AhmedDAH1/soar-lite)

Automates the full SOC triage workflow — alert ingestion via webhooks, IOC extraction, async threat-intelligence enrichment (VirusTotal, AbuseIPDB), a YAML playbook engine, and one-click PDF/DOCX reports. Cuts simulated incident response from 30+ minutes to under 2.

**Stack:** Python · FastAPI · SQLAlchemy · Alembic · PostgreSQL/SQLite · Docker

**🚀 [Live demo](https://soar-lite.onrender.com)** · **🎬 [6-min walkthrough](https://youtu.be/Wade9SSN-Ts)** · **[Code](https://github.com/AhmedDAH1/soar-lite)**

---

## 🛠️ Security Projects

### 📧 Email Threat Analyzer — Phishing Detection Engine
[![Live Demo](https://img.shields.io/badge/Live_Demo-Online-success?style=flat-square)](https://email-threat-analyzer-zt7f.onrender.com)
[![Code](https://img.shields.io/badge/Code-GitHub-181717?style=flat-square&logo=github)](https://github.com/AhmedDAH1/email-threat-analyzer)

Live web tool — paste any `.eml` and see it scored 0–100 across header, URL, attachment, and content modules. Validated at **73% detection on the Nazario phishing corpus** (414 real-world emails), with a labeled benign control demonstrating low false positives. Docker + gunicorn, 34 tests, CI.

**Tech:** Python · Flask · Docker · VirusTotal API · pytest
**🔗 [Live demo](https://email-threat-analyzer-zt7f.onrender.com)** · **[Code](https://github.com/AhmedDAH1/email-threat-analyzer)**

### 🚨 Log Threat Detector — SIEM-Style Log Analysis & Correlation
[![Live Demo](https://img.shields.io/badge/Live_Demo-Online-success?style=flat-square)](https://log-threat-detector.onrender.com)
[![Code](https://img.shields.io/badge/Code-GitHub-181717?style=flat-square&logo=github)](https://github.com/AhmedDAH1/log_threat_detector)

Ingests SSH, Apache, and syslog files to detect brute-force attempts, port scans, and anomalies; correlation engine identifies cross-source attack patterns. Real-time Flask + WebSocket dashboard, AbuseIPDB enrichment, email alerting, SQLite persistence. Containerized.

**Tech:** Python · Flask · SQLite · AbuseIPDB API · Chart.js
**🔗 [Live demo](https://log-threat-detector.onrender.com)** · **[Code](https://github.com/AhmedDAH1/log_threat_detector)**

### 📡 Network Scanner — Multi-Threaded Network Reconnaissance
[![Live Demo](https://img.shields.io/badge/Live_Demo-Online-success?style=flat-square)](https://network-scanner-8ihy.onrender.com)
[![Code](https://img.shields.io/badge/Code-GitHub-181717?style=flat-square&logo=github)](https://github.com/AhmedDAH1/network-scanner)

Scapy-based scanner with ARP/ICMP host discovery, multi-threaded SYN/UDP port scanning, TTL-based OS fingerprinting, MAC vendor lookup, and CVE vulnerability lookup. Web dashboard with live scan streaming. Docker with least-privilege capabilities (NET_RAW, never `--privileged`).

**Tech:** Python · Scapy · Docker · Flask
**🔗 [Live demo](https://network-scanner-8ihy.onrender.com)** · **[Code](https://github.com/AhmedDAH1/network-scanner)**

### 🎯 Attack Surface Mapper — Security Assessment Platform
[![Code](https://img.shields.io/badge/Code-GitHub-181717?style=flat-square&logo=github)](https://github.com/AhmedDAH1/attack-surface-mapper)

Automated vulnerability scanning with MITRE ATT&CK technique mapping and compliance checks against PCI-DSS v4.0, NIST CSF, and CIS Controls v8. Three interfaces (CLI, terminal dashboard, web UI), Shodan exposure checks, Slack alerting, multi-format reporting (PDF/HTML/CSV/JSON). 23 tests.

**Tech:** Python · Flask-SocketIO · MITRE ATT&CK · Shodan
**[Code](https://github.com/AhmedDAH1/attack-surface-mapper)**

---

## 🔧 Technical Skills

**Security & Blue Team** — Threat Detection · Incident Response · SIEM Concepts · Log Analysis · IOC Extraction · MITRE ATT&CK · Phishing Analysis · Threat Intelligence (VirusTotal, AbuseIPDB, Shodan) · Packet Analysis (Wireshark) · Vulnerability Assessment

**Development** — Python (FastAPI, Flask, asyncio, Scapy) · REST APIs · PostgreSQL · SQLite · Docker · GitHub Actions CI/CD · Linux / Bash · pytest · Git

**Learning** — Penetration Testing (Metasploit, Burp Suite, Nmap) · MISP / OpenCTI · STIX/TAXII

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

## 🎓 Education & Certifications

**B.Sc. Software Engineering** — Zhengzhou University · 2021–2027

| Status | Certification |
|--------|--------------|
| 🔄 In progress | CompTIA Security+ (target Q3 2026) |
| ✅ Completed | Cisco Endpoint Security |
| ✅ Completed | Cisco Introduction to Cybersecurity |
| ✅ Completed | Python Security Fundamentals |

**Practice:** TryHackMe (SOC Level 1 path) · PicoCTF (Web Exploitation, Forensics)

---

## 🎯 What I'm Looking For

Seeking an **entry-level SOC Analyst** role where I can work on threat detection, incident response, security automation, and threat-intelligence-driven detection workflows — remote or relocation.

📧 [adahdouh123@gmail.com](mailto:adahdouh123@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/ahmed-dahdouh) · 🔗 [github.com/AhmedDAH1](https://github.com/AhmedDAH1?tab=repositories)
