# Malicious File Analysis via VirusTotal – Incident Handler's Journal Entry 002

## 📌 Overview

This folder contains a formal journal entry documenting a cybersecurity incident involving the analysis of a suspicious file within a financial services organization. The journal outlines the alert response, investigation process, and technical findings using VirusTotal and threat intelligence frameworks such as the Pyramid of Pain.

This entry is part of a broader effort to document and reflect on real-world security incidents to improve organizational resilience and incident response capabilities.

## 🧩 Scenario Summary

I am a Level 1 Security Operations Center (SOC) analyst at a financial services company. I received an alert regarding the download of a suspicious, password-protected spreadsheet on an employee’s workstation.

Upon investigation, I discovered that the employee had received a phishing email containing the spreadsheet and password. After the file was opened, a malicious payload was executed. I generated the SHA256 hash of the file and analyzed it using VirusTotal.

The VirusTotal report confirmed the file was malicious, flagged by multiple antivirus engines, and linked to negative community feedback. Behavioral analysis revealed that the malware created unauthorized executables and established communication with known malicious infrastructure (domains and IPs).

Key indicators of compromise (IoCs) were extracted and categorized using the Pyramid of Pain model, supporting further threat intelligence enrichment and response efforts.

## 🎯 Objectives

This journal entry serves the following purposes:

- Document the timeline and characteristics of the malware incident.
- Identify the attack vector and threat actor behavior.
- Analyze organizational vulnerabilities that enabled the event.
- Provide actionable recommendations for improving cybersecurity posture.
- Contribute to threat intelligence and incident response documentation.

## 📁 Files Included

- `Incident_Handler's_Journal_002.pdf`:  
  A detailed journal entry documenting the investigation of a phishing-based malware incident. It includes:  
  - Timeline of events and alert response.  
  - VirusTotal analysis and hash-based investigation.  
  - The 5 W’s (Who, What, When, Where, Why) of the incident.  
  - Key IoCs discovered and defensive recommendations.

- `Investigation_findings.pdf`:  
  Supplementary report summarizing extended threat intelligence findings. It includes:  
  - Attribution of the malicious file to **Flagpro malware**, linked to **APT group BlackTech**.  
  - VirusTotal detection data (flagged by 50+ vendors).  
  - Indicators of Compromise categorized using the **Pyramid of Pain** framework.  
  - MITRE ATT&CK techniques observed.  
  - Strategic recommendations for prevention and mitigation.

## 🛡️ Skills Demonstrated

- Threat detection and incident analysis using open-source tools (VirusTotal).
- Malware identification and behavior analysis based on file hash investigation.
- IoC categorization using the Pyramid of Pain.
- Application of MITRE ATT&CK techniques for TTP mapping.
- Security incident documentation and threat attribution.
- Recommendation development for enhanced cyber defense.

## ✅ Outcome

This journal entry highlights the early detection and analysis of a malicious file that bypassed initial email defenses. The investigation leveraged VirusTotal to uncover malware behavior, associated infrastructure, and threat actor patterns.

The accompanying findings link the file to a known APT group (BlackTech), enhancing situational awareness and supporting intelligence-driven response strategies.

## 🔮 Future Recommendations

To reduce the risk of similar incidents, the following measures should be implemented:

- Deploy endpoint protection and antivirus solutions across all user devices.
- Use advanced email filtering and anti-phishing tools.
- Implement firewalls and IDS/IPS to monitor suspicious activity.
- Establish secure, redundant backup systems (offline/cloud).
- Adopt a centralized SIEM solution for real-time threat detection.
- Conduct regular employee security awareness training to reduce phishing risk.

Preventing malware incidents requires a combination of technical controls, user training, and timely intelligence sharing.
