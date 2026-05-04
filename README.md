# 🛡️ Windows OS Threat Simulation & Detection using Wazuh SIEM

This project demonstrates a real-world Security Operations Center (SOC) scenario where common Windows operating system threats are simulated and analyzed using Wazuh SIEM.

---

## 🚀 Project Overview

In this lab, I simulated post-compromise attacker behavior on a Windows 10 endpoint and analyzed the generated logs using Wazuh.

### 🔍 Attacks Simulated:
- PowerShell Abuse (IEX execution)
- Unauthorized User Account Creation
- Privilege Escalation (Adding user to Administrators group)
- Defense Evasion (Clearing Security Logs)

---

## 🧠 Detection & Analysis

The following Windows Event IDs were analyzed:

| Event ID | Description |
|--------|------------|
| 4104 | PowerShell Script Execution |
| 4720 | User Account Creation |
| 4732 | Privilege Escalation |
| 1102 | Security Log Cleared |

These events were correlated to reconstruct the attack lifecycle.

---

## 🛠️ Tools & Technologies

- Wazuh SIEM
- Windows Event Logs
- Active Directory Lab
- VirtualBox

---

## 🎯 Key Learning Outcomes

- Hands-on SIEM monitoring and detection
- Log correlation and attack timeline analysis
- Understanding of post-exploitation techniques
- MITRE ATT&CK mapping

---

## 📄 Full Report

👉 [Download Full PDF](Windows_OS_Threats_Wazuh_Report.pdf)

---

## 🔗 Connect with Me

I am actively seeking opportunities in SOC / Cybersecurity roles.
