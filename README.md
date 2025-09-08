# Active Directory Attack and Mitigation Lab
## 📌 Project Summary
This project is a hands-on exploration of Active Directory (AD) attacks and their mitigations in a controlled lab environment. I built a dedicated lab to simulate real-world attack scenarios, analyze their impact, and implement defenses.

The project follows a structured four-stage approach for each attack:

- Explanation – Understanding the attack and its potential impact.

- Initiation – Step-by-step execution of the attack in a lab.

- Mitigation – Defensive measures to protect AD environments.

- Detection – Monitoring attack behavior using Wazuh SIEM + Sysmon.

This methodology provided me with both red team (offensive) and blue team (defensive) perspectives, strengthening my understanding of AD security.

# 🔐 Attacks Covered

- 🟡 LLMNR Poisoning

- 🟡 SMB Relay

- 🟡 Kerberoasting (with Pass-the-Hash)

- 🟡 Silver Ticket

- 🟡 DCSync

- 🟡 Golden Ticket

- 🟡 BloodHound Enumeration (high- and low-privileged users)

## ⚙️ Lab Setup

- Domain Controller (Windows Server)

- Two Client Machines (Windows 11)

- Attacker Machine (Kali Linux)

- SIEM: Wazuh (OVA deployment)

- Endpoint Logging: Sysmon + Wazuh Agent

All machines were placed in a 192.168.1.0/24 subnet for controlled attack simulations.
