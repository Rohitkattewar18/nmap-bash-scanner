# nmap-bash-scanner

![image](https://github.com/user-attachments/assets/6752bf57-79bd-4404-863c-d0a3a90b5c36)

## Overview

This tool helps users perform essential network scans such as:
- Host availability (ping scan)
- Open ports
- Operating system and service detection

All scan results are saved in organized text files within a results/ directory.

---

## Features

- Accepts IP address or domain as input
- Automates:
  - Ping scan
  - Full port scan
  - OS and version detection
- Saves results to results/<target>_scan.txt

---

## Prerequisites

- A Linux/Unix system
- nmap installed:
  ```bash
  sudo apt update
  sudo apt install nmap
  ```
  
