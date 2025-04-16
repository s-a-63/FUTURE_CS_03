# 🌐 Network Scanning & Traffic Analysis – Task 3

This repository contains the network analysis and scanning exercise conducted as part of **Task 3** of the cybersecurity internship. The objective was to perform both active and passive analysis on a local network, understand traffic patterns, and identify open ports and connected devices.

---

## 📁 Repository Structure  

### ▶️ [`Wireshark/`](./Wireshark/)  
Contains:  
- 📄 `packet_analyzer_anonymized.pcapng` – Anonymized file (safe for public sharing)  

### ▶️ [`Nmap/`](./Nmap/)  
Contains:  
- Screenshots and summaries of Nmap scans for various IPs  
- Comments on open ports, likely device types, and services  

### ▶️ [`Final_Report/`](./Final_Report/)  
Contains:  
📄 `Task3_NetworkAnalysis_Report.docx` – Final report detailing scanning results, Wireshark findings, and privacy measures  

---

## 🧰 Tools Used  
- **Wireshark**  
- **Nmap**  
- **Python script** (for anonymizing `.pcapng` files)  

---

## 📌 Summary  

- **Active Analysis**:
  - Scanned multiple devices within the `192.168.1.0/24` subnet  
  - Identified open ports and services like HTTP, HTTPS, DNS, and FTP  
  - Inferred device types based on port/service patterns

- **Passive Analysis**:
  - Captured network traffic using Wireshark  
  - Analyzed key packets using filters like `http`, `dns`, `tcp.port == 80`  
  - Exported filtered results and anonymized sensitive metadata

- **Anonymization Measures**:  
  - MAC addresses and hostnames scrubbed from public files  
  - Any identifiable names or domains were excluded or obfuscated  

---

## 🧠 Skills Gained  
- Port Scanning and Service Fingerprinting  
- Packet Capture and Protocol Analysis  
- Data Sanitization and Privacy Best Practices  
- Report Writing for Technical Findings  

---

## 📝 Notes on Public Sharing  
- The original `.pcapng` file is retained for internal review only  
- Only the anonymized `.pcapng` file (`packet_analyzer_cleaned.pcapng`) is safe to post  
- Nmap screenshots have been redacted/blurry where IPs are visible – public release follows ethical disclosure guidelines  

---

## 📞 Contact  
**Author:** M. Sahiti  
**Email:** sahitim137@gmail.com  
**Date:** April 2025
