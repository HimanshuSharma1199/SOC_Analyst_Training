# 🧠 Day 01 - SOC Overview

## 👨‍💻 What is a SOC?
- A Security Operations Center (SOC) is a centralized team that monitors, detects, and responds to security incidents.
- Works 24/7 in shifts.
- Analysts use SIEM tools to investigate logs and alerts.

---

## 🧑‍💼 SOC Analyst Roles

| Tier | Role Name         | Responsibilities                                                                 | Tools Used                             | Skills Needed                            |
|------|-------------------|----------------------------------------------------------------------------------|----------------------------------------|-------------------------------------------|
| 1    | Tier 1 Analyst    | Monitor SIEM alerts,identify false positives,escalate serious alerts,create tickets | Splunk, Wazuh, ServiceNow        | Log analysis, attention to detail         |
| 2    | Tier 2 Analyst    | Investigate escalated alerts, correlate across systems, validate incidents        | EDR tools, MITRE ATT&CK, ELK Stack    | Deep log correlation, threat hunting      |
| 3    | Tier 3 Analyst    | Lead incident response, reverse malware, write detection rules                    | Velociraptor, YARA, Volatility          Malware analysis, threat intel, IR        |

---

## 📘 Key Definitions

- **SIEM**: Security Information & Event Management system (like Splunk)
- **IOC**: Indicator of Compromise (IP, domain, file hash, etc.)
- **Triage**: Prioritizing and reviewing alerts to decide their severity
- **False Positive**: A harmless event that triggers an alert
- **Log**: A recorded event from a system (login, error, change, etc.)

---

## 🧠 My Practice Questions & Answers

1. **What does a SOC do?**  
   A SOC monitors for, investigates, and responds to security events 24/7.

2. **What are 3 types of logs a Tier 1 analyst reviews?**  
   - Windows Event Logs  
   - Firewall logs  
   - Authentication logs

3. **How do analysts know if an alert is serious?**  
   They check context like IP reputation, number of attempts, time, and user behavior.

4. **What’s a false positive?**  
   A legitimate action that mistakenly triggers a security alert.

---

## ✅ Completed Tasks
- [x] Watched SOC overview videos  
- [x] Wrote SOC Tier comparison  
- [x] Defined key terms  
- [x] Answered analyst questions  
