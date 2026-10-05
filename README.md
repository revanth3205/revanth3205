# 👋 Hi, I'm Kengana Revanth

### Cybersecurity Engineer in Progress · Security Researcher · Open-Source Contributor

<p align="center">
  <img src="https://img.shields.io/badge/Cybersecurity-Research-red?style=for-the-badge&logo=hackthebox&logoColor=white" />
  <img src="https://img.shields.io/badge/Penetration%20Testing-Active-black?style=for-the-badge&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/AI%20%26%20Security-Research-blue?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Open%20Source-Contributor-green?style=for-the-badge&logo=github&logoColor=white" />
</p>

<p align="center">
  <b>Cybersecurity undergraduate focused on offensive security, vulnerability research, security engineering, and AI-driven threat detection.</b>
</p>

---

## 🧑‍💻 About Me

I'm a **B.Tech Computer Science & Engineering student specializing in Cyber Security** at the Indian Institute of Information Technology, Kottayam.

My work sits at the intersection of:

* 🔴 **Web & API Security**
* ⚔️ **Penetration Testing & Vulnerability Assessment**
* 🔬 **Vulnerability Research**
* 🛡️ **Security Engineering**
* 🤖 **AI-driven Threat Detection**
* 🌐 **Network Security**
* 🔎 **Digital Forensics & OSINT**
* 🌍 **Open-Source Security**

I prefer learning by building — security scanners, defensive systems, detection frameworks, forensic investigations, CTF challenges, and real-world vulnerability research.

Currently exploring how **AI can augment both offensive security assessment and defensive detection systems**.

---

# 🏆 Open-Source Security Contributions

### Rapid7 Metasploit Framework

**Open-Source Security Contributor · 2 Merged PRs · 2026**

#### 🔧 PR #21882 — Linux Persistence Module Validation

* Fixed incorrect `WritableDir` validation across **8 Linux/multi persistence modules**.
* Replaced incorrect `exists?` checks with appropriate `directory?` validation.
* Tested the changes against a **Metasploitable2** environment.
* Added validation and regression coverage.
* PR merged into `rapid7/master`.

#### 🧪 PR #21947 — Frozen DNS Question Regression

* Added regression coverage for `Net::DNS::Question#check`.
* Addressed a `FrozenError` caused by mutation of frozen DNS question names.
* Verified the implementation with **RSpec, RuboCop, msftidy, msfconsole, and functional testing**.
* PR merged into `rapid7/master`.

> Contributing to a widely used penetration-testing framework has been one of my most valuable experiences in understanding production security tooling, testing, debugging, and secure code changes.

---

# 🔬 Vulnerability Research

### HackWithIndia — Vulnerability Disclosure Program

**Security Researcher · January 2026**

Identified and reported a **client-side game-logic vulnerability** that allowed manipulation of URL parameters to force unauthorized game-winning states.

### Research Process

```text
Application Analysis
        ↓
JavaScript Logic Review
        ↓
Parameter Manipulation
        ↓
Vulnerability Identification
        ↓
Proof of Concept
        ↓
Impact Analysis
        ↓
Responsible Disclosure
```

The report included reproduction steps, proof-of-concept evidence, impact analysis, and remediation recommendations.

---

# 🚀 Featured Projects

## 🧠 AI-Driven Adaptive Intrusion Detection & Network Threat Intelligence

Research project focused on building an adaptive IDS using **Transformer-based temporal anomaly detection**.

### Focus

* Network traffic anomaly detection
* Temporal traffic analysis
* Multi-class attack classification
* Threat intelligence
* AI-assisted detection
* Security analytics

### Dataset

**CICIDS2017 — 2.8M+ network flows**

### Targeted Attack Categories

```text
DDoS / DoS
Port Scanning
Brute Force
SQL Injection
XSS
Botnet
Infiltration
Network Anomalies
```

### Stack

`Python` `Pandas` `NumPy` `Scikit-learn` `Matplotlib`

---

## 🕷️ WebSentry

### Modular Web Application Vulnerability Scanner

A Python-based security assessment framework designed around the **OWASP Top 10**.

### Capabilities

* 🔎 Reconnaissance
* 🕸️ Web crawling
* 🔍 Technology fingerprinting
* 💉 SQL Injection detection
* 🧪 XSS detection
* 🔐 CSRF analysis
* 🔑 IDOR testing
* ↪️ Open Redirect detection
* 📊 Confidence-based findings
* 📈 CVSS-based severity scoring
* 📄 Structured JSON reporting

### Architecture

```text
Target
  │
  ├── Reconnaissance
  │
  ├── Crawling
  │
  ├── Fingerprinting
  │
  ├── Endpoint Discovery
  │
  └── Vulnerability Detection
          │
          ├── SQLi
          ├── XSS
          ├── CSRF
          ├── IDOR
          └── Open Redirect
                    │
                    ↓
              Finding Engine
                    │
                    ↓
             CVSS + Confidence
                    │
                    ↓
              JSON Report
```

**Stack:** `Python` `Requests` `BeautifulSoup` `OWASP` `CVSS`

