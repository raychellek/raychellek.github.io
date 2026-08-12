---
title: "Lab challenges"
permalink: /labchallenges/
layout: tags
author_profile: true
---


## 🔬 Lab Challenges

### 🧩 Challenge 1: Getting Started — Hack The Box

**Problem Statement:** Get familiar with the HTB lab environment, establish connectivity, and retrieve the first flag.
**Approach:**

* Configured an OpenVPN connection to access the HTB private network.
* Started the target machine and performed basic network enumeration using `nmap`.
* Identified the web server and inspected the page source to locate the hidden flag.

**Tools Used:** OpenVPN, browser developer tools, `nmap`

**Lessons Learned:**

* Proper lab connectivity and environment setup are essential before beginning a penetration testing assessment.
* Basic enumeration can quickly reveal useful information about a target.

---

### 🐍 Challenge 2: Python Basics — TryHackMe

**Problem Statement:** Build a foundation in Python and understand how scripting can support cybersecurity tasks.
**Approach:**

* Practiced Python fundamentals including variables, conditional statements, loops, functions, and data structures.
* Worked through exercises involving file handling and basic scripting.

**Tools Used:** Python 3, VS Code, terminal

**Lessons Learned:**

* Python can be used to automate repetitive tasks and support security analysis.
* Strong programming fundamentals provide a foundation for developing practical cybersecurity scripts.

---

### 🔎 Challenge 3: Passive Reconnaissance — TryHackMe

**Problem Statement:** Gather information about a target through passive reconnaissance techniques without directly interacting with its systems.
**Approach:**

* Used `whois` to gather domain registration and name server information.
* Used `nslookup` and `dig` to investigate DNS records.
* Used `crt.sh` and DNSDumpster to identify potential subdomains.
* Used Shodan to investigate publicly exposed services and infrastructure.

**Tools Used:** `whois`, `nslookup`, `dig`, DNSDumpster, `crt.sh`, Shodan

**Lessons Learned:**

* Publicly available information can provide significant insight into a target's infrastructure before direct testing begins.
* Passive reconnaissance is useful for identifying domains, subdomains, and publicly exposed services.

---

### 🌐 Challenge 4: DNS in Detail — TryHackMe

**Problem Statement:** Understand how DNS operates and how DNS information can be used during reconnaissance.
**Approach:**

* Studied the DNS hierarchy, including root servers, TLD servers, recursive resolvers, and authoritative name servers.
* Examined common DNS records including A, AAAA, CNAME, and MX records.
* Used DNS queries to understand the resolution process and the role of TTL values in DNS caching.

**Tools Used:** `dig`, `nslookup`, DNS

**Lessons Learned:**

* Understanding DNS is important when mapping an organization's domains and network infrastructure.
* DNS records can expose useful information during the reconnaissance phase of a security assessment.

---

### 🛡️ Challenge 5: Junior Security Analyst Intro — TryHackMe

**Problem Statement:** Gain practical exposure to the responsibilities of a Junior Security Analyst working within a Security Operations Center.
**Approach:**

* Worked through a simulated SOC environment and investigated security alerts.
* Reviewed alerts, identified a malicious IP address, and determined the appropriate response and escalation path.
* Worked through scenarios involving phishing, ransomware, and information-stealing malware.

**Tools Used:** TryHackMe SOC environment, security alert dashboard, firewall concepts

**Lessons Learned:**

* Developed a better understanding of SOC workflows, including alert monitoring, investigation, and escalation.
* Learned how analysts assess security events and determine appropriate actions during an incident.

---

### 🪟 Challenge 6: Windows Forensics 1 — TryHackMe

**Problem Statement:** Understand how Windows Registry artifacts can be used as evidence during digital forensic investigations.
**Approach:**

* Studied the structure of the Windows Registry and the purpose of its major registry hives.
* Examined artifacts from `SAM`, `SYSTEM`, `SOFTWARE`, and `NTUSER.DAT`.
* Used forensic tools including Registry Explorer, RegRipper, Autopsy, and FTK Imager.
* Investigated artifacts such as UserAssist to identify evidence of application and user activity.

**Tools Used:** Registry Explorer, RegRipper, Autopsy, FTK Imager

**Lessons Learned:**

* Windows Registry artifacts can provide valuable evidence about system configuration and user activity.
* Combining multiple forensic artifacts can help establish a clearer timeline of activity on a Windows system.

---

### 🕵️ Challenge 7: Threat Intelligence Tools — TryHackMe

