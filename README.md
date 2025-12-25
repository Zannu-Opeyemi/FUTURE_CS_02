# 🛡️ SOC Task 2: Log Analysis & Incident Response

### **Cybersecurity Internship Project | Future Interns**

**Analyst:** Zannu Opeyemi Emmanuel  
**Role:** SOC Analyst Intern  
**Tools:** Splunk SIEM, Excel, Log Analysis  
**Focus:** Malware Detection, Threat Hunting, Incident Response

---

## 📝 Project Overview

This project simulates a real-world **Security Operations Center (SOC)** environment. The objective was to analyze raw system logs, detect simulated security threats, and execute a full **Incident Response (IR)** cycle. 

As a SOC Analyst, I ingested raw log data into **Splunk**, identified critical indicators of compromise (IoCs), and drafted a comprehensive remediation strategy for a multi-vector malware attack.

### **The Scenario**
The organization’s network experienced a series of anomalous activities. My task was to:
1.  Ingest and normalize raw system logs.
2.  Identify suspicious patterns (Failed logins, Malware signatures).
3.  Classify incidents by severity (High/Medium/Low).
4.  Propose remediation steps to contain the threat.

---

## 🔧 Tools & Skills Demonstated

| Category | Tools / Skills |
| :--- | :--- |
| **SIEM Tool** | **Splunk Enterprise** (Data Ingestion, SPL Queries, Dashboards) |
| **Analysis** | Log Parsing, Threat Triage, Correlation Analysis |
| **Threats Detected** | **Ransomware**, **Rootkits**, Trojans, Worms, Spyware |
| **Reporting** | Incident Response Documentation, Executive Communication |
| **Frameworks** | Incident Response Lifecycle (Preparation -> Detection -> Containment) |

---

## 📂 Repository Contents

| File | Description |
| :--- | :--- |
| `Incident Response Report.pdf` | **Main Deliverable:** A professional report detailing the investigation, findings, and remediation. |
| `Alert Classification Log.xlsx` | A triage spreadsheet categorizing the 22 detected alerts by severity. |
| `Email Communication Draft.txt` | A simulated email notification to the CISO/Management team reporting the incident. |
| `Screenshots of Analysed Alerts and Siem Dashboard.png` | Visualization of the attack timeline and threat distribution created in Splunk. |

---

## 🔍 Investigation Findings

The analysis of logs from **July 3, 2025**, revealed a critical security breach involving **22 distinct alerts**.

### **Key Threats Identified**
* 🚨 **High Severity:** Active **Ransomware Behavior** detected on User Bob's workstation (IP: `172.16.0.3`).
* 🚨 **High Severity:** **Rootkit Signatures** found on multiple endpoints (Alice & Eve), indicating deep system compromise.
* ⚠️ **Medium Severity:** **Worm Infection Attempts** suggesting lateral movement across the network.

---

## 🚀 Remediation Strategy

Based on the investigation, the following containment actions were recommended:
1.  **Isolation:** Immediately disconnect affected IPs (`172.16.0.3`, `10.0.0.5`) from the network.
2.  **Access Control:** Force password resets for compromised accounts (Bob, Alice, Eve).
3.  **Sanitization:** Re-image systems infected with Rootkits and restore Ransomware-affected data from backups.
4.  **Hardening:** Update firewall rules to block identified malicious IPs.

---

## 📬 Contact

**Zannu Opeyemi Emmanuel** *Aspiring Cybersecurity Professional* [https://www.linkedin.com/in/zannu-opeyemi-emmanuel-669653391/?lipi=urn%3Ali%3Apage%3Ad_flagship3_feed%3BOV%2Boel4MSUSLOgh666dmcA%3D%3D]

---
*This project was completed as part of the Future Interns Cybersecurity Internship Program.*
