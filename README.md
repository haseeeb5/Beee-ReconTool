🐝 Beee ReconTool - Advanced Reconnaissance Framework
https://img.shields.io/badge/Python-3.8%252B-blue
https://img.shields.io/badge/License-MIT-green
https://img.shields.io/badge/Platform-Windows%2520%257C%2520Linux%2520%257C%2520Mac-lightgrey

text
██████╗ ███████╗███████╗███████╗        🐝     
██╔══██╗██╔════╝██╔════╝██╔════╝        🐝          
██████╔╝█████╗  █████╗  █████╗          🐝🐝🐝🐝    
██╔══██╗██╔══╝  ██╔══╝  ██╔══╝          🐝       🐝         
██████╔╝███████╗███████╗███████╗        🐝       🐝            
╚═════╝ ╚══════╝╚══════╝╚══════╝        🐝🐝🐝🐝       
Beee ReconTool is a Python-based offensive security toolkit designed for automated reconnaissance. It supports both passive and active scanning, presenting findings in detailed HTML reports. Built for ethical hackers, penetration testers, and security researchers.

📖 Table of Contents
Features

Installation

Usage

Modules

Screenshots

Contributing

License

Disclaimer

🚀 Features
🔍 Passive Reconnaissance
WHOIS Lookup: Advanced domain registration information with privacy detection

DNS Enumeration: Comprehensive DNS record analysis (A, AAAA, MX, TXT, NS, SOA)

Subdomain Discovery: Automated subdomain enumeration with multiple techniques

⚡ Active Reconnaissance
Port Scanning: Multi-threaded port scanning (SYN, Connect, UDP modes)

Service Banner Analysis: Service identification and banner grabbing

Technology Detection: Web technology stack fingerprinting

📊 Reporting & Analysis
HTML Reports: Professional, detailed assessment reports

Data Visualization: Clean, organized presentation of findings

Export Capabilities: Multiple output formats for analysis

🛠️ Installation
Prerequisites
Python 3.8 or higher

pip (Python package manager)

Quick Setup
bash
# Clone the repository
git clone https://github.com/yourusername/Beee_ReconTool.git
cd Beee_ReconTool

# Install dependencies
pip install -r requirements.txt

# Run the tool
python main.py
Virtual Environment (Recommended)
bash
# Create virtual environment
python -m venv env

# Activate on Windows
.\env\Scripts\Activate.ps1

# Activate on Linux/Mac
source env/bin/activate

# Install dependencies
pip install -r requirements.txt
🎯 Usage
Basic Operation
bash
python main.py
Interactive Menu System
The tool provides an intuitive menu-driven interface:

Select reconnaissance type (Passive/Active/Full)

Enter target (domain or IP address)

Choose specific modules to execute

View results in real-time

Generate reports in HTML format

Example Session
text
➤ Enter domain/IP: example.com

✓ WHOIS data found
✓ DNS A, MX, TXT records collected  
✓ Subdomains discovered: www, blog, mail

→ HTML report generated: reports/example_report.html
📦 Modules Overview
Passive Modules
Module	Description	File
WHOIS Lookup	Domain registration analysis	modules/passive/who_is.py
DNS Enumeration	Complete DNS reconnaissance	modules/passive/dns_enum.py
Subdomain Discovery	Subdomain enumeration	modules/passive/subdomain.py
Active Modules
Module	Description	File
Port Scanning	Network port discovery	modules/active/port_scan.py
Banner Analysis	Service identification	modules/active/banners.py
Technology Detection	Web stack fingerprinting	modules/active/tech_detect.py
Utility Modules
Module	Description	File
Reporting	HTML report generation	modules/reporting.py
Async Runner	Task management	utils/async_runner.py
Logger	Comprehensive logging	utils/logger.py
🏗️ Project Structure
text
Beee_ReconTool/
├── main.py                  # Main entry point
├── modules/
│   ├── passive/             # WHOIS, DNS, Subdomain modules
│   └── active/              # Port scanning, banners, tech detection
├── utils/                   # Helper functions and utilities
├── templates/               # HTML report templates
├── reports/                 # Generated output reports
├── requirements.txt         # Python dependencies
├── README.md               # This file
└── LICENSE                 # MIT License
📋 Requirements
Dependencies are listed in requirements.txt:

rich==13.7.0

requests==2.31.0

python-whois==0.9.3

dnspython==2.4.2

python-nmap==0.7.1

beautifulsoup4==4.12.2

lxml==4.9.3

matplotlib==3.8.2

seaborn==0.13.0

and more...

🎨 Screenshots
Command Line Interface
text
        ██████╗ ███████╗███████╗███████╗        🐝     
        ██╔══██╗██╔════╝██╔════╝██╔════╝        🐝          
        ██████╔╝█████╗  █████╗  █████╗          🐝🐝🐝🐝    
        ██╔══██╗██╔══╝  ██╔══╝  ██╔══╝          🐝       🐝         
        ██████╔╝███████╗███████╗███████╗        🐝       🐝            
        ╚═════╝ ╚══════╝╚══════╝╚══════╝        🐝🐝🐝🐝       
         
                Advanced Reconnaissance Tool 
Sample Output
text
=== WHOIS Results ===
Domain: example.com
TLD: com

Registration Dates:
Created: 1995-08-14 (10000+ days ago)
Expires: 2024-08-13 (150 days) [ACTIVE]

Registrar:
Name: RESERVED-Internet Assigned Numbers Authority
🤝 Contributing
We welcome contributions! Here's how:

Fork the repository

Create a feature branch (git checkout -b feature/amazing-feature)

Commit your changes (git commit -m 'Add amazing feature')

Push to the branch (git push origin feature/amazing-feature)

Open a Pull Request

Development Setup
bash
# Install development dependencies
pip install -r requirements.txt

# Run the tool in development mode
python main.py
📄 License
Distributed under the MIT License. See LICENSE file for more information.

⚠️ Legal Disclaimer
This tool is designed for authorized security testing and educational purposes only.

🚨 IMPORTANT:

Obtain proper authorization before scanning any systems

Use only on networks you own or have explicit permission to test

The developers are not liable for misuse of this software

Compliance with local laws and regulations is your responsibility

🐛 Support
For bug reports and feature requests:

Check existing Issues

Create a new issue with detailed description

Include steps to reproduce and error logs

📞 Contact
Project Maintainer: [Your Name] - [your.email@example.com]

Project Link: https://github.com/yourusername/Beee_ReconTool

Beee ReconTool - Because reconnaissance shouldn't be a buzzkill! 🐝✨

"The more you know about your target, the better you can protect it."

