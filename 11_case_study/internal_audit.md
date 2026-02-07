# Internal Information Security Audit – Case Study

## 1. Audit Overview

| Item | Description |
|-----|------------|
| Organization | MedTech Solutions Ltd |
| Audit Type | Internal ISMS Audit |
| Standard | ISO/IEC 27001:2022 |
| Audit Date | 2026-02-01 |
| Auditor | Internal ISMS Auditor |
| Audit Scope | Cloud-hosted systems, access control, logging, backup |
| Audit Criteria | ISO/IEC 27001:2022 clauses & Annex A |

---

## 2. Audit Objectives

The objectives of this internal audit were to:
- Verify conformity of the ISMS with ISO/IEC 27001:2022
- Confirm that Annex A controls are implemented as defined in the SoA
- Evaluate effectiveness of selected controls
- Identify gaps, risks, and improvement opportunities

---

## 3. Audit Methodology

The audit was conducted using:
- Document review (policies, SoA, RCM)
- Evidence review (cloud screenshots, logs, reports)
- Interviews with IT and security personnel
- Sampling of technical and procedural controls

---

## 4. Documents Reviewed

- Statement of Applicability (`03_control_framework_mapping/statement_of_applicability.md`)
- Risk Control Matrix (RCM)
- Risk Register
- Cloud access review records
- Backup and restore test reports
- Logging and monitoring dashboards

---

## 5. Controls Sampled

| Annex A Control | Control Name |
|----------------|-------------|
| A.5.15 | Access control |
| A.5.18 | Access rights |
| A.8.5 | Secure authentication |
| A.8.13 | Information backup |
| A.8.15 | Logging |

---

## 6. Audit Findings Summary

| ID | Type | Control | Description |
|----|------|--------|-------------|
| F-01 | Minor Nonconformity | A.5.18 | Access reviews not performed for all environments |
| F-02 | Conformity | A.8.5 | MFA enabled for privileged cloud accounts |
| F-03 | Conformity | A.8.13 | Backup and restore testing performed successfully |
| F-04 | Observation | A.8.15 | Logging dashboard available but alert thresholds undocumented |

---

## 7. Detailed Finding (Example)

**Finding ID:** F-01  
**Control:** Annex A.5.18 – Access rights  

**Description:**  
Access reviews were conducted for production systems; however, development environments were excluded from the quarterly review.

**Evidence:**  
- `sample_cloud_evidence/A5.18_access_review.xlsx`

**Risk:**  
Unauthorized or unnecessary access may remain undetected in non-production environments.

---

## 8. Conclusion

The ISMS is partially effective and generally aligned with ISO/IEC 27001:2022 requirements.  
One minor nonconformity and one observation were identified.  
Corrective actions are required and documented in the Corrective Action Plan.

---

## 9. Audit Closure

| Role | Name | Date |
|-----|------|------|
| Auditor |  |  |
| ISMS Owner |  |  |
