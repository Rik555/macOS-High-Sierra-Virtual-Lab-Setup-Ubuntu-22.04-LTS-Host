# macOS-High-Sierra-Virtual-Lab-Setup-Ubuntu-22.04-LTS-Host
This project documents the successful deployment and configuration of a VirtualBox-based lab environment on older macOS hardware (High Sierra). The purpose was to create a secure, isolated sandbox for hands-on practice with Command Line Interface (CLI) tools, network diagnostics, and system log analysis without compromising the host machine.
# macOS-High-Sierra-Virtual-Lab-Setup (Ubuntu 22.04 LTS)

## 🧠 Overview
Created a secure, isolated virtual lab environment on macOS High Sierra for cybersecurity practice.  
Configured Ubuntu 22.04 LTS VM for network scanning, system hardening, and basic security analysis.

## 🧰 Tools & Technologies
- macOS High Sierra (Host)
- VirtualBox 6.1.50
- Ubuntu 22.04 LTS (Guest)
- CompTIA Security+ toolkit (Nmap, Wireshark, etc.)
  
- ## 🧠 Project Overview
This virtual lab was created to simulate a secure, isolated environment for hands-on cybersecurity practice.  
It allows testing and analysis of network tools without compromising the host system.

## 🧩 Skills Demonstrated
- Virtualization setup (Oracle VirtualBox)
- Operating system installation (Ubuntu 22.04 LTS)
- Linux command-line administration
- Network scanning & traffic analysis (Nmap, Wireshark)
- System updates, package management (APT)
- Documentation and version control (Git & GitHub)
- Understanding of CompTIA Security+ concepts in practice

## ⚙️ Setup Instructions
1. Install [VirtualBox 6.1.50](https://www.virtualbox.org/wiki/Downloads)
2. Download Ubuntu 22.04 LTS ISO
3. Create a new VM with:
   - 2 GB RAM
   - 2048 MB base memory
   - VMSVGA Graphics controller 
   - 2 CPUs
   - 15 GB storage
4. Boot from ISO and install Ubuntu
5. Install tools:
   
   ```bash
   sudo apt update && sudo apt install -y nmap wireshark net-tools
