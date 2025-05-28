# 🕵️‍♀️ Network Monitoring with Wireshark

## 🔧 Lab Objective
To capture and analyze network packets using Wireshark, understand traffic types, apply filters, and identify packet-level information relevant to cybersecurity.

---

## 🛠 Tools Used
- **Wireshark**
- **Web browser (e.g., Chrome)**
- **Local machine IP address**

---

## 🧪 Steps Performed

### 1️⃣ Open Wireshark and Begin Capture
- Interface selected: `Wi-Fi` 
- Started capture and browsed common websites (e.g., google.com)

### 2️⃣ Applied Display Filters
- Used `tls` to view encrypted traffic
- Used `ip.addr == <your IP>` to isolate personal device traffic
- Attempted `http` filter — no unencrypted data found due to HTTPS

### 3️⃣ Identified TLS Handshake Packets
- Located **Client Hello** and **Server Hello**
- Found the **SNI (Server Name Indication)** extension
  - **Server Name:** `www.google.com`



## 🧠 What I Learned
- How to analyze **packet-level data**
- How to locate **domains** using the TLS handshake
- Importance of encryption — minimal `http` traffic found
- How to use **filters** to pinpoint relevant traffic

---

## 📸 Screenshots

1. ![Main View](https://github.com/SindiswaFezile/Cybersecurity-Portfolio-/blob/main/wireshark-main.png?raw=true) 
   _Wireshark with filters applied_

2. ![TLS Client Hello](https://github.com/SindiswaFezile/Cybersecurity-Portfolio-/blob/main/tls-client-hello-2.png?raw=true)  
   _Client Hello expanded to show `Server Name: www.google.com`_

3. ![Interesting Packet](https://github.com/SindiswaFezile/Cybersecurity-Portfolio-/blob/main/interesting-packet-2.png?raw=true)
   _No unencrypted data found due to HTTPS

---

## 📝 Analyst Notes
- Wireshark is a powerful tool for identifying and understanding real-time traffic.
- TLS encryption hides payloads, but metadata (like domain name in SNI) is still accessible.
- This type of monitoring is crucial for both blue teams (defense) and red teams (offense).

---

## ✅ Conclusion
This exercise simulated real-world monitoring. I successfully applied filters, explored encrypted traffic, and identified critical metadata in TLS handshakes. A foundational skill for any cybersecurity analyst.


