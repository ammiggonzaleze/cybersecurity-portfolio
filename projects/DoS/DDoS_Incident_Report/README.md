# Web Server DDoS Attack - Security Incident Analysis

## 📌 Overview

This folder contains the results of an exercise to analyze a **Distributed Denial of Service (DDoS)** attack on a multimedia company's internal network. The purpose of this exercise is to document the impact of the DDoS attack on network availability and to understand how the organization responded to mitigate and recover from the incident using the NIST Cybersecurity Framework (CSF).

## 🧩 Scenario Summary

The company, which offers web design, graphic design, and social media marketing solutions, was targeted by a DDoS attack. The attack overwhelmed the network with a high volume of **ICMP packets**, causing the internal network to become unreachable for approximately two hours. The incident management team responded by blocking incoming ICMP traffic, taking non-critical services offline, and restoring critical network services. The subsequent investigation revealed that the attack exploited an unconfigured firewall, allowing the attacker to flood the network with ICMP traffic.

## 🎯 Objectives

The objectives of this exercise are to:

* Document the findings of the DDoS attack that disrupted the organization's internal network.
* Analyze the captured network traffic during the incident to identify attack patterns.
* Understand how the DDoS attack impacted network availability and caused service interruptions.
* Report the incident using a standardized framework, focusing on detection, response, and recovery.
* Propose future preventive measures to avoid similar incidents.

## 📁 Files Included

* `Incident_report_analysis_multimedia_company.pdf`: Comprehensive report structured in five sections based on the NIST Cybersecurity Framework:
  * **Identify**: Assessment of the unconfigured firewall vulnerability and identification of gaps in network monitoring.
  * **Protect**: Actions taken to improve network security, including firewall rule changes and deployment of an IDS/IPS system.
  * **Detect**: Enhancements in detection capabilities, such as the installation of monitoring software and log analysis tools.
  * **Respond**: Incident management response actions, including blocking malicious traffic and restoring services.
  * **Recover**: Steps taken to restore normal network operations and mitigate future risks.

## 🛡️ Skills Demonstrated

* Identification and analysis of DDoS attacks based on ICMP traffic patterns.
* Incident documentation and reporting following industry-standard frameworks.
* Deployment of security tools like IDS/IPS systems for DDoS detection.
* Understanding of firewall configuration and network monitoring best practices.

## ✅ Outcome

This project demonstrates the process of identifying and mitigating a DDoS attack on an organization's internal network. The results emphasize the importance of firewall configuration and effective incident response in minimizing the impact of cyberattacks. The measures implemented following the attack have significantly improved the organization's ability to prevent and respond to similar incidents in the future.

## 🔮 Future Recommendations

To improve future security posture, the following actions are recommended:
* Regular firewall audits and proper configuration management to prevent vulnerabilities.
* Continued training for employees and network administrators on recognizing and preventing DDoS attacks.
* Integration of advanced network monitoring tools with anomaly detection capabilities to enhance attack detection.
* Development and testing of an incident response playbook, specifically for DDoS and other high-volume attack scenarios.
* Establishment of automated traffic mitigation mechanisms for faster recovery during future incidents.
