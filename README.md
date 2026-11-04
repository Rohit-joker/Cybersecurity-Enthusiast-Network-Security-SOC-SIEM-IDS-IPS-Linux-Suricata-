# 🛡️ Real-Time Network Intrusion Detection and Security Monitoring Platform Using Suricata

## 📌 Overview

An end-to-end Network Intrusion Detection and Security Monitoring Platform developed using Suricata IDS, Grafana Alloy, Loki, and Grafana.

The project focuses on monitoring network traffic, generating structured IDS events, collecting security logs, storing events centrally, and visualizing monitoring data through Grafana.

The environment was developed and tested using three virtual machines in Oracle VirtualBox.

## 🏗️ Architecture

### Virtual Machines

| Virtual Machine | Purpose |
|---|---|
| Kali Linux | Authorized network testing |
| OWASP Target VM | Target environment |
| Ubuntu | IDS and monitoring server |

### Technology Stack

- Suricata IDS
- Kali Linux
- Nmap
- Ubuntu Linux
- Oracle VirtualBox
- Grafana Alloy
- Grafana Loki
- Grafana

### Monitoring Pipeline

Kali Linux → VirtualBox Network → Suricata → eve.json → Grafana Alloy → Loki → Grafana Dashboard.

## 🚀 Key Features

- Network traffic monitoring.
- Structured IDS event generation.
- Centralized security log collection.
- Log storage and querying.
- Security event visualization.
- Authorized Nmap testing.
- End-to-end monitoring validation.

## 📸 Project Screenshots

See the `screenshots/` directory for implementation evidence and dashboard screenshots.

## 📚 Documentation

[View Complete Project Documentation](documentation/Suricata_Project_Documentation.pdf)

## 📂 Repository Structure

```text
├── documentation/
├── architecture/
├── screenshots/
├── configuration/
├── scripts/
├── results/
└── README.md
```

## 🎯 Learning Outcomes

- Network Intrusion Detection Systems.
- Linux-based security monitoring.
- Network traffic analysis.
- Security event and log analysis.
- Centralized log management.
- Security dashboard development.

## ⚠️ Disclaimer

This project was developed for educational purposes in a controlled laboratory environment.

All security testing was performed against authorized lab systems.

## 👨‍💻 Author

**Rohit Dhotre**

Cybersecurity | Network Security | SOC & Security Monitoring

[GitHub Profile](https://github.com/YOUR_USERNAME)
