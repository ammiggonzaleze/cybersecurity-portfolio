# Phishing Alert Investigation – SOC Analyst Report

## 📌 Overview

This folder contains a formal incident report based on a phishing alert I investigated and escalated as a **Level 1 Security Operations Center (SOC) analyst** in a financial services organization. The report outlines the incident handling process, technical analysis of a suspicious file, and documentation of steps taken in accordance with organizational procedures.

The investigation demonstrates the application of internal playbooks for phishing response, malware identification through hash analysis, and proper escalation protocols within a SOC environment.

## 🧩 Scenario Summary

While monitoring alerts as part of my responsibilities in the SOC, I received a phishing alert related to a suspicious email that had been delivered to an employee. The alert indicated the possible download of malware through an attachment (`bfsvc.exe`). 

I followed my organization’s phishing incident response playbook to:

- Evaluate the email and its indicators.
- Extract and verify the file hash.
- Confirm the file was malicious.
- Update the alert ticket with findings.
- Escalate the case to a Level 2 analyst due to confirmed malicious behavior.

The email came from a suspicious domain, contained grammatical errors, and included a password-protected executable file — all common signs of a phishing attack. Intrusion Detection Systems (IDS) flagged suspicious behavior shortly after the file was opened.

## 🎯 Objectives

This incident handling exercise demonstrates the following:

- Investigating and validating phishing alerts.
- Identifying and confirming malicious attachments.
- Following organizational playbooks and response procedures.
- Documenting incident details and escalation reasons clearly.
- Contributing to ongoing monitoring and defense workflows in the SOC.

## 📁 Files Included

- `Phishing incident response playbook.pdf`:  
  A structured guide outlining the SOC process for:
  - Receiving and analyzing phishing alerts.
  - Evaluating links and attachments.
  - Escalation decision flow.
  - Closing alerts following investigation.

- `Alert ticket.pdf`:  
  A copy of the incident ticket that includes:
  - Alert ID and summary.
  - Severity level and technical details.
  - Analyst comments with file hash analysis.
  - Indicators of compromise (IOC).
  - Escalation rationale and timeline of observed events.

## 🛡️ Skills Demonstrated

- SOC-level alert triage and ticket handling.
- Malware confirmation through hash analysis.
- Recognition of phishing indicators (spoofed sender, file behavior, language cues).
- Use of internal documentation standards.
- Communication of technical findings to higher-tier analysts.

## ✅ Outcome

Through structured investigation and adherence to established procedures, I confirmed that the email attachment was malicious and posed a potential threat to the organization’s systems. My analysis and documentation provided clear justification for escalation, supporting timely response and deeper investigation by senior analysts.

This report reflects key competencies in phishing response, evidence handling, and incident documentation within a real-world SOC context.

## 🔮 Future Recommendations

To enhance the organization’s resilience against similar attacks, the following measures are recommended:

- Strengthen email filtering policies to block password-protected executables.
- Reinforce employee training on identifying phishing attempts.
- Implement stricter endpoint execution policies for unknown files.
- Automate file hash lookups in alerts for faster confirmation.
- Enhance detection rules in IDS/EDR systems to flag password-protected malware.

Effective phishing response relies on timely detection, clear procedures, and collaborative escalation within the SOC team.
