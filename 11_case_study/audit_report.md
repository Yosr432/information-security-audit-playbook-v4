# Internal Audit Report – ISO/IEC 27001 Case Study

## 1. Executive Summary

An internal audit of the Information Security Management System (ISMS) was conducted to assess conformity with ISO/IEC 27001:2022.  
The audit confirmed that core security controls are implemented; however, opportunities for improvement were identified.

---

## 2. Audit Scope

The audit covered:
- Cloud access management
- Authentication mechanisms
- Backup and recovery processes
- Logging and monitoring
- Control implementation as defined in the SoA

---

## 3. Overall Audit Results

| Result Category | Count |
|----------------|------|
| Conformities | 3 |
| Minor Nonconformities | 1 |
| Major Nonconformities | 0 |
| Observations | 1 |

---

## 4. Key Strengths

- Multi-factor authentication enforced for privileged cloud users
- Regular backups performed with successful restore testing
- Centralized logging implemented for critical systems

---

## 5. Identified Issues

### 5.1 Minor Nonconformity

**Control:** Annex A.5.18 – Access rights  
**Issue:**  
Quarterly access reviews did not include development environments.

**Impact:**  
Incomplete access governance across cloud environments.

---

### 5.2 Observation

**Control:** Annex A.8.15 – Logging  
**Observation:**  
Logging dashboards are implemented, but alert thresholds and response procedures are not formally documented.

---

## 6. Recommendations

- Update access review procedures to include all environments
- Document logging alert thresholds and escalation procedures
- Perform periodic effectiveness reviews of implemented controls

---

## 7. Corrective Actions

Corrective and preventive actions have been defined and tracked in:

📄 `11_case_study/corrective_action_plan.md`

---

## 8. Audit Conclusion

Based on the audit evidence reviewed, the ISMS demonstrates **partial conformity** with ISO/IEC 27001:2022.  
With implementation of the identified corrective actions, the ISMS is expected to achieve full conformity.

---

## 9. Approval

| Role | Name | Signature | Date |
|-----|------|-----------|------|
| Lead Auditor |  |  |  |
| ISMS Owner |  |  |  |