**Problem Statement:** Explore OSINT and threat intelligence tools used to investigate potential security threats and indicators of compromise.
**Approach:**

* Used UrlScan.io to investigate URLs and identify related domains, IP addresses, technologies, and other information.
* Explored Abuse.ch resources including MalwareBazaar, Feodo Tracker, URLhaus, and ThreatFox.
* Used PhishTool to analyze phishing emails and Cisco Talos to investigate IP and domain reputation.

**Tools Used:** UrlScan.io, MalwareBazaar, Feodo Tracker, URLhaus, ThreatFox, PhishTool, Cisco Talos

**Lessons Learned:**

* Threat intelligence platforms can provide valuable context when investigating suspicious domains, files, IP addresses, and phishing attempts.
* Correlating information from multiple intelligence sources can improve the accuracy of a threat assessment.

---

### 🖧 Challenge 8: L2 MAC Flooding & ARP Spoofing — TryHackMe

**Problem Statement:** Understand Layer 2 attacks involving MAC flooding and ARP cache poisoning and their role in man-in-the-middle attacks.
**Approach:**

* Studied how Ethernet switches maintain and use MAC address tables to forward traffic.
* Explored MAC flooding and its effect on switch MAC address tables.
* Studied ARP cache poisoning and how manipulated ARP mappings can redirect network traffic.
* Examined how these techniques can be used to facilitate a man-in-the-middle attack.

**Tools Used:** Wireshark, ARP, MAC flooding concepts

**Lessons Learned:**

* Understanding ARP and MAC address behavior is important when analyzing Layer 2 network attacks.
* Network segmentation, monitoring, and appropriate security controls can help mitigate these types of attacks.

---

### 📋 Challenge 9: Intro to Log Analysis — TryHackMe

**Problem Statement:** Learn the fundamentals of log analysis and how logs can be used for security monitoring and incident investigation.
**Approach:**

* Studied different types of logs, including system, security, application, network, and web server logs.
* Learned how timestamps, event information, and source details can help establish context during an investigation.
* Analyzed Apache logs using command-line tools to search for relevant activity and patterns.

**Tools Used:** Linux command-line tools, Apache logs, TryHackMe AttackBox

**Lessons Learned:**

* Log analysis can help establish a timeline and identify suspicious activity during an investigation.
* Efficiently searching and filtering logs is an important skill for security monitoring and incident response.

---

### 🏢 Challenge 10: Attacktive Directory — TryHackMe

**Problem Statement:** Assess a vulnerable Active Directory environment and identify weaknesses within a simulated corporate network.
**Approach:**

* Performed initial enumeration of the target and identified exposed services.
* Used `nmap` to identify open ports and gather information about the target environment.
* Investigated the exposed services and Active Directory environment to identify potential attack paths.

**Tools Used:** `nmap`, Active Directory enumeration tools, TryHackMe

**Lessons Learned:**

* Thorough enumeration is important when assessing an Active Directory environment.
* Understanding exposed services and domain configurations can help identify potential security weaknesses.

---

### 📶 Challenge 11: WiFi Hacking 101 — TryHackMe

**Problem Statement:** Understand WPA/WPA2 wireless security and common techniques used to assess wireless networks.
**Approach:**

* Studied wireless networking concepts including SSID, BSSID, WPA2-PSK, WPA2-EAP, and RADIUS.
* Examined the WPA/WPA2 four-way handshake and its role in client authentication.
* Explored how captured authentication information can be used to assess the security of a wireless network in a controlled environment.

**Tools Used:** Aircrack-ng concepts, WPA/WPA2, TryHackMe wireless lab

**Lessons Learned:**

* Understanding the WPA/WPA2 authentication process helps identify potential weaknesses in wireless security.
* Strong authentication and properly configured wireless networks are important for reducing wireless security risks.

---

### 🦠 Challenge 12: MAL: Malware Introductory — TryHackMe

**Problem Statement:** Gain an introduction to malware analysis and understand the techniques used to investigate malicious software.
**Approach:**

* Studied different malware types and the ways malware can be delivered, executed, and propagated.
* Explored stages of a malware attack, including execution, persistence, and propagation.
* Reviewed static analysis techniques and tools used to examine Portable Executable (PE) files.
* Examined real-world malware examples such as Stuxnet and WannaCry.

**Tools Used:** PEview, PeID, PE Explorer, IDA Freeware, WinDbg

**Lessons Learned:**

* Malware analysis can provide insight into how malicious software operates and affects a system.
* Static analysis is a useful starting point for examining malware characteristics and identifying potential indicators of compromise.


