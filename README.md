# Active Directory Attack and Mitigation Lab
## 📌 Project Summary
This project is a hands-on exploration of Active Directory (AD) attacks and their mitigations in a controlled lab environment. I built a dedicated lab to simulate real-world attack scenarios, analyze their impact, and implement defenses.

The project follows a structured four-stage approach for each attack:

- *Explanation* – Understanding the attack and its potential impact.

- Initiation – Step-by-step execution of the attack in a lab.

- Mitigation – Defensive measures to protect AD environments.

- Detection – Monitoring attack behavior using Wazuh SIEM + Sysmon.

This methodology provided me with both red team (offensive) and blue team (defensive) perspectives, strengthening my understanding of AD security.

## 🔐 Attacks Covered

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

# 📊 Tools & Technologies

- Attacker Tools: Responder, Impacket, Hashcat, BloodHound

- Defensive Tools: Wazuh, Sysmon

- Monitoring: SIEM dashboards, Event logs

# 🛡️ Key Learnings

- How attackers exploit AD misconfigurations and weak passwords.

- How to detect suspicious activities via log correlation in Wazuh.

- Importance of password policies, privilege management, and secure Kerberos configurations.

- Real-world mapping of attacks to MITRE ATT&CK techniques.

# 📖 Conclusion

This project helped me gain comprehensive insights into AD security, balancing offensive and defensive perspectives. While the lab was intentionally configured with weak defenses, the exercise demonstrated how proper hardening, monitoring, and detection can prevent these attacks in real-world environments.

I plan to extend this work in the future by covering more advanced AD attacks.


