# 🧩 Splunk Detections & Dashboards

A collection of Splunk dashboards and queries designed for **Windows Security event monitoring and threat detection**.  
This project focuses on **EventCodes 4625 (Failed Logons)** and **4672 (Special Privileges Assigned)** to help analysts identify suspicious authentication activity and privilege escalation patterns.

---

## 📊 Dashboard Preview

![Login Privilege Dashboard](images/dashboard_preview.png)

---

## 🎯 Features

- 📈 **Privilege Monitoring:** Visualizes accounts assigned special privileges (EventCode 4672).
- 🚫 **Failed Logons Tracking:** Displays recent failed authentication attempts (EventCode 4625).
- 🕵️ **Security Analytics Focus:** Useful for SOC teams, blue teams, or cybersecurity learners building detection logic.
- ⚙️ **Customizable SPL:** Adaptable queries for your specific indexes and sourcetypes.

---

## 🧠 How It Works

This dashboard uses SPL (Search Processing Language) queries in Splunk to extract and visualize authentication activity from Windows Event Logs:

- **Index:** `winlogs`
- **Sourcetype:** `WinEventLog:Security`
- **EventCodes Used:**
  - `4625` → Failed logon attempts  
  - `4672` → Special privileges assigned to new logon sessions

---

## 🚀 Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/Niknaz-65/splunk-detections-dashboards.git

---

---

## 👩‍💻 Author

**Niknaz Sadehvandi (Niknaz-65)**  
Cybersecurity Student | Splunk Enthusiast | SOC & GRC Learner  

🔗 [LinkedIn Profile](https://www.linkedin.com/in/niknaz-sadehvandi-a34179325)  
