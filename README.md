# AI Governance Portfolio

**Demonstrating practical AI risk management and regulatory compliance skills**

---

## About This Portfolio

This portfolio documents hands-on AI governance work using industry-standard frameworks and tools. All examples use a fictional healthcare analytics company (Lone Star Healthcare Analytics) to demonstrate real-world compliance scenarios.

### Skills Demonstrated
- AI system inventory and risk classification
- Regulatory compliance (TRAIGA, EU AI Act, NIST AI RMF)
- Risk assessment and mitigation planning
- Policy development and lifecycle management
- Vendor AI due diligence
- GRC platform experience (VerifyWise)

---

## Portfolio Contents

### 1. AI System Inventory
Complete documentation of 6 AI systems with risk classifications:

| System | Purpose | Risk Level | Key Compliance Considerations |
|--------|---------|------------|------------------------------|
| TalentMatch | Employment screening | High | TRAIGA intent documentation, proxy variable analysis |
| ClinAssist | Clinical decision support | High | Patient safety, SB 1188 disclosure requirements |
| ClaimSense | Claims processing | Limited | Denial bias monitoring, vendor data handling |
| PatientFlow Pro | Scheduling optimization | Minimal | Socioeconomic proxy considerations |
| VoiceBot TX | Customer service chatbot | Limited | Emotion recognition regulatory scope |
| FraudShield | Fraud detection | Minimal | False positive impact, model drift |

📁 See: [`/01-ai-system-inventory/`](./01-ai-system-inventory/)

### 2. Risk Assessments
14 documented risks across all systems with:
- Risk categorization (Bias, Compliance, Vendor, Operational)
- Likelihood and severity scoring
- Specific mitigation strategies
- Assigned owners and target dates

📁 See: [`/02-risk-assessments/`](./02-risk-assessments/)

### 3. TRAIGA Compliance Analysis
Texas Responsible AI Governance Act (effective Jan 1, 2026) analysis including:
- Prohibited use screening for all systems
- Intent-based liability documentation approach
- Safe harbor alignment with NIST AI RMF
- 60-day cure period procedures

📁 See: [`/03-traiga-compliance/`](./03-traiga-compliance/)

### 4. Policies
Three governance policies developed for TRAIGA compliance:

| Policy | Purpose |
|--------|---------|
| AI Acceptable Use Policy | Establishes prohibited uses and documentation requirements |
| AI Vendor Due Diligence Policy | Pre-procurement and ongoing vendor assessment |
| AI Incident Response Policy | Response procedures including AG inquiry handling |

📁 See: [`/04-policies/`](./04-policies/)

### 5. VerifyWise Implementation
Screenshots and documentation from hands-on GRC platform implementation:
- Dashboard configuration
- Use case documentation
- Risk register management
- Vendor tracking

📁 See: [`/05-verifywise-screenshots/`](./05-verifywise-screenshots/)

---

## Case Study: TalentMatch Employment Screening

**The Challenge:** Assess a high-risk AI hiring tool for TRAIGA compliance before the January 1, 2026 effective date.

**Key Risks Identified:**
1. **Proxy Variable Discrimination** - Input features (zip code, graduation year) may correlate with protected characteristics
2. **Vendor Compliance Gap** - No TRAIGA attestation from vendor
3. **Documentation Deficiency** - Missing intent documentation for safe harbor defense

**Mitigation Approach:**
- Engaged I/O psychologist for proxy variable audit
- Implemented name/address anonymization in screening process
- Established quarterly adverse impact analysis
- Drafted Business Justification Memo documenting legitimate, non-discriminatory purpose
- Amended vendor contract with TRAIGA representations and audit rights

**Outcome:** System approved for continued use with enhanced monitoring and documentation controls.

📁 Full case study: [`/06-case-studies/talentmatch-assessment.md`](./06-case-studies/talentmatch-assessment.md)

---

## Frameworks & Standards

This portfolio demonstrates alignment with:

| Framework | Application |
|-----------|-------------|
| **NIST AI RMF** | Risk assessment methodology, safe harbor documentation |
| **EU AI Act** | Risk classification, high-risk system requirements |
| **TRAIGA** | Texas-specific compliance, intent-based liability |
| **ISO 42001** | AI management system principles |

---

## Tools & Platforms

- **VerifyWise** - Open-source AI governance platform
- **Risk Assessment** - Likelihood × Impact scoring methodology
- **Policy Management** - Lifecycle from draft to annual review

---

## About Me

Ladi Lemboye | AI Governance Professional

I'm building expertise in AI risk management and regulatory compliance. This portfolio represents hands-on work with real governance frameworks and tools, prepared using fictional scenarios to demonstrate practical skills.

**Currently seeking:** AI Governance Analyst, AI Risk Analyst, or Responsible AI roles

📧 [Ladi20029@gmail.com]
💼 [https://www.linkedin.com/in/ladi-lemboye-85910b208/]
📍 Texas, USA

---

## Repository Structure

```
ai-governance-portfolio/
├── README.md
├── 01-ai-system-inventory/
│   └── system-catalog.md
├── 02-risk-assessments/
│   ├── risk-register.md
│   └── risk-matrix.md
├── 03-traiga-compliance/
│   ├── prohibited-use-screening.md
│   └── safe-harbor-documentation.md
├── 04-policies/
│   ├── ai-acceptable-use-policy.md
│   ├── ai-vendor-due-diligence-policy.md
│   └── ai-incident-response-policy.md
├── 05-verifywise-screenshots/
│   └── [platform screenshots]
└── 06-case-studies/
    └── talentmatch-assessment.md
```

---

*This portfolio was created for educational and job-seeking purposes. All company names, systems, and scenarios are fictional.*
