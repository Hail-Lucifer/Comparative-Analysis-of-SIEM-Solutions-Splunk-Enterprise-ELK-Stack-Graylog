<div align="center">

# 🔍 SIEM Showdown

## Splunk Enterprise · ELK Stack · Graylog

![Project Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![SIEM](https://img.shields.io/badge/SIEM-Splunk%20%7C%20ELK%20%7C%20Graylog-blue)
![Incident Response](https://img.shields.io/badge/Incident-Real%20%23147-red)

**A hands-on comparative analysis of three leading SIEM platforms with a real security incident investigation** 

</div>

---

## 📌 What is this project?

This project evaluates **Splunk Enterprise**, **ELK Stack**, and **Graylog** across architecture, ease of use, alerting, scalability, and real-world detection capabilities.

**But here's what makes it different:**  
It includes a **real incident investigation (Case #147)** conducted in a live SOC environment using ELK Stack and TheHive.

---

## 🔴 Real Incident Highlight: Case #147

| Field | Detail |
|-------|--------|
| **Date** | March 20, 2026 |
| **Source IP** | 10.10.2.21 |
| **Affected User** | p.rousseau |
| **Severity** | High |
| **Log Sources** | Proxy · Firewall · IDS · Windows Event Logs · Linux auth · Web server |

**What I did:**
- Correlated logs across 6+ sources
- Mapped the attack to the Cyber Kill Chain
- Created a ticket in TheHive
- Delivered a full postmortem report with remediation steps

---

## 📊 Quick Comparison

| Feature | Splunk | ELK Stack | Graylog |
|---------|--------|-----------|---------|
| **License** | $$$ | Open Source | Free / $$ |
| **Deployment** | Medium | High | Low |
| **Ease of Use** | Medium (SPL) | Hard | Easy |
| **Best For** | Large enterprises | Engineering teams | SMBs |

---

## 🛠️ Tools Used

`Splunk Enterprise` `ELK Stack` `Graylog` `TheHive` `Windows Event Logs` `Linux auth` `Proxy logs` `Firewall logs` `IDS alerts`

---

## 📂 Full Documentation

👉 [Click here for the complete SIEM Comparison Report](./SIEM-Comparison-Report.md)

---

## ✅ Skills Demonstrated

- SIEM deployment and configuration
- Log ingestion from diverse sources
- Alert creation and tuning (SPL, Watchers, Streams)
- Incident investigation and cross-source log correlation
- Cyber Kill Chain mapping
- Ticketing system integration (TheHive)
- Postmortem reporting
