# Security Procedure Intake Questionnaire

This project provides a web-based questionnaire designed to collect the necessary information to build **audit-ready cybersecurity procedures** aligned with a System Security Plan (SSP) and control framework (NIST 800-53 / CMMC / GRC).

## 🔍 Overview

The questionnaire is used during the **procedure development phase** to gather:

- Systems and applications in use
- Cloud platforms and infrastructure
- Security tools and identity systems
- Roles, responsibilities, and approval workflows
- Operational processes (account management, incident response, patching, etc.)
- Evidence and documentation practices

This ensures procedures are:
- Accurate to the environment
- Operationally realistic
- Audit-defensible

The form is implemented as a single HTML file:
- :contentReference[oaicite:0]{index=0}

## 🚀 Features

- Structured sections aligned to security control families:
  - AC-2 (Account Management)
  - IA (Authentication)
  - IR (Incident Response)
  - SI-2 (Patch Management)
  - CM-3 (Change Management)
  - CA-7 (Continuous Monitoring)
  - CP-9 / CP-10 (Backup & Recovery)
- Environment & Systems Overview (applications, tools, data locations)
- Required fields for critical inputs
- Export options:
  - JSON
  - CSV
- Copy summary to clipboard
- Print / Save as PDF
- Clean UI for client walkthroughs

## 🧱 How to Use

### Option 1 – Direct Use
1. Open `index.html` in a browser
2. Complete the questionnaire
3. Export results (JSON/CSV) or print to PDF

### Option 2 – Client Walkthrough
- Share screen and complete live with stakeholders
- Capture accurate operational workflows
- Validate assumptions in real time

### Option 3 – GitHub Pages (Recommended)
Host as a live form:

1. Go to **Settings → Pages**
2. Set:
   - Source: `main`
   - Folder: `/root`
3. Access via: https://YOUR_USERNAME.github.io/unitron-procedure-questionnaire/

## 🎯 Purpose

This tool bridges the gap between:
- **Policies & SSP (what should exist)**  
and  
- **Procedures (how things actually work)**

It enables development of:
- Real-world procedures
- Evidence-driven controls
- Audit-ready documentation

## ⚠️ Security Notice

Do NOT enter:
- Passwords
- API keys
- Secrets
- Sensitive client data

Only describe:
- Locations
- Processes
- Tools

## 🧠 Next Steps

After completing the questionnaire:
1. Build procedures (AC-2, IA, IR-4, SI-2, etc.)
2. Map procedures to SSP controls
3. Define evidence requirements
4. Validate against real operations

## 📌 Author

Anthony Saunders  
Product Security / GRC / Cybersecurity Strategy

---
Go into code and change the heading company name to one you are using. 
