# 🛑 WannaCry Attack Simulation (Controlled Lab)

## 📌 Overview
This project demonstrates a **WannaCry-style ransomware attack simulation** performed in a controlled lab environment.  

The objective was to understand how attackers exploit **SMBv1 vulnerability (MS17-010)** using EternalBlue and deploy ransomware on a vulnerable Windows system.

---

## 🎯 Objectives
- Identify vulnerable systems using Nmap
- Exploit MS17-010 (EternalBlue)
- Gain remote access using Metasploit
- Deploy a WannaCry-like payload
- Observe real-world ransomware behavior

---

## 🛠 Tools Used
- Kali Linux
- Metasploit Framework
- Nmap
- Windows 7 (Vulnerable VM)
- Oracle VirtualBox

---

## ⚙️ Lab Setup

Two virtual machines were configured:

- Attacker: Kali Linux
- Victim: Windows 7 (SMBv1 enabled)

Both systems were connected via NAT Network.
![wannacry10](https://github.com/user-attachments/assets/38372bd5-26ae-48d5-b873-e72102f85db9)

---
## 🔍 Step 1: Reconnaissance (Nmap Scan)

Scanning target machine to identify open ports.

```bash
nmap -sV 10.0.2.15
![Wannacry1](https://github.com/user-attachments/assets/b6a5565c-ee45-454a-b563-68011dfb599b)

---
## 🔍 Step 2: Vulnerability Detection 


