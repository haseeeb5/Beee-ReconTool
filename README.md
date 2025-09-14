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

1. **Select reconnaissance type** (Passive/Active/Full)
2. **Enter target** (domain or IP address)
3. **Choose specific modules** to execute
4. **View results** in real-time
5. **Generate reports** in HTML format

### Example Session
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

## 📦 Modules Overview

### Passive Modules
Module	Description	File
WHOIS Lookup	Domain registration analysis with privacy detection	modules/passive/who_is.py
DNS Enumeration	Complete DNS reconnaissance and record analysis	modules/passive/dns_enum.py
Subdomain Discovery	Subdomain enumeration with multiple techniques	modules/passive/subdomain.py
### Active Modules
Module	Description	File
Port Scanning	Multi-threaded network port discovery	modules/active/port_scan.py
Banner Analysis	Service identification and banner grabbing	modules/active/banners.py
Technology Detection	Web technology stack fingerprinting	modules/active/tech_detect.py
### Utility Modules
Module	Description	File
Reporting	Professional HTML report generation	modules/reporting.py
Async Runner	Asynchronous task management	utils/async_runner.py
Logger	Comprehensive logging system	utils/logger.py
Cache	Result caching functionality	utils/cache.py

## 🏗️ Project Structure
```text
Beee_ReconTool/
├── main.py                    # Main application entry point
├── modules/
│   ├── passive/               # Passive reconnaissance modules
│   │   ├── who_is.py         # WHOIS lookup functionality
│   │   ├── dns_enum.py       # DNS enumeration
│   │   └── subdomain.py      # Subdomain discovery
│   └── active/               # Active reconnaissance modules
│       ├── port_scan.py      # Port scanning
│       ├── banners.py        # Banner grabbing
│       └── tech_detect.py    # Technology detection
├── utils/                    # Utility functions
│   ├── async_runner.py       # Async task management
│   ├── logger.py            # Logging system
│   └── cache.py             # Result caching
├── templates/               # HTML report templates
├── reports/                # Generated output reports
├── requirements.txt        # Python dependencies
└── README.md              # Project documentation
```

## 📋 Dependencies
Key dependencies (see ```requirements.txt``` for complete list):

- ```rich==13.7.0``` - Beautiful terminal formatting
- ```requests==2.31.0``` - HTTP requests
- ```python-whois==0.9.3``` - WHOIS lookups
- ```dnspython==2.4.2``` - DNS enumeration
- ```python-nmap==0.7.1``` - Port scanning
- ```beautifulsoup4==4.12.2``` - HTML parsing
- ```lxml==4.9.3``` - XML processing
- ```matplotlib==3.8.2``` - Data visualization
- ```seaborn==0.13.0``` - Statistical visualizations
