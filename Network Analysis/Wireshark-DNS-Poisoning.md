# 🧪 Wireshark DNS Poisoning Lab

## 🖥️ Tools Used:
- Wireshark
- DNS Spoofing PCAP

## 🔍 Objective:
Analyze a PCAP to detect signs of DNS poisoning and possible cleartext credential leaks.

## 🧪 Filters Used:
- `dns`
- `ftp or http`

## 📸 Screenshots:
1. ![DNS Spoofing Detection]([../assets/wireshark-dns-alert.png](https://github.com/SindiswaFezile/Cybersecurity-Portfolio-/blob/main/Network%20Analysis/wireshark-dns-alert.PNG)
2. ![Cleartext Password Detected]([../assets/wireshark-password-leak.png](https://github.com/SindiswaFezile/Cybersecurity-Portfolio-/blob/main/Network%20Analysis/wireshark-dns-alert.PNG)

## 🧠 Findings:
- Multiple DNS responses with conflicting IPs for same domain.
- FTP credentials exposed in cleartext.
- Indications of network-level attack simulation.

## ✅ Remediation:
- Enforce encrypted DNS (DNS over HTTPS/DoH)
- Use secure protocols like SFTP and HTTPS.

## 🎯 Conclusion:
This lab demonstrates the ability to analyze real network traffic for threats using Wireshark.
