# FUTURE_CS_02
TASK 2 - SECURITY ALERT MONITORING & INCIDENT  RESPONSE

# 🔍 Security Alert Monitoring & Incident Response  
**SOC Cybersecurity Internship Project**

## 📌 Overview  
This project simulates real-world SOC operations using **Splunk** to monitor security alerts and perform incident response. It involves analyzing Windows event logs, detecting suspicious activities, classifying incidents, and documenting remediation steps.

---

## 🧰 Tools & Technologies  
- Splunk Enterprise (SIEM tool)  
- Windows 10 (for generating and analyzing event logs)  
- Simulated log files (Security, Sysmon, etc.)  
- Notepad++ or VS Code (for documentation)

---

## 🛠️ Project Workflow  

### 1. Log Ingestion  
- Uploaded simulated Windows logs into Splunk  
- Indexed sources like:
  - `WinEventLog:Security`  
  - `WinEventLog:System`  
  - `Sysmon`

### 2. Security Monitoring  
- Used SPL (Search Processing Language) to explore logs  
- Visualized activities via dashboards  
- Monitored for patterns like:
  - Multiple failed login attempts  
  - PowerShell execution  
  - Registry or file changes  
  - New user creation or group changes

### 3. Alert Detection  
- Detected potential threats such as:
  - Brute-force attacks  
  - Privilege escalation  
  - Lateral movement  
  - Suspicious command execution  

### 4. Incident Classification  
- Categorized incidents by severity:
  - 🟢 Low: Normal failed logins  
  - 🟠 Medium: Suspicious PowerShell activity  
  - 🔴 High: Unauthorized admin access

### 5. Response & Remediation  
- Identified and documented:
  - Affected systems  
  - Source IPs  
  - Compromised user accounts  
- Suggested actions:
  - Password reset  
  - Account disablement  
  - Patch application  
  - Blocking malicious IPs

---


## 🧠 Learning Outcomes  
- Developed skills in real-time log monitoring  
- Understood SIEM fundamentals and SOC workflows  
- Learned SPL for custom searches  
- Practiced classifying and responding to incidents

---

## ⚠️ Disclaimer  
This project uses **simulated logs** and is meant for **educational purposes only**. No real systems or data were involved.

---



