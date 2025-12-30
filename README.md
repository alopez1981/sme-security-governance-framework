# SME Security Governance Framework 🛡️

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Compliance](https://img.shields.io/badge/Compliance-GDPR%20Ready-blue)](https://gdpr.eu/)
[![Status](https://img.shields.io/badge/Status-Active-success)]()

> A practical, lightweight, and scalable **Security Governance Kit** designed for SMEs transitioning from "Startup
> Chaos" to "Corporate Structure".

---

## Overview

Growing companies often hit a "Security Wall": they have revenue, but their operations rely on tribal knowledge and "
heroes". [cite_start]This repository provides the foundational documentation to implement an **ISMS-Lite** (Information
Security Management System), based on **ISO 27001** principles but adapted for agile teams[cite: 339, 428].

### The Core Philosophy: "Process First, People Proof"

Security shouldn't depend on a specific person having a good day. [cite_start]It must depend on **documented processes,
automated checks, and clear metrics**.

---

## Repository Structure

This framework is organized into functional modules ready for deployment:

### 1. Policies (`/policies`)

The "Law" of the organization.

* **General Security Policy:** Covers Access Control, Device Encryption, and Clean Desk
  policies.
* **Cloud Security:** Specific controls for Google Workspace/AWS (MFA enforcement, "Public Link"
  restrictions).
* **Business Continuity (BCP):** Protocols for when things go wrong (Provider outages, Office
  unavailability).

### 2. Playbooks (`/playbooks`)

Actionable guides for "War Time" scenarios.

* **Incident Response Plan (IRP):** A 7-step protocol from *Identification* to *Recovery*, including legal
  notification timelines (<72h for GDPR breaches).

### 3. ✅ Checklists (`/checklists`)

For the "Peace Time" routine.

* **Quarterly Security Audit:** A rigorous inspection list for Drive permissions, Zombie accounts, and
  Backup integrity tests.

### 4. Procedures (`/procedures`)

Standard Operating Procedures (SOPs) for Identity Management.

* **Onboarding/Offboarding:** The "Kill-switch" protocol to revoke access immediately upon employee
  exit.
* **ROPA (Record of Processing Activities):** Data mapping template for GDPR compliance.

### 5. Metrics (`/metrics`)

Because you can't manage what you don't measure.

* **Security KPIs:** Tracking MFA adoption, Mean Time to Respond (MTTR), and Patching SLA
  compliance.

---

## Getting Started

1. **Clone the repo:**
   ```bash
   git clone [https://github.com/your-username/sme-security-governance-framework.git](https://github.com/your-username/sme-security-governance-framework.git)

2. **Customize**

Replace the placeholders (e.g, [Company Name],[IT Dept]) with your organization's details.

3. **Audit**

Run the `checklists/quarterly-audit-checklist.md` to assess your current security posture.

4. **Enforce**

Publish the policies and start the "Security by Default" culture shift.

---

## Tech Stack & Context

This framework is designed to govern environments using:

* Identity: Google Workspace, AWS, IAM, Azure AD.
* Infrastructure: Hybrid (on-premise + Cloud).
* Development: DDD/ Hexagonal Architecture workflows (secure SDLC).

## Author

Albert López - Engineering Manager & SecOps Lead

Building scalable tech operations. Turning cost center into efficiency engines.

* Focus: Scalability, Governance, DDD and Business Intelligence.

---

Disclaimer: This repository is for educational and structural purpose. Always consult with legal counsel for specific
GDPR/Compliance requirements.

