# Linux File Permissions - Access Control Management

## 📌 Overview

This folder contains the results of a hands-on exercise focused on managing **Linux file permissions** to ensure proper access control within a large organization's research team. The purpose of this exercise is to demonstrate how to examine and adjust file system permissions using Linux command-line tools in order to align with organizational authorization policies and strengthen system security.

## 🧩 Scenario Summary

I am a cybersecurity professional working in a large organization, primarily supporting a research team. Part of my responsibility is to ensure that team members are only granted access to files and directories for which they are authorized.

In this scenario, I was tasked with reviewing the existing file permissions on a Linux system to determine whether they comply with internal access control policies. If discrepancies were found, I modified permissions accordingly — granting appropriate access to authorized users and removing access for unauthorized users — to maintain system integrity and confidentiality.

## 🎯 Objectives

The objectives of this exercise are to:

- Identify and document the current file permissions in a Linux environment.
- Compare existing permissions against expected user authorizations.
- Use appropriate Linux commands to modify file and directory permissions.
- Remove unnecessary or unauthorized access to secure sensitive resources.
- Explain and justify each step and command used in the permission management process.

## 📁 Files Included

- `File_Permissions_Report.pdf`: A detailed report including:
  - Summary of the initial file system state.
  - Step-by-step permission analysis.
  - Commands used to inspect and modify file permissions.
  - Justification for each permission change.
  - Screenshots or command output as evidence of the process.

- `Current_File_Permissions.pdf`:  
  This document displays the file structure of the `/home/researcher2/projects` directory and the permissions of the files and subdirectory it contains. 

## 🛡️ Skills Demonstrated

- Practical use of Linux commands such as `ls -l`, `chmod`, `chown`, and `chgrp`.
- Understanding of file permission notation (symbolic and numeric) and user/group roles.
- Implementation of the principle of least privilege in access control.
- Analysis of authorization requirements in a multi-user environment.
- System hardening through manual permission auditing and correction.

## ✅ Outcome

This project demonstrates my ability to analyze and enforce proper file permissions in a Linux system, ensuring that only authorized users have access to sensitive files. The exercise showcases not only my technical command of Linux permission tools but also my understanding of access control as a critical security mechanism in enterprise environments.

## 🔮 Future Recommendations

To maintain strong access control and system security, the following actions are recommended:

- Regular permission audits using automated tools or scheduled scripts.
- Implementation of user groups with defined roles to simplify permission management.
- Use of Access Control Lists (ACLs) for fine-grained permissions when needed.
- Inclusion of permission checks in onboarding/offboarding procedures.
- Continuous training for system administrators on Linux file security best practices.
