# PSPF Security Maturity Offering

This PSPF Security Maturity Offering connects Engage Squared’s Microsoft 365 and Purview capabilities to the **Protective Security Policy Framework (PSPF)**.  
It builds on the **Essential 8** and **Data Security Maturity** models by adding the governance and assurance layer required for Commonwealth entities and regulated industries.

---

## 1. Relationship Between PSPF, Essential 8, and ISM

| Framework | Purpose | Relationship |
|---|---|---|
| **PSPF (Protective Security Policy Framework)** | Whole-of-government framework covering governance, information, personnel, and physical security | Establishes security expectations for Australian Government entities |
| **ISM (Information Security Manual)** | Control catalogue that operationalises PSPF Policy 10 | Provides the technical control baseline used to achieve PSPF outcomes |
| **Essential 8** | Priority mitigation strategies against common cyber threats | Practical subset of ISM controls, required under PSPF Policy 10 |
| **M365 + Purview** | Platform that implements and evidences technical and governance controls | Provides measurable compliance with PSPF and E8 requirements |

---

## 2. PSPF Domain Alignment

| PSPF Domain | Example Policies | Typical Engage Squared Activities | Microsoft Capability Alignment |
|---|---|---|---|
| **Governance** | Policy 1–3: Governance, Risk, and Assurance | Establish governance structures, define security ownership, automate reporting | Purview Compliance Manager, Power BI dashboards, Compliance Score API |
| **Information Security** | Policy 10: Safeguarding Information from Cyber Threats | Assess and implement E8 controls, configure M365 security baselines, monitor Secure Score | Purview Information Protection, Entra ID, Intune, Defender XDR |
| **Personnel Security** | Policy 12–15 | Build onboarding/offboarding workflows, enforce privileged access reviews | Entra ID PIM, Access Reviews, Purview Audit, Power Automate |
| **Physical Security** | Policy 16–18 | Integrate access systems, manage visitor and asset data | Power Apps + Power Automate integrations |
| **Assurance and Reporting** | Policy 2 and 5 | Deliver continuous compliance dashboards and evidence packs | Compliance Manager, Secure Score, Purview Audit logs |

---

## 3. PSPF Maturity Levels

| Level | Description | Engage Squared Focus |
|---|---|---|
| **Level 1 – Ad Hoc** | Limited security governance or documentation | Establish baseline governance, E8 Level 1 controls |
| **Level 2 – Developing** | Policies defined but not fully implemented | Deploy Purview labeling, Intune compliance, and DLP |
| **Level 3 – Managing** | Security integrated into operations | Automate compliance via Purview dashboards and Secure Score |
| **Level 4 – Embedded** | Security embedded in governance and culture | Continuous assurance and executive reporting |
| **Level 5 – Optimised** | Predictive analytics and AI support decision-making | Security Copilot, automated insights, proactive risk management |

---

## 4. PSPF + Essential 8 Control Mapping

| PSPF Policy 10 Requirement | Related Essential 8 Control | Supporting M365 Capability |
|---|---|---|
| Patch applications and operating systems | **Patch Applications**, **Patch Operating Systems** | Intune, Windows Update for Business |
| Multi-factor authentication | **MFA** | Entra ID Conditional Access, Authenticator |
| Restrict admin privileges | **Restrict Admin Privileges** | Entra ID PIM, Access Reviews |
| Protect against malicious code | **Application Control**, **User Application Hardening** | Defender for Endpoint, ASR rules |
| Prevent macro malware | **Configure MS Office Macros** | Office Cloud Policy Service |
| Back up critical systems | **Regular Backups** | SharePoint / OneDrive versioning, retention labels |
| Restrict unapproved apps | **Application Control** | WDAC, Smart App Control |
| Maintain incident response capability | **Operational Resilience** | Defender XDR, Security Copilot, Purview Audit |

---

## 5. Engage Squared PSPF Offering Levels

| Offering Level | Objectives | Example Deliverables | Key Outcomes |
|---|---|---|---|
| **Level 1 – Baseline PSPF Readiness** | Establish governance, align to PSPF Policy 10 | PSPF/E8 maturity assessment, roadmap, Secure Score snapshot | Visibility of current state and gaps |
| **Level 2 – Integrated Information Security** | Embed E8 controls and Purview governance | Label taxonomy, auto-labeling, Insider Risk, DLP policy pack | Controlled data flows and monitoring |
| **Level 3 – Assurance and Continuous Compliance** | Automate PSPF reporting and risk visibility | PSPF Control Register, Compliance Manager dashboard, executive report pack | Continuous compliance and executive assurance |

---

## 6. Integration with Engage Squared Data Security Offering

| Engage Squared Level | PSPF Focus Area | Supporting Capabilities |
|---|---|---|
| **Foundational (Level 1)** | Data Discovery and Classification | Purview Labels, Records Management, Secure Score |
| **Established (Level 2)** | Policy Enforcement and Monitoring | DLP, Insider Risk, Compliance Manager |
| **Advanced (Level 3)** | Assurance and Response | eDiscovery Premium, Defender XDR, Security Copilot, DSPM Readiness |

---

## 7. Recommended Engage Squared Next Steps

1. **Build a PSPF Assessment Template**  
   Create an Excel or Power BI tool that scores maturity across Governance, Information, Personnel, and Physical domains.  

2. **Extend the Data Security Maturity Workbook**  
   Add a PSPF tab with direct policy mapping and recommended actions.  

3. **Develop a PSPF Workshop Deck**  
   Use the three offering levels as a framework for consulting engagements.  

4. **Leverage Purview Compliance Manager**  
   Use Microsoft’s built-in PSPF and ISM templates for evidence mapping and control tracking.  

5. **Position PSPF as the governance layer**  
   Use Essential 8 and DSPM as the technical foundation under Policy 10 for government and critical infrastructure customers.  

---

## 8. Example Engage Squared PSPF Narrative (For Workshop or Deck)

> “Our PSPF offering brings together governance, technology, and assurance.  
> We help agencies not just implement the Essential 8, but demonstrate compliance across PSPF domains through real-time data visibility in Microsoft Purview and Defender.  
> By integrating Secure Score, Compliance Manager, and Power BI reporting, we give executives a single view of their protective security posture.”

---

## 9. Supporting Resources

- [Protective Security Policy Framework (PSPF)](https://www.protectivesecurity.gov.au)
- [Australian Cyber Security Centre – Essential Eight](https://www.cyber.gov.au/resources-business-and-government/essential-eight)
- [Microsoft Compliance Manager for PSPF and ISM](https://learn.microsoft.com/en-us/microsoft-365/compliance/)
- [Australian ISM Framework](https://www.cyber.gov.au/resources-business-and-government/government/ism)

---

**Author:** Engage Squared Security Practice  
**Purpose:** PSPF Readiness and M365 Compliance Acceleration
