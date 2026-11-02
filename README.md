# 🛡️ Windows Account Lockout Monitoring Using Wazuh SIEM

## 📌 Project Overview
This is my fourth hands-on SOC Analyst lab. In this project, I practised monitoring Windows account lockout activity using Wazuh SIEM.

The objective was to understand how repeated unsuccessful login attempts can lead to account lockouts and how SOC Analysts investigate these security events.

## 🎯 Project Objectives
- Understand Windows account lockout policies.
- Monitor account lockout events.
- Identify locked user accounts.
- Investigate authentication-related security activity.

## 🛠️ Tools & Technologies
- Wazuh SIEM
- Windows
- Ubuntu Linux
- Oracle VirtualBox

## ⚙️ Lab Implementation
1. Started the Wazuh Server on Ubuntu.
2. Connected the Windows Agent to Wazuh.
3. Checked the Windows Account Lockout Threshold.
4. Explored Windows Security Event ID 4740.
5. Searched for account lockout events in Wazuh Threat Hunting.
6. Practised investigating account lockout details.

## 🔍 Detection Query

```text
data.win.system.eventID:4740
```

## 📖 Important Windows Event ID

| Event ID | Description |
|---|---|
| 4740 | A user account was locked out |

## 📚 Key Learnings
- Understanding account lockout policies.
- Learning Windows Security Event ID 4740.
- Monitoring authentication activity.
- Investigating locked user accounts.
- Understanding basic SOC investigation procedures.

## 📸 Screenshots
Add your own screenshots:
- Wazuh Dashboard
- Active Windows Agent
- Account Lockout Threshold
- Event ID 4740 search results
- Event investigation details

## 📝 Conclusion
This hands-on lab helped me understand Windows account lockout monitoring and basic security event investigation using Wazuh SIEM.

**Project Level:** Beginner  
**Project Type:** SOC Analyst Home Lab  
**Status:** Practical lab steps completed
