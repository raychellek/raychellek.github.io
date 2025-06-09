---
title: "Lab challenges"
permalink: /labchallenges/
layout: tags
author_profile: true
---


## 🔬 Lab Challenges

### 🧩 Challenge 1: Getting Started — Hack The Box  
**Problem Statement:** Understand the structure of HTB labs, access an instance, and retrieve your first flag.  
**Approach:**  
- Set up a VPN connection to access HTB’s private network.  
- Launched the target machine and used enumeration techniques to discover the web server.  
- Found a hidden flag by inspecting the source code.  
**Tools Used:** OpenVPN, browser dev tools, basic `nmap`  
**Lessons Learned:**  
- Importance of connectivity and setup in a penetration testing lab.  
- Basic enumeration can reveal valuable information with minimal tools.

---

### 🐍 Challenge 2: Python Basics — TryHackMe  
**Problem Statement:** Learn foundational Python skills for cybersecurity tasks.  
**Approach:**  
- Wrote Python scripts for basic operations like file handling, loops, and conditionals.  
- Practiced automation tasks like reading from logs and making requests to web APIs.  
**Tools Used:** Python 3, VS Code, terminal  
**Lessons Learned:**  
- Scripting can speed up repetitive tasks in cybersecurity.  
- Understanding Python is key for both offensive and defensive roles.

---

### 🔎 Challenge 3: Passive Reconnaissance — TryHackMe  
**Problem Statement:** Perform passive reconnaissance without directly interacting with the target system.  
**Approach:**  
- Used WHOIS, DNS lookups, and Google dorking to gather info.  
- Discovered subdomains and public metadata using passive OSINT tools.  
**Tools Used:** `whois`, `nslookup`, `theHarvester`, `crt.sh`  
**Lessons Learned:**  
- Passive recon helps you stay stealthy and avoid detection.  
- A lot of information is already publicly available — if you know where to look.

---

### 🌐 Challenge 4: DNS in Detail — TryHackMe  
**Problem Statement:** Understand how the DNS system works and how it can be leveraged during recon and attacks.  
**Approach:**  
- Studied different DNS record types (A, AAAA, MX, TXT, etc.).  
- Performed zone transfers and subdomain enumeration.  
- Analyzed how DNS poisoning and tunneling work.  
**Tools Used:** `dig`, `nslookup`, `dnsenum`, `fierce`  
**Lessons Learned:**  
- DNS is a vital protocol in the recon phase.  
- Misconfigured DNS can lead to major information leakage.

---

> 💡 Keep revisiting these labs periodically — especially as your skills grow. Each revisit reveals something new!



