# Engage Squared Security Deliveries

This repository houses delivery playbooks and learning modules to standardise high-quality security engagements. Each module is designed as a self-contained facilitator guide with business-aligned content, reference material, and templates.

---

## When to Use Each Module

| Module | Purpose | Best Used For |
|--------|---------|----------------|
| **[Security Foundations](./Security%20Foundations.md)** | Introduces foundational security concepts like the CIA Triad (Confidentiality, Integrity, Availability) in plain business terms. | Security awareness sessions, executive briefings, and early-stage discussions. |
| **[Essential Eight](./Essential%20Eight.md)** | Assesses maturity against the Australian Essential 8 model; includes plain-language explanations, discussion prompts, scoring tables, and uplift roadmaps. | Australian organisations establishing a baseline or planning a practical security uplift. |
| **[Security Architecture Review](./Security%20Architecture%20Review.md)** | A high-level architecture review using Essential 8 as an anchor, with optional alignment to NIST and Zero Trust. Includes facilitator guidance, threat modeling workflows, and a strategic roadmap. | When evaluating or validating a solution’s security posture, especially cloud or M365-heavy environments. |
| **[Security Roadmap Workshop](./Security%20Roadmap%20Workshop.md)** | Aligns strategy, stakeholders, and next steps following initial security engagements. Produces a Crawl–Walk–Run roadmap with executive alignment. | When an organisation requires an actionable security roadmap for funding, prioritisation, or project planning. |
| **[Sensitivity Labelling Uplift](./Sensitivity%20Labelling%20Uplift.md)** | Improves visibility and control of sensitive data through Microsoft Purview Sensitivity Labels. Focuses on discovery, taxonomy design, governance, and adoption. | Organisations looking to strengthen data protection, meet compliance requirements, or reduce oversharing risks. |
| **[Basic Data Loss Prevention (DLP) Advisory](./Basic%20Data%20Loss%20Prevention%20(DLP)%20Advisory)** | Introduces foundational Data Loss Prevention controls in Microsoft 365. Establishes baseline policies for sensitive information. | Organisations at the start of their DLP journey, requiring visibility into sensitive data risks and quick protection wins. |

--- 
## Suggested Delivery Flow 

The modules follow an escalation path.  
Start with **Security Foundations**, progress through **Architecture Review** and **Roadmap**, then branch into more specialised modules.  

Security Foundations 
        ↓
Security Architecture Review 
        ↓
Security Roadmap Workshop 
        ↓
   ┌───────────────┬─────────────────┐
   ↓               ↓                 ↓
Sensitivity   Basic DLP         (future modules:
Labelling     Advisory          Defender, IRM, etc.)
Uplift

---

## Supporting Resources

| Resource | Purpose | Best Used For |
|----------|---------|----------------|
| **[Essential 8 Maturity Score Table](./Essential%208%20Maturity%20Score%20Table.md)** | Provides a standardised template for capturing current vs. target maturity (Level 0–3) for each Essential 8 strategy. Includes space for risks and recommended actions. | Used during workshops or customer sessions to capture results in a structured way. |
| **[Essential 8 in Plain Language](./Essential_Eight_PlainLanguage.md)** | Explains each Essential 8 strategy in simple business language with examples. | Handout or pre-reading for customers and executives who need to understand the “why” without technical jargon. |

---

##  Learning Resources & References

Each module features best-practice frameworks and contextual links to deepen understanding or share with clients:

- [Microsoft 365 & Essential Eight Overview](https://learn.microsoft.com/en-us/compliance/anz/e8-overview)  
- [ACSC Essential 8 Maturity Model](https://www.cyber.gov.au/resources-business-and-government/essential-cybersecurity/essential-eight/essential-eight-maturity-model)  
- [CSO Online: The CIA Triad](https://www.csoonline.com/article/568917/the-cia-triad-definition-components-and-examples.html)  
- [Microsoft Cybersecurity Reference Architecture (MCRA)](https://learn.microsoft.com/en-us/security/adoption/mcra)  
- [Microsoft Security Adoption](https://learn.microsoft.com/en-us/security/adoption/adoption)

---

##  Getting Started

1. **Choose a module** that fits your engagement stage.
2. **Review the facilitator guide** and ensure you understand the purpose and flow.
3. **Capture outputs** using provided templates like maturity score tables or mind maps.
4. **Leverage linked references** to support further learning or client handoff.

---

##  Contribution & Usage Guidelines

- Keep content clear, business-appropriate, and facilitation-friendly.
- Use clients’ terminology where possible — this is not a developer repo.
- No deep technical prescriptive recommendations; guide frameworks, not configurations.
- Maintain all references — reviewers should easily follow public documentation if needed.
