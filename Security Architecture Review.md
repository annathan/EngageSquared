# Security Architecture Review — Delivery Pack

## Introduction & Purpose
The Security Architecture Review (SAR) evaluates the security posture of a solution’s design against recognised best practices.  
It focuses on:

- **NIST Cybersecurity Framework** (e.g., NIST SP 800-53)  
- **Zero Trust principles** — verify explicitly, assume breach, enforce least privilege  
- **High-level security architecture controls**

**Note:** Standards like **ISO 27001** and the **Information Security Registered Assessors Program (IRAP)** are valuable and often align closely with NIST and Zero Trust. However, they require deep control-level assessment, which is outside the scope of this review.

---

## Agenda

1. **Kickoff & Context Setting**
   - Define business outcomes, review objectives, and scope
   - Confirm this is a strategic-level architecture security review

2. **Architecture Walk-through**
   - Review high-level diagrams, deployment models, data flows, trust boundaries
   - Identify areas for Zero Trust alignment

3. **Threat Modeling & NIST-Based Evaluation**
   - Apply STRIDE (or equivalent) threat modeling
   - Assess against NIST and Zero Trust control families

4. **Checklist Assessment**
   - Focus on domains most relevant to security posture:
     - Identity & Access Management
     - Network Security & Segmentation
     - Data Protection (at rest & in transit)
     - Logging, Monitoring, and Incident Response readiness
     - Resilience and Recovery Controls
   - Avoid going into full ISO/IRAP detail

5. **Findings, Recommendations & Roadmap**
   - Categorise findings as High / Medium / Low
   - Provide prioritised, actionable recommendations

6. **Review & Closeout**
   - Present findings to stakeholders
   - Assign owners and timelines for remediation

---

## Template: Security Architecture Review

Use this structure for each engagement.

### 1. Engagement Overview
- **Outcome**: Validate architecture against NIST and Zero Trust principles, producing an actionable security roadmap
- **Timebox**: 2 weeks (example)
- **Delivery Model**: Remote / Onsite / Hybrid
- **Core Deliverables**:
  - Annotated architecture diagrams
  - Threat model outputs
  - Security checklist findings
  - Executive summary with roadmap

### 2. Why This Matters
- Proactively identifies architectural risks before deployment or exploitation
- Embeds Zero Trust concepts: identity-centric, segmented, and resilient
- Aligns with broader compliance goals without becoming a full audit

### 3. Prerequisites
- **Commercial**: SOW signed, named security sponsor, success criteria agreed
- **Technical**: Architecture diagrams, data flow maps, identity & access documentation, network topology, logging/monitoring overview
- **People**: Security architect, solution architect, operations lead, optional compliance SME

### 4. Roles & RACI
- **Lead Security Architect** — accountable for delivery quality
- **Threat Modeling Analyst** — develops model, reviews flows
- **PM** — manages schedule and cadence
- **Client POC** — provides artifacts and coordinates SMEs
- **Escalation** — CISO / Security Practice Lead

### 5. Timeline & Cadence
| Phase  | Focus |
|--------|-------|
| Week 1 | Kickoff, gather artifacts, architecture walkthrough |
| Week 2 | Threat modeling, checklist assessment, findings consolidation |
| Final  | Deliver report, stakeholder review, agree remediation actions |

**Standups:** Daily  
**Check-ins:** Midpoint and final presentation

### 6. Tooling & References
- Threat modeling tools (e.g., MS Threat Modeling Tool)
- NIST CSF / SP 800-53
- Zero Trust architecture guides (Microsoft, CISA)
- SAR checklist (tailored to security domains)

### 7. Delivery Steps
1. **Kickoff** — Confirm scope, outcomes, access needs
2. **Architecture Review** — Diagram walkthrough, annotate control gaps
3. **Threat Modeling** — Identify threats and attack vectors
4. **Checklist Assessment** — Review controls in focus areas
5. **Reporting** — Consolidate findings, create prioritised roadmap
6. **Handover** — Present to client, assign actions, propose follow-up

### 8. Quality Bar & Exit Criteria
- Architecture reviewed and annotated
- Threat model validated with SMEs
- Checklist assessment complete with no unresolved critical items
- Roadmap agreed and documented

### 9. Evidence to Capture
- Annotated diagrams
- Threat model artifacts
- Completed checklist
- Decision logs and stakeholder sign-off

### 10. Risks & Mitigations
- **Missing artifacts** — escalate early, run discovery interviews
- **Scope creep into compliance** — clarify ISO/IRAP out of scope
- **Stakeholder unavailability** — schedule reviews at kickoff

### 11. Metrics & Reporting
- Number of threats identified
- Severity breakdown of findings
- Percentage of architecture components reviewed
- Remediation commitment rate

### 12. Escalation Path
- Complex identity/cloud issues → Cloud Security Lead
- Compliance questions → Compliance SME
- Major redesign → Enterprise Architect

### 13. Communication Templates
**Kickoff Email**  
Subject: Security Architecture Review — Kickoff & Access Requirements

**Midpoint Update**  
- Completed: [Discovery / Threat Modeling]
- Next: [Checklist Assessment / Findings Consolidation]
- Risks & Decisions Needed: [List]

**Closeout Email**  
- Summary of findings
- Deliverables list
- Agreed next steps

### 14. Deliverables to Client
- Executive summary sli
