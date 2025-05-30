# VulnScan - Application & API Security Testing Lab 🔍

VulnScan is a hands-on lab and automation toolkit designed to simulate real-world application and API vulnerabilities. This project demonstrates the end-to-end workflow of identifying, exploiting, and reporting security issues in web and API environments.

## 🔧 Features

- Automated scanning using Python, Burp Suite API, and OWASP ZAP
- OWASP Top 10 focused vulnerability testing
- API security tests with Postman and Fiddler
- Dockerized vulnerable apps (DVWA, Juice Shop, WebGoat)
- Markdown-based report templates for SDLC integration

## 🧰 Tools Used

- Burp Suite
- OWASP ZAP
- Postman, Fiddler
- Nikto, Nmap
- Python, Bash
- Docker

## 📂 Folder Structure

- `scan_scripts/`: Scripts to automate and customize tests
- `reports/`: Markdown reports with detailed findings
- `config/`: Target list and environment setup
- `docs/`: Diagrams, test cases, and system design

## 🚀 Getting Started

```bash
git clone https://github.com/yourusername/VulnScan-AppSecLab.git
cd VulnScan-AppSecLab
pip install -r requirements.txt
python scan_scripts/vulnscan_web.py

