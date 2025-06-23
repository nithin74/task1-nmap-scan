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


---

## 📋 Summary of Results:
- **Live Hosts Detected**: 6
- **Devices Identified**: JioFiber router, POCO phone, Xiaomi device, Desktop, Kali Linux machines
- **Common Open Ports**:
  - 80 (HTTP)
  - 443 (HTTPS)
  - 22 (SSH)
  - 53 (DNS)
  - 8080 (HTTP-proxy)

