# USB Data Exposure Analysis - Security Incident Report

## 📌 Overview

This repository contains the results of a security analysis exercise conducted by the cybersecurity team at *Hospital Retórico*. The objective of the exercise is to investigate the potential risks associated with the discovery of an unclaimed USB device found on hospital premises and to evaluate appropriate response protocols for handling unknown media.

The exercise simulates a real-world incident where digital hygiene, curiosity, and secure investigative practices intersect, offering insight into attacker strategies, organizational vulnerabilities, and control mechanisms.

## 🧩 Scenario Summary

Upon arriving at work one morning, a member of the hospital's cybersecurity team found a USB flash drive lying on the ground in the hospital parking lot. The device bore the hospital’s official logo, suggesting it may have originated from within the organization.

To investigate safely, the USB was analyzed using a secure virtualized environment—an isolated system with no external network or file access. This ensured that any potential malware or harmful code on the USB could not compromise production systems or sensitive information.

The device was found to contain a mixture of personal and professional files, including:

- Family and pet photos
- A new hire welcome letter
- An employee shift schedule

These findings raise several red flags regarding data classification, storage, and device usage policies.

## 🎯 Objectives

The main goals of this exercise are to:

- Assess the contents and potential threats posed by the discovered USB device.
- Evaluate how an attacker might exploit the exposed data.
- Identify technical, operational, and managerial safeguards that could mitigate such risks.
- Reinforce best practices for handling unknown or misplaced digital media.

## 📁 Files Included

* `Parking lot USB exercise.pdf`: A detailed incident report that includes:
  - **Device Content Summary**: Overview of discovered files.
  - **Attacker Mindset**: Exploration of how the data could be weaponized against Jorge (presumed USB owner) or the hospital.
  - **Risk Analysis**: Identification of applicable controls and proposed mitigation strategies across technical, operational, and managerial dimensions.

* `Device content.png`: A visual representation of the USB file structure, revealing a mix of personal photos, onboarding documents, and employee schedules.

## 🛡️ Skills Demonstrated

* Secure analysis of potentially compromised devices using virtualization.
* Identification of data exposure risks from physical media.
* Risk assessment from an attacker’s perspective.
* Application of security frameworks and mitigation strategies.
* Documentation of findings and security recommendations.

## ✅ Outcome

This exercise highlights the potential dangers of unmanaged physical media and the importance of training staff on secure data practices. It also underscores the value of containment strategies such as sandboxing and virtualization when investigating unknown devices.

By proactively addressing the risks revealed through this scenario, *Hospital Retórico* can strengthen its data protection policies, employee awareness, and incident response preparedness.
