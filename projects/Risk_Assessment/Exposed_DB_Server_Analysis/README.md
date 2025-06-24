# Database Exposure Analysis - Security Risk Report

## 📌 Overview

This repository contains the results of a cybersecurity risk assessment exercise related to an exposed database server at an e-commerce company. The goal is to analyze the root cause of the exposure, evaluate current access controls, and propose actionable recommendations to strengthen the organization’s cybersecurity posture.

## 🧩 Scenario Summary

As a newly hired cybersecurity analyst at an e-commerce company, I discovered that the main database server—used by remote employees worldwide to retrieve customer-related data—had been publicly accessible since the company’s inception three years ago. This exposure represented a critical vulnerability that placed the company’s operations and sensitive data at significant risk.

I was tasked with performing a vulnerability assessment and communicating findings to decision-makers. The result is a detailed report evaluating the threat landscape, the likelihood and impact of potential attacks, and mitigation strategies aligned with NIST SP 800-30 Rev. 1.

## 🎯 Objectives

The objectives of this exercise are to:

* Analyze the exposure of a publicly accessible database.
* Conduct a risk assessment following NIST SP 800-30 Rev. 1 guidelines.
* Identify threat sources and threat events that could impact the organization.
* Recommend technical controls to reduce the attack surface.
* Justify how these measures align with best practices in cybersecurity.

## 📁 Files Included

* `Vulnerability assessment report.pdf`:  
  A structured vulnerability assessment document containing:
  - **System Description**: Technical details of the server environment.
  - **Scope & Purpose**: Objectives of the evaluation and business value of securing the server.
  - **Risk Assessment**: Methodology, threat analysis, and business impact.
  - **Remediation Strategy**: Concrete steps for improving security, including:
    - Role-based access control (RBAC)
    - Multi-factor authentication (MFA)
    - IP allow-listing
    - Transition to TLS encryption
    - Auditing and monitoring mechanisms

* `NIST SP 800-30 Rev. 1.pdf`:  
  A summarized reference guide including:
  - **Threat Sources**: Internal, external, and environmental threat categories.
  - **Threat Events**: Examples such as exfiltration, DoS, certificate spoofing, and MITM attacks.
  - **Risk Metrics**: Qualitative and quantitative values for likelihood and severity.
  - **Assessment Framework**: Scoring guidelines and risk prioritization logic.

## 🛡️ Skills Demonstrated

* Cybersecurity risk analysis using NIST methodologies.
* Identification of infrastructure vulnerabilities.
* Alignment of mitigation strategies with security frameworks.
* Communication of technical risks to non-technical stakeholders.
* Development of security controls for real-world applications.

## ✅ Outcome

This exercise underscores the critical importance of protecting publicly accessible infrastructure and conducting regular vulnerability assessments. By applying structured risk analysis and NIST-aligned remediation strategies, the organization can reduce exposure to threats, maintain system integrity, and uphold trust in its data handling practices.

Aligning remediation efforts with NIST SP 800-30 Rev. 1 provides a defensible and industry-recognized approach to cybersecurity risk management.
