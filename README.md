# 🚀 Cyber Security Internship - Task 1

## 📝 Task Title:
**Port Scanning with Nmap**

---

## 🎯 Objective:
Scan the local network using Nmap to identify live hosts, open ports, and exposed services.

---

## 🛠️ Tools Used:
- **Nmap** – Used for TCP SYN scanning to find open ports
- (Optional) Wireshark – Not used in this task

---

## 💻 Command Used:
nmap -sS 192.168.31.0/24

Explanation
  -sS: TCP SYN scan (stealthy and fast)

   192.168.31.0/24: Scans all 256 IPs in the local subnet

