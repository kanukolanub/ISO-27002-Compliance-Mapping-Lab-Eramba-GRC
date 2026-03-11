
# ISO 27002 Compliance Mapping Lab (Eramba GRC)

## 🎯 Overview

This project demonstrates the practical application of **Governance, Risk, and Compliance (GRC)** principles using the **Eramba Community Edition** platform. The lab focuses on the transition from identifying regulatory requirements to implementing and auditing functional internal solutions.

By the end of this exercise, I established a "Defensible Compliance" posture where high-level ISO requirements are directly linked to tangible organizational evidence (Policies and Internal Controls).

---

## 🛠️ Technology Stack

* **GRC Platform:** Eramba Community Edition
* **Framework:** ISO 27002:2022 (Information security, cybersecurity and privacy protection)
* **Environment:** Self-hosted GRC Lab

---

## 🚀 Lab Workflow

### 1. Framework Acquisition & Integration

* **Action:** Imported the **ISO 27002:2022 Annex A** compliance package via the Eramba Community download portal.
* **Outcome:** Established a localized library of 93 security controls, categorized by Organizational, People, Physical, and Technological themes.

### 2. Solution Architecture

I defined two distinct types of "solutions" within the GRC ecosystem to satisfy the framework:

* **The Policy (Documentary Evidence):** Created an *Information Security Policy*. This serves as the "Governance" layer, proving the organization has formal intentions and management support.
* **The Internal Control (Operational Evidence):** Created a *Monthly User Access Review* control. This serves as the "Technical" layer, proving that a specific, repeatable activity is occurring to mitigate risk.

### 3. Compliance Analysis & Mapping

I mapped the identified "Solutions" to the "Problem" (the ISO requirements):

| ISO 27002 Requirement | Control Title | Solution Type | Logic |
| --- | --- | --- | --- |
| **5.1 (Policies for InfoSec)** | InfoSec Policy v1.0 | Policy | Satisfies the need for documented management direction. |
| **8.2 (Privileged Access)** | Monthly Access Review | Internal Control | Satisfies the need for restricted and reviewed access rights. |

### 4. The Audit Cycle & Dashboarding

* **Verification:** Logged a successful audit for the "Monthly Access Review" to simulate evidence collection.
* **Visualization:** Monitored the **Compliance Analysis Dashboard** to ensure the status transitioned from "Undefined" to "Compliant" (Green).

---

## 🧠 Key Skills & Takeaways

* **Relational Mapping:** Gained hands-on experience in connecting abstract regulatory clauses to specific, auditable business processes.
* **Control Ownership:** Configured "Accountable" and "Responsible" roles within the tool, simulating a real-world corporate environment.
* **Evidence-Based Compliance:** Moved beyond the "Checklist" mentality to show how continuous auditing maintains a "Green" compliance status.
* **Hybrid Threat Awareness:** Integrated concepts from the *2025 Microsoft Digital Defense Report* by focusing on identity-centric controls (ISO 8.2) as a primary defense against lateral movement.

---
