# Centralized Context-Aware Firewall (SIEM-based Security Tool)

🏆 **Runner-up:** Logica 3.0 State-Level Project Competition  
📄 **Publication:** Presented at the 10th ICT4SD International Conference (Goa, India)

## 📌 Project Overview
This project is a centralized network security tool that functions similarly to a **SIEM (Security Information and Event Management)** system. It was designed to address the limitations of standalone firewalls by centralizing threat intelligence and providing real-time visibility into network traffic.

The tool monitors incoming traffic, identifies malicious patterns, and executes automated responses across the network.

## 🛠️ Architecture & Tech Stack
The system is built on a Linux environment and integrates industry-standard security tools:

* **Intrusion Detection (IDS):** Suricata (used for detecting SQLi, XSS, and DDoS signatures).
* **Automated Response:** Fail2Ban (dynamic IP banning based on detection logs).
* **Logging & Visualization:** ELK Stack (Elasticsearch, Logstash, Kibana) for real-time monitoring.
* **Operating System:** Ubuntu/Linux.

## 🚀 Key Achievements
* **Low Latency:** Achieved threat detection and logging in under **5 seconds**.
* **Automated Mitigation:** Successfully simulated and blocked 100% of brute-force and SQLi attacks during testing.
* **Scalability:** Designed a centralized architecture where a single monitoring node can protect multiple client nodes.

## 📖 Research & Publication
The methodology and results of this project were published in the proceedings of the **10th International Conference on ICT for Sustainable Development (ICT4SD)**. The paper focuses on the effectiveness of "Context-Aware" rules in reducing false positives in enterprise firewalls.
