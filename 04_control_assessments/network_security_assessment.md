# Network Security Audit Program

## Objective
Assess whether network security controls adequately protect systems from unauthorized access,
lateral movement, and external attacks.

## Scope (Typical)
- Firewalls (on‑prem & cloud)
- Network segmentation (VLANs, security zones)
- Remote access (VPN)
- IDS / IPS monitoring
- Network logging & alerting

---

## Key Risks
- Excessive or unmanaged firewall rules
- Flat network enabling lateral movement
- Weak VPN authentication
- IDS alerts not monitored or tuned
- Insufficient network visibility

---

## Control Expectations
- Firewalls follow least‑privilege rule design
- Segmentation enforced between user, server, and sensitive zones
- VPN access protected by MFA
- IDS/IPS alerts reviewed and documented
- Network logs centrally collected and retained

---

## Test Procedures

### 1. Firewall Rule Management
- Obtain firewall rule base export
- Identify:
  - Any‑Any rules
  - Inactive or shadowed rules
  - Rules without business justification
- Sample 10 high‑risk rules and validate:
  - Owner
  - Approval
  - Last review date

### 2. Network Segmentation
- Review network diagrams
- Verify separation between:
  - User network
  - Server network
  - OT / sensitive environments
- Sample 3 segmentation controls and validate enforcement

### 3. VPN & Remote Access
- Review VPN configuration
- Verify MFA enforcement
- Sample 5 VPN users:
  - Access level
  - Approval
  - Logging enabled

### 4. IDS / IPS Monitoring
- Review IDS/IPS deployment scope
- Verify alert review process
- Sample 5 alerts:
  - Triage notes
  - Escalation evidence
  - Closure rationale

### 5. Network Logging
- Verify network device logs are sent to SIEM
- Check retention period
- Confirm correlation use cases exist

---

## Evidence Examples
- Firewall configuration export
- Network diagrams
- VPN user list
- IDS alert samples
- SIEM dashboard screenshots (sanitized)

---

## Typical Findings
- Firewall rules without expiry or review
- IDS alerts not investigated
- Over‑permissive VPN access
