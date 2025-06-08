---
title: "Lab challenges"
permalink: /labchallenges/
layout: tags
author_profile: true
---


## 🧪 Lab Challenges

### 🔐 Challenge 1: SQL Injection (Web Security Fundamentals)  
**Platform:** TryHackMe  
**Problem Statement:** Exploit a vulnerable login page using SQL injection to bypass authentication.  
**Approach:**  
- Identified the input field was vulnerable to SQLi using `' OR '1'='1`.  
- Used `sqlmap` to automate database enumeration.  
**Tools Used:** Burp Suite, sqlmap, browser dev tools  
**Screenshot:**  
![SQLi Screenshot](/assets/images/sqli_lab.png)  
**Lessons Learned:**  
- Gained hands-on experience with input sanitization flaws.  
- Learned how to identify and test for SQL injection manually and with tools.

---

### 🛡️ Challenge 2: Broken Authentication  
**Platform:** OWASP Juice Shop  
**Problem Statement:** Gain unauthorized access to a user account.  
**Approach:**  
- Discovered weak password reset implementation.  
- Used predictable token to reset another user’s password.  
**Tools Used:** Burp Suite, Firefox Dev Tools  
**Screenshot:**  
![Broken Auth](/assets/images/broken_auth.png)  
**Lessons Learned:**  
- Understood the importance of secure token generation and session management.  

---

### 🧠 Challenge 3: Basic Linux Privilege Escalation  
**Platform:** Hack The Box  
**Problem Statement:** Gain root access on a Linux box with limited user access.  
**Approach:**  
- Enumerated sudo rights with `sudo -l`  
- Exploited `nano` with elevated permissions  
**Tools Used:** LinPEAS, GTFOBins, SSH  
**Screenshot:**  
![Privilege Escalation](/assets/images/linux_privesc.png)  
**Lessons Learned:**  
- Importance of Linux enumeration  
- How misconfigured sudo permissions can be escalated

---

### 🧩 Challenge 4: Steganography - Hidden Flag in Image  
**Platform:** PicoCTF  
**Problem Statement:** Extract a hidden message/flag embedded in an image.  
**Approach:**  
- Used `steghide` and `zsteg` for analysis  
- Discovered flag hidden in LSB (Least Significant Bit)  
**Tools Used:** steghide, zsteg, binwalk  
**Lessons Learned:**  
- How digital images can be manipulated to carry hidden data  
- Improved attention to file metadata and encoding

---


