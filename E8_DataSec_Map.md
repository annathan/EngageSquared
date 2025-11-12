# Essential 8 + Data Security Maturity Model

This framework shows how Microsoft 365 can raise both Essential 8 maturity and data security maturity.  
It maps practical M365 controls to ACSC Essential 8 and outlines steps from Level 0 to Level 3 across identity, devices, data, and operations.

---

## 1. Alignment Framework

| Maturity Area | Essential 8 Focus | Data Security Focus | Relevant M365 Capabilities |
|---|---|---|---|
| **Identity & Access** | MFA, Admin Privileges | Access governance, insider risk | Entra ID, Conditional Access, Privileged Identity Management, Access Reviews |
| **Device & Application Security** | Application Control, Patching, Hardening | Endpoint protection, configuration baseline | Intune, Defender for Endpoint, Attack Surface Reduction rules, Secure Score |
| **Data Protection** | Regular Backups | Classification, labeling, encryption, DLP, lifecycle | Purview Information Protection, Sensitivity Labels, DLP, Insider Risk, Records Management |
| **Operational Resilience** | Regular Backups, Patching | Backup and recovery, incident response | OneDrive Version History, SharePoint retention, Defender portal alerts, Purview Audit |
| **Monitoring & Governance** | All | Continuous improvement, reporting | Microsoft Secure Score, Purview Risk and Compliance, M365 Lighthouse |

---

## 2. Maturity Model Mapping

| Level | Essential 8 Behaviour | Data Security Behaviour | Microsoft 365 Example Actions |
|---|---|---|---|
| **Level 0 – Unmanaged** | No consistent patching or MFA | Data unclassified, no DLP | Default tenant, open sharing, no policies |
| **Level 1 – Basic Controls** | MFA enabled, OS patched | Manual labels, limited DLP | Basic Conditional Access, user-driven labeling, alert-only DLP |
| **Level 2 – Managed Controls** | Automated patching, fewer admins | Auto classification, active monitoring | Intune compliance, Purview auto labeling, retention policies |
| **Level 3 – Optimised Controls** | Continuous assessment, risk-based MFA | Full lifecycle protection and governance | PIM with approvals, adaptive DLP, insider risk program, advanced analytics |

---

## 3. Visual Path to Maturity

## Visual Path to Maturity

| Stage | Step 1 | Step 2 | Step 3 |
|---|---|---|---|
| **Identity & Access** | MFA enabled | Conditional Access | PIM and Access Reviews |
| **Data Protection** | Manual labels | Auto labels | Adaptive DLP and Data Map |
| **Resilience** | Local backups | M365 retention | Tested restore and geo controls |



---

## 4. Essential 8 Maturity Score Table

Use ASD maturity levels 0–3.  
- **Level 0:** Not implemented  
- **Level 1:** Partially implemented  
- **Level 2:** Mostly implemented  
- **Level 3:** Fully implemented  

| Essential 8 Strategy | Current Level | Target Level | Key Risks or Observations | Recommended Actions (Quick Wins and Strategic) |
|---|---:|---:|---|---|
| Application Control | | | | |
| Patch Applications | | | | |
| Configure MS Office Macros | | | | |
| User Application Hardening | | | | |
| Restrict Admin Privileges | | | | |
| Patch Operating Systems | | | | |
| Multi-Factor Authentication | | | | |
| Regular Backups | | | | |

---

## 5. CIA Triad Summary View

| CIA Principle | Relevant Essential 8 Strategies | Examples | Current Average | Target Average | Overall Gap |
|---|---|---|---:|---:|---:|
| **Confidentiality** | MFA, Restrict Admin Privileges, Application Control, Office Macro Controls | Only the right people access data, blocked privilege escalation | | | |
| **Integrity** | Patch Applications, Patch Operating Systems, Application Control, User Application Hardening | Reduce vulnerabilities, block unauthorised changes | | | |
| **Availability** | Regular Backups, Patch Operating Systems, User Application Hardening | Keep services available, enable recovery | | | |

---

## 6. Implementation Roadmap

| Phase | Objective | M365 Focus | Outputs |
|---|---|---|---|
| **Crawl (30 days)** | Baseline security | MFA, Secure Score, core DLP | Essential 8 self-assessment, baseline policies |
| **Walk (90 days)** | Consistency and monitoring | Intune, Purview, Defender for Endpoint | Policy automation, user training, reporting |
| **Run (180 days)** | Data governance and optimisation | Insider Risk, Records Management, PIM | Compliance dashboard, executive metrics, tested recovery |

---

## 7. Notes on the Mapping

- Controls can support more than one CIA principle.  
- Use this for communication, not as the audit standard.  
- Average scores per pillar help show executive progress.  
- Quick wins include enforcing MFA, disabling macros, and enabling backups.  
- Strategic actions include auto labeling, insider risk programs, access reviews, and restore testing.  
- Always record context (for example, “backups exist but are not tested”).  

---

## 8. Optional: M365 Control Reference Starters

| Essential 8 Strategy | Primary M365 Controls | Example Config Items |
|---|---|---|
| Application Control | Intune, Defender for Endpoint | ASR rules, Smart App Control, WDAC baseline |
| Patch Applications | Intune, Windows Update for Business | Update rings, feature deferrals, compliance policies |
| Configure MS Office Macros | Intune, Office cloud policy | Block macros from internet, trusted locations |
| User Application Hardening | Defender for Endpoint, Edge policies | Block unsigned ActiveX, PDF handling, script limits |
| Restrict Admin Privileges | Entra ID PIM, Access Reviews | Just-in-time admin, approval workflows, review cycles |
| Patch Operating Systems | Intune, Windows Update for Business | Quality updates, driver and firmware cadence |
| Multi-Factor Authentication | Entra ID, Conditional Access | Require MFA, sign-in risk, device compliance |
| Regular Backups | OneDrive, SharePoint, retention | Versioning, retention labels, tested restore runbooks |
