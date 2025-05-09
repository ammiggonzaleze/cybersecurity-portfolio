# Web Server DoS Attack - Security Incident Analysis

## 📌 Overview

This folder contains the results of an exercise to analyze a **Denial of Service (DoS)** attack on a web server. The purpose of this exercise is to demonstrate the ability to identify, document, and understand the impact of a **SYN flood attack** on a network, using packet capture analysis to detect attack patterns.

## 🧩 Scenario Summary

While working as a security analyst for a travel agency, a sudden website connection timeout error was reported by employees. Upon further investigation, a high volume of incoming **SYN packets** from an unknown IP address was detected, overwhelming the server and causing it to fail in responding to legitimate traffic. This behavior is characteristic of a SYN flood attack, a type of DoS attack that targets the server’s resources by initiating connection requests without completing the handshake.

## 🎯 Objectives

The objectives of this exercise are to:

* Document findings of the SYN flood attack that caused network disruption.
* Analyze the network traffic captured during the incident to identify attack patterns.
* Understand how the DoS attack impacts server functionality and causes connection timeouts.
* Report the attack findings using a standardized incident report template.

## 📁 Files Included

* `Cybersecurity_Incident_Report.pdf`: Comprehensive report structured in two sections:

  * Identification of the SYN flood attack as the cause of the incident, based on server logs and network behavior.
  * Explanation of how the attack disrupts the TCP Three-Way Handshake process, leading to denial of service and timeout errors.

* `TCP_Log.pdf`: Raw TCP log captured from Wireshark, showing packet exchange between client and server during the incident.

* `Color_Coded_TCP_Log.pdf`: Visual version of the TCP log, using color codes to distinguish:

  * Green: Normal TCP handshakes.
  * Red: Malicious SYN packets from the attacker.
  * Yellow: Failed connections due to the attack.

## 🛡️ Skills Demonstrated

* Packet capture and analysis using Wireshark.
* Identification of SYN flood attacks in network traffic.
* Understanding of the TCP Three-Way Handshake process.
* Incident documentation and reporting.
* Analysis of DoS attack impact on server performance.

## ✅ Outcome

This project demonstrates the process of identifying and analyzing a DoS attack on a web server using network logs. The results reinforce the importance of traffic analysis in detecting malicious activity and understanding its impact, enabling better incident response and mitigation strategies in real-world scenarios.
