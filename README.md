# RedEyeMap

**RedEyeMap** is an advanced, interactive extension and wrapper for `Nmap`. It is designed to simplify complex network scanning, service enumeration, and vulnerability testing through a sleek, menu-driven interface.

*Author: infinite667 - infinite667 ([@itsinfinite667](https://t.me/itsinfinite667))*

---

## Features

RedEyeMap provides an easy-to-use graphical terminal interface (via `xterm`) to launch various Nmap scans without needing to memorize complex flags.

**Core Capabilities:**
- **Automated Scanning & Output formatting**: Generate XML, HTML, normal, and grepable outputs automatically.
- **Vulnerability Scanning**: Over 70 built-in Nmap Scripting Engine (NSE) brute-force attacks (FTP, HTTP, MySQL, Oracle, SMB, SNMP, VNC, and many more).
- **Service Enumeration**: Easily launch targeted enumeration scripts for specific protocols.
- **Port Scanning Profiles**: Quick access to common scan types (stealth, aggressive, full port range).

## Requirements

The script checks for and requires the following dependencies:
- `nmap`
- `xterm`

*Note: You must be running this as `root` within an X (graphical) session. It has been tested on Parrot OS and Kali Linux.*

## Usage

```bash
# Ensure the script is executable
chmod +x redeyemap-1.sh

# Run the script as root
sudo ./redeyemap-1.sh
```

Once launched, follow the interactive terminal menus to select your target IP and the type of scan or attack you wish to perform.

---
**Disclaimer**: This tool is for educational purposes and authorized auditing only. Usage of RedEyeMap for attacking targets without prior mutual consent is illegal. It is the end user's responsibility to obey all applicable local, state, and federal laws.
