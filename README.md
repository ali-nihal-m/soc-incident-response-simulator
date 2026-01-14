# SOC Incident Response Simulator (Frontend Demo)

A web-based **Security Operations Center (SOC) dashboard simulation** that demonstrates incident detection, analysis, and response workflows.

This project is designed for **educational and portfolio purposes**, focusing on SOC concepts rather than real-time security infrastructure.

---

## 🎯 Purpose

The goal of this project is to demonstrate understanding of **SOC operations**, including:

- Incident triage and prioritization  
- Severity classification  
- Analyst response actions  
- Risk scoring and security metrics visualization  

It is intended as a **frontend demo/simulation**, not a production SOC or SIEM replacement.

---

## ✨ Features

- **Incident Management**  
  Simulated detection of ransomware, data exfiltration, brute force, malware, and phishing incidents.

- **Severity Classification**  
  Automatic categorization into **Critical**, **High**, and **Medium** severity levels.

- **Analyst Actions**  
  Perform actions such as **Contain**, **Escalate**, or **Ignore**, with dynamic updates to risk score and incident status.

- **Response Playbooks**  
  Step-by-step incident response procedures tailored to each threat type.

- **Live Log Stream (Simulated)**  
  Continuous generation of security log entries to mimic SOC monitoring activity.

- **Threat Intelligence Feed (Simulated)**  
  Display of current threat and vulnerability information for situational awareness.

- **Security Metrics & Visualizations**  
  Interactive charts showing:
  - Threat distribution (donut chart)
  - Incident trends over time (line chart)

- **Search & Filter**  
  Real-time filtering of incidents by title or description.

- **Incident Report Export**  
  Generate a text-based incident report for documentation purposes.

---

## 🛠️ Technologies Used

- HTML5  
- CSS3 (custom dark UI, glassmorphism-style design)  
- Vanilla JavaScript  
- Chart.js for data visualization  

> The project is intentionally **frontend-only** to focus on SOC workflows and visualization rather than backend infrastructure.

---

## 🚀 How to Run

Open `index.html` in any modern web browser.

No installation, build process, or server is required.

---

## 📊 How It Works

The simulator models a simplified SOC workflow:

1. **Detection** – Incoming security alerts are displayed with severity and contextual metadata.  
2. **Analysis** – Selecting an incident reveals affected assets, source IPs, and event details.  
3. **Response** – Analysts apply response actions and follow predefined playbooks.  
4. **Documentation** – Incident reports can be exported for record-keeping.

All data shown is **simulated** and generated within the browser.

---

## ⚠️ Disclaimer

This project is a **demonstration / simulation tool** created for learning and portfolio use.

It does **not**:
- Connect to real security infrastructure  
- Ingest live logs or telemetry  
- Replace professional SIEM or SOAR platforms  

---
## 📸 Screenshots

### Dashboard Overview
![Dashboard Overview](screenshots/dashboard-overview.png)

### Incident Details & Actions
![Incident Details](screenshots/incident-details.png)

### Playbook & Log Stream
![Playbook Logs](screenshots/playbook-logs.png)

---
## 📝 License

MIT License  
© 2026 Ali Nihal M

---

**Built as part of cybersecurity education and SOC skill development**

