# SQL Security Investigation - Access Anomaly Detection

## 📌 Overview

This folder contains the results of a hands-on security investigation focused on detecting and analyzing **suspicious login behavior** within a large organization. The goal of this exercise was to demonstrate how Structured Query Language (SQL) can be used to examine authentication data, correlate user and device activity, and identify potential security threats.

## 🧩 Scenario Summary

I am a cybersecurity professional working in a large organization, responsible for protecting the integrity of employee access and authentication systems. Recently, I discovered several **potential security issues** related to **login attempts** on employee machines.

In this scenario, I was tasked with analyzing organizational data from two primary datasets: the `employees` table and the `log_in_attempts` table. My role was to apply SQL filters to extract meaningful patterns and investigate anomalies such as unauthorized access attempts, unusual login hours, and unexpected device usage.

## 🎯 Objectives

The objectives of this investigation were to:

- Retrieve and filter login data to expose suspicious activity.
- Join employee metadata with login records for contextual analysis.
- Detect login attempts from unauthorized or unknown machines.
- Identify repeated failed login attempts that could indicate brute-force attacks.
- Document investigative steps and findings to support security enhancements.

## 📁 Files Included

- `Apply filters to SQL queries.pdf`:  
  This document contains all the results of the SQL-based security investigation exercise. It includes:

  1. **Project Description** 
  2. **Retrieve After Hours Failed Login Attempts** – Query to detect failed login attempts outside of regular working hours.
  3. **Retrieve Login Attempts on Specific Dates** – Filters used to investigate access on specific, high-risk dates.
  4. **Retrieve Login Attempts Outside of Mexico** – Identification of geographically suspicious login attempts.
  5. **Retrieve Employees in Marketing** – Query to extract employees from the Marketing department.
  6. **Retrieve Employees in Finance or Sales** – Queries targeting users in the Finance or Sales departments.
  7. **Retrieve All Employees Not in IT** – Query to find users outside the IT department.
  8. **Summary** 

  This document illustrates how targeted SQL queries were used to support an effective security investigation within the organization.

## 🛡️ Skills Demonstrated

- Advanced use of SQL for filtering, joining, and aggregating data.
- Analysis of authentication logs to detect security threats.
- Correlation of user roles with access behavior.
- Practical knowledge of access control and insider threat indicators.
- Creation of reproducible investigation queries for ongoing use.

## ✅ Outcome

This project demonstrates my ability to apply SQL techniques for security analysis and anomaly detection in authentication systems. The insights from this investigation will help the organization proactively respond to access-related threats and strengthen its security posture through data-driven policies.