---

## 🛡️ AegisWAF

### Custom Web Application Firewall

A multithreaded reverse-proxy WAF designed to detect and mitigate common web attacks.

### Features

* SQL Injection detection
* XSS detection
* Command Injection detection
* IP blacklist / filtering
* Anomaly scoring
* Sliding-window rate limiting
* Structured security logging
* Modular rule engine
* Reverse-proxy architecture

**Stack:** `Python` `Regex` `JSON` `Multithreading` `HTTP`

---

# 💼 Experience

### Cybersecurity Research Intern

**RV University · Bengaluru**

**AI & Intrusion Detection · 2026**

Working on an AI-driven adaptive intrusion detection and network threat intelligence framework using **Transformer-based temporal anomaly detection**.

Areas of research include:

* Network anomaly detection
* IDS architectures
* Temporal traffic analysis
* Threat intelligence
* Machine-learning based detection
* Cyber-threat analytics

---

# 🧪 Security Research Areas

| Area                      | Focus                                                         |
| ------------------------- | ------------------------------------------------------------- |
| 🌐 Web Security           | OWASP Top 10, API Security, Authentication, Access Control    |
| ⚔️ Offensive Security     | VAPT, Pentesting, Reconnaissance, Enumeration                 |
| 🔬 Vulnerability Research | Root-cause analysis, PoC development, responsible disclosure  |
| 🛡️ Defensive Security    | WAF, IDS, anomaly detection, security monitoring              |
| 🤖 AI Security            | AI-assisted detection, anomaly detection, security automation |
| 🔎 DFIR                   | Disk forensics, metadata analysis, investigation              |
| 🌍 OSINT                  | Reconnaissance, information gathering, intelligence analysis  |

---

# 🛠️ Technical Arsenal

### Programming

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white"/>
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/Bash-121011?style=flat-square&logo=gnubash&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
</p>

### Offensive Security

<p>
<img src="https://img.shields.io/badge/Burp%20Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white"/>
<img src="https://img.shields.io/badge/OWASP-000000?style=flat-square&logo=owasp&logoColor=white"/>
<img src="https://img.shields.io/badge/Nmap-4682B4?style=flat-square"/>
<img src="https://img.shields.io/badge/Metasploit-2596CD?style=flat-square"/>
<img src="https://img.shields.io/badge/Nuclei-000000?style=flat-square"/>
<img src="https://img.shields.io/badge/SQLMap-CC0000?style=flat-square"/>
<img src="https://img.shields.io/badge/FFUF-000000?style=flat-square"/>
<img src="https://img.shields.io/badge/Gobuster-000000?style=flat-square"/>
</p>

### Network & Analysis

`Wireshark` `Nmap` `WhatWeb` `Amass` `Subfinder` `Nikto` `tcpdump`

### Digital Forensics / OSINT

`Autopsy` `FTK Imager` `ExifTool` `Volatility` `OSINT`

### Development & Infrastructure

`Git` `GitHub` `Docker` `Linux CLI` `VirtualBox` `VMware`

### Operating Systems

`Kali Linux` `Ubuntu` `Windows`

### Security Knowledge

`OWASP Top 10` `MITRE ATT&CK` `CVSS` `Web Security` `API Security` `Network Security` `VAPT` `DFIR`

---

# 📚 Currently Learning

```text
Web Application Security
        ↓
API Security
        ↓
Advanced Vulnerability Research
        ↓
AI-Augmented Security Testing
        ↓
SOC & Threat Detection
        ↓
Security Engineering
```

I'm continuously building practical labs and security tooling rather than limiting my learning to theoretical material.

---

# 🎯 Current Focus

### 🔴 Offensive Security

* Web application penetration testing
* API security testing
* Vulnerability research
* Reconnaissance & attack-surface discovery
* OWASP methodology

### 🔵 Defensive Security

* Intrusion detection
* Network threat intelligence
* Security monitoring
* Anomaly detection
* Security engineering

### 🟣 AI + Cybersecurity

Exploring architectures where AI assists security workflows while keeping **deterministic security tooling, controlled execution, evidence-based findings, and human validation** at the core.

---

# 🏅 Certifications

### Certified Ethical Hacker (CEH v13)

**EC-Council — In Progress**

---

# 📊 GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=revanth3205&show_icons=true&theme=transparent&hide_border=true&rank_icon=github" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=revanth3205&layout=compact&theme=transparent&hide_border=true" height="165"/>
</p>

---

# 🤝 Let's Connect

<p align="center">

<a href="https://www.linkedin.com/in/revanth-kengana">
<img src="https://img.shields.io/badge/LinkedIn-Revanth%20Kengana-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://github.com/revanth3205">
<img src="https://img.shields.io/badge/GitHub-revanth3205-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="mailto:revanthkengana3205@gmail.com">
<img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

</p>

---

<p align="center">

### 🔐 Build. Break. Investigate. Defend.

*"Learning cybersecurity by building systems, breaking assumptions, and contributing back to the security community."*

</p>
