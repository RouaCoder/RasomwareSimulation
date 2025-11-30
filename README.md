<h1 align="center">🛡️ Red & Blue Team Ransomware Simulation Project</h1>
<p align="center"><strong>Educational Cybersecurity Lab – Detection, Response & Forensics</strong></p>

<p align="center">

  <!-- Project Identity -->
  <img src="https://img.shields.io/badge/Red%20%26%20Blue%20Team%20Simulation-Project-8A2BE2?style=for-the-badge">

  <!-- Virtual Machines -->
  <img src="https://img.shields.io/badge/Windows%2010-Victim%20Machine-0078D6?style=for-the-badge&logo=windows">
  <img src="https://img.shields.io/badge/Kali%20Linux-Attacker%20Machine-557C94?style=for-the-badge&logo=kalilinux">

  <!-- Tools Used -->
  <img src="https://img.shields.io/badge/Metasploit-Payload%20Generation-critical?style=for-the-badge&logo=metasploit">
  <img src="https://img.shields.io/badge/Python-HTTP%20Server-3776AB?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/PowerShell-Real--time%20Detection-2CA5E0?style=for-the-badge&logo=powershell">

  <!-- Category -->
  <img src="https://img.shields.io/badge/Category-Educational%20Cybersecurity-green?style=for-the-badge">

  <!-- Status -->
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">

</p>


## 📘 Overview

This project is a full **Red Team / Blue Team ransomware simulation**, built to reproduce—safely and ethically—the full lifecycle of a ransomware incident inside an isolated cybersecurity lab.

It demonstrates:

- How an attacker infiltrates a system and executes a ransomware-like payload (Red Team)
- How a defender detects, contains, analyzes, and recovers from the attack (Blue Team)

⚠️ **This project is strictly educational** and follows safe cybersecurity practices.  
All activities were performed inside isolated virtual machines.

### 🏗️ Project Features

## 🔴 Red Team Capabilities
- Reverse shell payload generation (msfvenom)
- Remote execution through Meterpreter
- File encryption demonstration (educational only)
- Ransom note deployment
- Payload hosting via Python HTTP server

## 🔵 Blue Team Capabilities
- Real-time ransomware detection (PowerShell)
- Automated isolation & process kill
- Logging and forensic evidence extraction
- Real-time secure data backup
- BitLocker drive protection
- System recovery workflow

## ✔ Backup & Recovery Strategy

Multiple mechanisms were evaluated:

| Backup Method | Purpose |
|--------------|----------|
| **Custom PowerShell Real-Time Backup** | Immediate protection + mirroring |
| **BitLocker** | Data-at-rest encryption |
| **Windows Backup (System Image)** | Complete system recovery |
| **OneDrive Versioning** | Rollback for corrupted/encrypted files |

➡️ **Final solution implemented:**  
✔ Custom Real-Time PowerShell backup with integrity checks.

# 🧪 Environment & Architecture

### 🖥️ Lab Setup

- **Attacker Machine:** Kali Linux VM  
- **Victim Machine:** Windows 10 VM  
- **Communication:** Reverse TCP payload  

### 🔧 Tools Used

- Metasploit Framework  
- Python HTTP Server  
- PowerShell (detection, IR, backup automation)  
- BitLocker  
- Sysinternals  
- Event Viewer  

# 🎥 Demonstration Video



[Watch the SOC Lab Demo](https://drive.google.com/uc?export=download&id=1jdWfefYc3i3klt-1_D9e2Q8UV2sW9uYN)





# 🛑 Ethical Notice

This project is strictly for:

- ✔ Academic research  
- ✔ Cybersecurity training  
- ✔ Isolated testing environments  
- ✔ Understanding ransomware behavior  

Never deploy offensive tools or scripts outside authorized laboratory conditions.


<p align="center">🛡️ <strong>Red Team vs Blue Team — Understanding Both Sides Strengthens Defense</strong> 🛡️</p>

          

