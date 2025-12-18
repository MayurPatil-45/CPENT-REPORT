
# 🧪 CPENT Module 5 – Internal Network Penetration Testing

## 📌 Module Overview

CPENT Module 5 focuses on **Internal Network Penetration Testing**, where attackers operate from inside the organization’s network. This module covers techniques used to identify, exploit, and escalate privileges within internal environments, including **Active Directory attacks, lateral movement, and post-exploitation** activities.

This module simulates real-world breach scenarios where perimeter defenses are bypassed or compromised.

---

## 🎯 Module Objectives

After completing this module, learners will be able to:

* Perform internal network reconnaissance
* Identify vulnerable hosts and services
* Exploit internal systems and misconfigurations
* Conduct Active Directory enumeration and attacks
* Perform privilege escalation and lateral movement
* Understand post-exploitation techniques
* Recommend defensive countermeasures

---

## 🧠 Topics Covered

* Internal Network Reconnaissance
* Host & Service Enumeration
* SMB, LDAP, Kerberos attacks
* Active Directory Enumeration
* Credential Access Techniques
* Privilege Escalation (Windows & Linux)
* Lateral Movement
* Pivoting & Tunneling
* Post-Exploitation
* Internal Network Reporting

---

## 🛠️ Tools Used

* **Nmap** – Internal network scanning and service detection
* **Netdiscover / ARP-scan** – Network discovery
* **BloodHound** – Active Directory attack path analysis
* **Mimikatz** – Credential dumping
* **CrackMapExec** – SMB and AD exploitation
* **Impacket** – NTLM relay and AD attacks
* **Responder** – LLMNR/NBT-NS poisoning
* **Metasploit Framework** – Exploitation and post-exploitation
* **PowerView / PowerSploit** – AD enumeration
* **PsExec** – Remote command execution

---

## 🔎 Attack Scenarios

* Compromised internal user machine
* Weak internal authentication controls
* Misconfigured Active Directory permissions
* Password reuse and weak credentials
* Insecure network segmentation

---

## 🛡️ Countermeasures & Defense

* Network segmentation and zero-trust architecture
* Strong password policies and credential hygiene
* Disable LLMNR and NBT-NS
* Implement Least Privilege access
* Use Multi-Factor Authentication (MFA)
* Regular patching and system hardening
* Active Directory security auditing
* Monitor lateral movement and suspicious authentication
* SOC monitoring using SIEM tools (Splunk, ELK)

---

## 🔐 SOC Detection Use Cases

* Detection of abnormal internal scans
* Monitoring failed and suspicious logins
* Identifying credential dumping behavior
* Lateral movement detection
* Alerting on privilege escalation attempts

---

## ⚠️ Disclaimer

> This module is intended strictly for **educational and authorized penetration testing purposes**. All activities must be performed with proper permission and within legal and ethical boundaries.

---

## 📚 Learning Outcomes

By completing this module, learners will:

* Gain hands-on experience with internal network attacks
* Understand attacker movement post-initial compromise
* Improve defensive and detection strategies
* Strengthen SOC and blue team readiness

---

## 👤 Author

**Mayur Dipak Patil**
Cybersecurity Enthusiast | CPENT | Internal Pentesting | SOC Analyst

---

## ⭐ Support

If this repository helps you learn CPENT internal network testing, consider giving it a ⭐.
