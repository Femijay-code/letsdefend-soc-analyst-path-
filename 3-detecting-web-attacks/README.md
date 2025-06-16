# 🌐 Module 2: Detecting Web Attacks  
*Let’s Defend SOC Analyst Learning Path*

## 📘 Overview
This module covers several common attack techniques used to exploit web applications. I learned how these attacks work, how attackers automate them, and how defenders detect and respond using logs and behavior patterns.

## 🔐 Attacks Covered
- **SQL Injection (SQLi)** — and its 3 main types
- **Cross-Site Scripting (XSS)**
- **Command Injection**
- **IDOR (Insecure Direct Object Reference)**
- **RFI/LFI (Remote & Local File Inclusion)**
- **File Uploads leading to Web Shells**

## 🛠️ What I Learned
- Why detecting web attacks is critical for protecting web infrastructure
- How to identify common payload patterns in logs
- Signs of automated scanning activity (e.g., 50+ requests/sec)
- Tools attackers use to launch SQLi and similar attacks
- OWASP’s role in identifying and ranking these vulnerabilities

## 🧪 Practical Analysis: SQL Injection Detection

### 📄 Scenario:
- An SQL Injection attack was launched against the **`id` parameter** on the main page of the web application.
- Source IP: **192.168.31.174**
- Over **50 requests/second**, indicating an **automated vulnerability scanner** was used.
- Payloads were **complex**, confirming automation and tool-based exploitation.
- We could not determine if the attack was successful due to missing response size or outcome data.

### 🧠 What I Took Away:
- High-frequency requests + complex payloads = likely automation
- Payload inspection is critical for identifying scanning tools
- Even if results are unknown, logging and alerting is still vital to prevent future compromise

---

✅ This hands-on scenario improved my ability to recognize and analyze real-world web application threats using forensic log data.

*This content is part of my public documentation of the Let’s Defend SOC Analyst Path.*
