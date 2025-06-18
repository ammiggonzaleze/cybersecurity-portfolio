# 🛡️ Improving Authentication and Authorization - Security Incident Report

## 📌 Overview

This folder contains the results of a cybersecurity exercise focused on analyzing and addressing an access control failure at a growing small business. The goal is to understand the root cause of a near-miss financial fraud incident, assess the current authentication and authorization practices, and recommend improvements to prevent similar events in the future.

## 🧩 Scenario Summary

As the first cybersecurity professional hired by the company, I was tasked with investigating an attempted unauthorized transfer to an unknown bank account. The Chief Financial Officer (CFO) confirmed they did not initiate the transaction, and fortunately, the payment was halted in time. 

My investigation began with a review of access logs and user accounts to identify any anomalies. I documented potential threat actors, discovered weaknesses in the company's access control mechanisms, and evaluated how these were exploited. Notably, I found that all users had administrator privileges, and at least one former employee account remained active long after their departure, leading to a serious vulnerability.

This situation reveals significant gaps in authentication, authorization, and account lifecycle management—factors that must be addressed to safeguard company assets and operations as the organization continues to grow.

## 🎯 Objectives

The objectives of this exercise are to:

* Investigate the security incident and summarize the key findings.
* Identify access control issues that contributed to the event.
* Evaluate the current account and privilege management processes.
* Recommend actionable technical and administrative measures to improve authentication and authorization.
* Justify the proposed changes using industry best practices and security standards.

## 📁 Files Included

* `Accounting_exercise.xlsx`: A review of system event logs to identify suspicious activity, detect vulnerabilities, and trace user behavior related to the incident.
* `Access_control_worksheet.pdf`: A structured document covering:
  - **Incident Summary**: Timeline and actors involved in the security breach attempt.
  - **Control Issues**: Key weaknesses, such as excessive privileges and inactive account management.
  - **Recommendations**:
    - Implementation of strict role-based access controls (RBAC).
    - Periodic audits to enforce the principle of least privilege.
    - Immediate deactivation of accounts for former employees.
  - **Justification**: Explanation of how each proposed control enhances system integrity and reduces risk.

## 🛡️ Skills Demonstrated

* Log analysis and incident investigation.
* Identification of flaws in access control and account management.
* Application of the principle of least privilege in a real-world context.
* Development of technical and procedural recommendations aligned with NIST and cybersecurity best practices.
* Risk mitigation planning for authentication and authorization controls.

## ✅ Outcome

This exercise highlights the importance of robust access control practices in preventing unauthorized system actions. By eliminating unnecessary administrator privileges and enforcing timely account deactivation, the company can significantly reduce its exposure to internal and external threats. These improvements are essential to supporting the organization’s secure growth and operational resilience.
