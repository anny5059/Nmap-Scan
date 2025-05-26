# 🔍 Nmap Scan Lab

## 🧾 Objective
Perform a TCP SYN scan on the local network to identify live hosts and their open ports using `nmap`.

## 🛠️ Tools Used
- Nmap
- Kali Linux
- Wireshark *(optional)*

## 📌 Steps Performed
1. Identified local IP address: `192.168.31.191`
2. Ran TCP SYN scan on the subnet: `192.168.31.0/24`
3. Analyzed open ports and services on discovered hosts
4. Saved scan results to text file
5. Documented findings in a report

## 📂 Files Included
- `nmap_report.md`: The full Markdown report
- `scan_results.txt`: Raw scan output from Nmap
- `screenshot.png`: Screenshot of terminal output *(optional)*

## ✅ Outcome
Successfully identified multiple live devices and potential open services such as UPnP, web server (HTTP), and device control ports.
