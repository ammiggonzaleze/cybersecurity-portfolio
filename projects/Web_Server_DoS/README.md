# Web Server DoS Attack - Security Incident Analysis

📌 **Overview**  
This folder contains the results of an exercise to analyze a **Denial of Service (DoS)** attack on a web server. The purpose of this exercise is to demonstrate the ability to identify, document, and understand the impact of a **SYN flood attack** on a network, using packet capture analysis to detect attack patterns.

🧩 **Scenario Summary**  
While working as a security analyst for a travel agency, a sudden **website connection timeout error** was reported by employees. Upon further investigation, a high volume of incoming **SYN packets** from an unknown IP address was detected, overwhelming the server and causing it to fail in responding to legitimate traffic. This behavior is characteristic of a **SYN flood attack**, a type of **DoS attack** that targets the server’s resources by initiating connection requests without completing the handshake.

🎯 **Objectives**  
The objectives of this exercise were to:  
- Document findings of the **SYN flood attack** that caused network disruption.  
- Analyze the network traffic captured during the incident to identify attack patterns.  
- Understand how the **DoS attack** impacts server functionality and causes connection timeouts.  
- Report the attack findings using an incident report template, focusing on the identification of the attack and its effects on the server.

📁 **Files Included**  
- **Cybersecurity Incident Report.pdf**: This document provides a comprehensive analysis of the network disruption incident. It is structured into two main sections:
  - **Section 1: Identification of the Type of Attack Responsible for the Network Disruption**  
    This section explains how a **SYN flood** attack is suspected to be the cause of the website's connection timeout errors. It describes how server logs indicate that legitimate traffic was no longer processed, with the server exclusively logging activity from a single IP address starting from log entry 125. This strongly suggests the occurrence of a **Denial of Service (DoS)** attack.
  - **Section 2: Explanation of How the Attack Is Causing Website Malfunctions**  
    This section provides a detailed explanation of the **TCP Three-Way Handshake** process and how a **SYN flood** attack disrupts this connection process. It outlines how the attack overwhelms the server's connection table by sending multiple incomplete SYN packets, causing a **Denial of Service (DoS)** condition. The report also analyzes the server logs and discusses error messages like **HTTP/1.1 504 Gateway Time-out** and **RST, ACK** packets, which are indicators of the server's failure to establish legitimate connections due to the attack.

- **TCP Log.pdf**: This document contains the raw **TCP** log captured from **Wireshark**, showing the network traffic during the incident. It includes the packets exchanged between the client and the server, which were analyzed to identify the attack pattern and its effects on the server’s performance.

- **Color Coded TCP Log.pdf**: This document is a **color-coded version** of the **TCP log**. It highlights the following:
  - **Green**: Normal TCP connection handshakes.
  - **Red**: Activity related to the attack (e.g., SYN packets from the suspected attacker).
  - **Yellow**: Normal TCP connections failing due to the attack (e.g., connection timeouts or failed handshakes).

🛡️ **Skills Demonstrated**  
- Packet capture and analysis using **Wireshark**.  
- Identification of **SYN flood** attacks in network traffic.  
- Understanding and explaining the **TCP Three-Way Handshake** process.  
- Documentation and reporting of cyber incidents using an **incident report template**.  
- Analysis of the impact of **DoS attacks** on server performance.

✅ **Outcome**  
This exercise demonstrates how to identify, document, and analyze a **DoS attack** on a web server. The findings highlight the importance of packet capture analysis in detecting malicious activity and understanding its effects on server performance. The ability to correctly identify attack patterns and explain the underlying cause of network disruptions is crucial for responding to and mitigating future attacks.
