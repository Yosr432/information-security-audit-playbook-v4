# 🛡️ Information Security Audit Playbook – ISO/IEC 27001:2022

A practical, audit-ready **Information Security Audit Playbook** aligned with **ISO/IEC 27001:2022**, designed to demonstrate how an organization can plan, execute, and document an internal information security audit with full traceability from **risk → control → evidence → improvement**.

This repository is built as a **realistic ISMS case study**, not just theory.**Note:** All examples are fictional/sanitized for use.

---


## Contents 
- Audit planning + scope pack
- Risk assessment methodology (inherent/residual)
- Framework mapping (ISO 27001 / NIST CSF / CIS)
- Control test programs (access, network, logging, vuln mgmt, cloud governance)
- Evidence checklists + sample evidence requests
- Findings, risk rating, executive summary, management response workflow



---

## 🎯 Project Objectives

This project demonstrates how to:

- Apply a **risk-based approach** to information security audits
- Map risks to **ISO 27001 Annex A controls**
- Build a **Risk Control Matrix (RCM)** with audit tests
- Collect and organize **objective evidence**
- Validate controls through **interviews**
- Perform an **internal audit** and document findings
- Manage **corrective actions (CAPA)**

It is suitable for:
- ISO 27001 learners
- Junior auditors / GRC analysts
- Cybersecurity students
- ISMS practitioners preparing for audits

---

## 🧭 High-Level Audit Flow

```mermaid
flowchart LR
    A[Governance & Scope] --> B[Risk Assessment]
    B --> C[Statement of Applicability]
    C --> D[Risk Control Matrix]
    D --> E[Audit Execution]
    E --> F[Evidence Review]
    F --> G[Audit Report]
    G --> H[Corrective Actions CAPA]
```
Folder Explanation
🏛️ 01_Governance_And_Context

Defines the ISMS foundation:

ISMS scope

Security policies

Roles & responsibilities

➡️ Aligns with ISO 27001 Clauses 4 & 5

⚠️ 02_Risk_Management

Implements the risk-based approach:

Risk assessment methodology

Risk register

Risk treatment logic

➡️ Aligns with ISO 27001 Clause 6

🧩 03_Control_Framework_Mapping

Core compliance mapping:

Statement of Applicability (SoA)

Risk Control Matrix (RCM)

Mapping to Annex A controls

Each RCM entry includes:

Risk

Control

Test procedure

Interview reference

Evidence reference

➡️ Aligns with ISO 27001 Annex A

🧪 04_Audit_Execution

Shows how the audit is performed:

Audit plan & checklists

Control testing procedures

Interview records with control owners

Interviews validate that controls are actually followed, not just documented.

➡️ Aligns with ISO 27001 Clause 9.2

📁 05_Evidence_Repository

Contains objective audit evidence, including:

Cloud security screenshots

MFA enforcement

Access reviews

Logging dashboards

Backup & restore tests

Evidence is referenced directly from the RCM and interviews.

➡️ Supports audit traceability

🧪 11_case_study

A complete end-to-end internal audit case study:

Internal audit execution

Audit report with findings

Corrective Action Plan (CAPA)

Demonstrates:

Nonconformity handling

Root cause analysis

Corrective & preventive actions

➡️ Aligns with ISO 27001 Clauses 9 & 10


this project enforces full traceability:


```mermaid
flowchart LR
    Risk --> SoA
    SoA --> RCM
    RCM --> Test
    Test --> Interview
    Interview --> Evidence
    Evidence --> Finding
    Finding --> CAPA
```


Key Concepts Explained Simply

RCM (Risk Control Matrix)
Links risks to controls and explains how auditors test them.

SoA (Statement of Applicability)
Explains which Annex A controls apply and why.

Interview Evidence
Confirms that people understand and follow the controls.

CAPA
Documents how issues are fixed and prevented from happening again.





