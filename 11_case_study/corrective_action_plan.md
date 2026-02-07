# Corrective Action Plan (CAPA) – Case Study

## 1. CAPA Overview

| Field | Value |
|------|-------|
| Case Study | MedTech Solutions Ltd |
| CAPA ID | CAPA-001 |
| Date Identified | 2026-02-05 |
| Source Document | 11_case_study/internal_audit.md |

**Purpose:**  
Record the corrective actions taken for issues found during the case study audit to ensure compliance with ISO/IEC 27001:2022 and to prevent recurrence of similar issues. :contentReference[oaicite:1]{index=1}

---

## 2. Identified Non-Conformity / Issue

**Description:**  
Access rights reviews in the cloud environment were not performed for all environments (e.g., development systems were not reviewed).  
**Impacted Control(s):**  
- ISO 27001 Annex A.5.18 – Access rights  
**Evidence Reference:**  
- `05_evidence_review/sample_cloud_evidence/A5.18_access_review.xlsx`

---

## 3. Root Cause Analysis

**Root Cause:**  
The quarterly access review process was not updated to include all environments, leading to development systems being omitted.

**Underlying Reasoning:**  
- Lack of documented scope in the access review process  
- No checklist requiring review of all system environments

---

## 4. Corrective Action Plan

| Action ID | Corrective Action | Owner | Target Completion Date |
|-----------|------------------|-------|------------------------|
| CA-001 | Update access review procedure to include all environments | IT Security Manager | 2026-02-15 |
| CA-002 | Conduct access review across all environments for the last quarter | IT Security Team | 2026-02-10 |
| CA-003 | Train auditors on updated scope and checklist | ISMS Lead | 2026-02-20 |

---

## 5. Preventive Action Plan

| Action ID | Preventive Action | Owner | Target Completion Date |
|-----------|------------------|-------|------------------------|
| PA-001 | Incorporate cloud environment inventory into risk register | ISMS Lead | 2026-02-18 |
| PA-002 | Implement quarterly reminders for reviews | IT Operations | 2026-02-12 |

---

## 6. Verification & Effectiveness

**Method:**  
Verify that the updated access review procedure includes all system environments and that future reviews document compliance.  
**Verification Date:**  
2026-02-28  
**Verification Results:**  
☑ All environments included in review  
☑ Checklist updated and applied

---

## 7. Close-Out

| Role | Name | Signature | Date |
|------|------|-----------|------|
| ISMS Owner |  |  |  |
| Lead Auditor |  |  |  |

