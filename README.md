# Beee ReconTool 🐝 - Advanced Reconnaissance Framework

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20Mac-lightgrey)

        ██████╗ ███████╗███████╗███████╗        🐝     
        ██╔══██╗██╔════╝██╔════╝██╔════╝        🐝          
        ██████╔╝█████╗  █████╗  █████╗          🐝🐝🐝🐝    
        ██╔══██╗██╔══╝  ██╔══╝  ██╔══╝          🐝       🐝         
        ██████╔╝███████╗███████╗███████╗        🐝       🐝            
        ╚═════╝ ╚══════╝╚══════╝╚══════╝        🐝🐝🐝🐝    
        
                Advanced Reconnaissance Tool 
                
**Beee ReconTool** is a comprehensive Python-based reconnaissance and security assessment platform designed for cybersecurity professionals, penetration testers, and ethical hackers. This tool provides both passive and active reconnaissance capabilities through an intuitive, menu-driven interface.

# 📖 Table of Contents

- [Features](#-features)
- [Installation](#-installation)
- [Usage](#-usage)
- [Modules](#-modules)
- [Project Structure](#-project-structure)
- [Contributing](#-contributing)
- [License](#-license)
- [Disclaimer](#-legal-disclaimer)

## 🚀 Features

### 🔍 Passive Reconnaissance
- **WHOIS Lookup**: Advanced domain registration information with privacy detection
- **DNS Enumeration**: Comprehensive DNS record analysis (A, AAAA, MX, TXT, NS, SOA)
- **Subdomain Discovery**: Automated subdomain enumeration with multiple techniques

### ⚡ Active Reconnaissance  
- **Port Scanning**: Multi-threaded port scanning (SYN, Connect, UDP modes)
- **Service Banner Analysis**: Service identification and banner grabbing
- **Technology Detection**: Web technology stack fingerprinting

### 📊 Reporting & Analysis
- **HTML Reports**: Professional, detailed assessment reports
- **Data Visualization**: Clean, organized presentation of findings
- **Interactive Menu System**: User-friendly command-line interface

## 🛠️ Installation

### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)

### Quick Setup
```bash
# Clone the repository
git clone https://github.com/yourusername/Beee_ReconTool.git
cd Beee_ReconTool

# Install dependencies
pip install -r requirements.txt

# Run the tool
python main.py
```

## 🎯 Usage
### Basic Operation
```bash
python main.py
```
### Interactive Menu System

The tool provides an intuitive menu-driven interface:

1. Select reconnaissance type (Passive/Active/Full)
2. Enter target (domain or IP address)
3. Choose specific modules to execute
4. View results in real-time
5. Generate reports in HTML format

#### Example Session
```text
➤ Enter Target (domain or IP address):
>>> www.acrodesk.com

Starting WHOIS lookup...
WHOIS lookup completed!

Starting DNS enumeration...
DNS enumeration completed!

Generate report? (y/n): y
Report filename (default: report.html): 
Report generated at: reports/acrodesk_com_report.html
```
