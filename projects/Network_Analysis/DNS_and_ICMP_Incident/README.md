# DNS and ICMP Traffic Analysis - Security Incident Report

## 📌 Overview

This folder contains the results of an exercise focused on analyzing DNS and ICMP network traffic during a service interruption. The purpose of this exercise is to demonstrate the ability to identify network-layer communication issues using protocol analysis tools, and to understand the role of DNS and ICMP in detecting and diagnosing service disruptions.

## 🧩 Scenario Summary

A company providing IT services received reports from client users who were unable to access the website `www.yummyrecipesforme.com`. All reported encountering the error message: “destination port unreachable.” An initial attempt to reproduce the issue confirmed the same result. A packet capture was performed using `tcpdump` to trace the network communication sequence during the attempted connection.

The DNS query was initiated using the UDP protocol to resolve the domain name, targeting port 53. However, the server responded with an ICMP error message indicating that the UDP destination port was unreachable. The captured traffic revealed that each DNS query was met with an ICMP Type 3 Code 3 response, meaning the destination port was closed or no DNS service was listening on port 53 at the destination IP.

This type of ICMP response suggests a failure in DNS resolution due to misconfigured or unavailable DNS services. As a result, the web browser was unable to resolve the domain name to an IP address, preventing the subsequent HTTPS request from being executed.

## 🎯 Objectives

The objectives of this exercise are to:

* Identify which network protocols were involved and affected during the incident.
* Interpret the relationship between DNS queries (UDP) and ICMP error messages.
* Analyze the packet data to determine the root cause of the service access issue.
* Document findings using a structured incident report and raw packet capture data.

## 📁 Files Included

* `Cybersecurity_Incident_Report_Network_Traffic_Analysis.pdf`: Full incident report detailing the timeline, IP communication, analysis of protocols, and IT response steps.

* `TCPDump_Record.png`: Image showing the raw tcpdump log, including the DNS request sent over UDP, the ICMP responses indicating that the DNS server's port 53 was unreachable, and timestamps with relevant protocol and IP information.

## 🛡️ Skills Demonstrated

* Network traffic analysis using `tcpdump`.
* Identification of ICMP Type 3 Code 3 messages in response to failed DNS queries.
* Interpretation of UDP-based DNS requests and related error handling at the network layer.
* Application of the TCP/IP model for packet-level diagnosis of service disruptions.
* Incident documentation and reporting based on real-world scenarios.

## ✅ Outcome

This exercise demonstrates a practical application of protocol analysis to investigate and document a DNS resolution failure. The analysis highlights how ICMP error messages can reveal issues in service availability and how analysts can interpret raw packet data to identify affected protocols and services. This methodology supports effective incident reporting and contributes to developing proactive network monitoring strategies.
