# 🛡️ Threat Detection Scenarios

## 🧠 Scenario Overview

In this lab, I reviewed real-world threat detection logs and simulated alerts to identify potential indicators of compromise (IOCs).

## 🧪 Objectives

- Analyze event logs for malicious activity  
- Identify IP addresses or hostnames involved in suspicious behavior  
- Practice incident triage (Security+ 4.1, 4.2, 3.2)

---

## 📋 Sample Scenario

**Incident:** Unauthorized SSH access attempt detected  
**Source IP:** 203.0.113.42  
**Destination Port:** 22  
**Action Taken:** Connection blocked by firewall


### 🧠 Analysis:

- Detected multiple failed login attempts within a short window.  
- Source IP was flagged in threat intelligence feeds.  
- Brute force attack likely — mitigated successfully.

---

## 📸 Screenshots

1. ![Simulated Terminal](https://github.com/SindiswaFezile/Cybersecurity-Portfolio-/blob/main/ssh-alert.png)
2. ![Brute-force Alertt](https://github.com/SindiswaFezile/Cybersecurity-Portfolio-/blob/main/firewall-block.png)

---

## ✅ Summary

This lab shows how to use logs and alerts to detect network-based attacks. It highlights how a SOC analyst would handle unauthorized access attempts and prevent escalation.
