# AI Vendor Due Diligence Policy

**Policy ID:** LSHA-AI-002  
**Version:** 1.0  
**Effective Date:** January 1, 2026  
**Owner:** Chief Procurement Officer  
**Review Cycle:** Annual  
**Next Review:** January 1, 2027

---

## 1. Purpose

This policy establishes requirements for evaluating AI vendors before and during engagement to ensure third-party AI systems meet LSHA's compliance obligations under TRAIGA and organizational risk standards.

## 2. Scope

This policy applies to:
- All procurement of AI systems or AI-enabled services from third parties
- Renewal of existing AI vendor contracts
- Material changes to AI vendor relationships
- All departments engaging AI vendors

## 3. Pre-Procurement Assessment

### 3.1 AI Capabilities Questionnaire

Before procurement, vendors must complete an AI assessment questionnaire covering:

**System Information:**
- AI system purpose and functionality
- Decision types (autonomous, advisory, semi-autonomous)
- Affected populations and use contexts
- Data inputs and outputs

**Development Practices:**
- Training data sources and composition
- Bias testing methodology and results
- Fairness metrics used
- Model validation approach

**Compliance Posture:**
- TRAIGA compliance attestation
- Regulatory certifications (FDA, SOC 2, etc.)
- Previous regulatory actions or litigation
- Insurance coverage for AI-related claims

### 3.2 Risk Assessment

Procurement must conduct risk assessment considering:
- AI system risk classification (High/Limited/Minimal)
- Sensitivity of decisions influenced by the system
- Volume of affected individuals
- Data sensitivity (PHI, PII, financial)
- Vendor's compliance track record

### 3.3 Technical Review

For High-Risk AI systems, technical review must include:
- Architecture documentation review
- Security assessment
- Integration requirements
- Performance benchmarks
- Explainability capabilities

## 4. Contract Requirements

### 4.1 Mandatory Contract Terms

All AI vendor contracts must include:

**TRAIGA Compliance Representations:**
```
Vendor represents and warrants that the AI System:
(a) Is not designed with intent to discriminate against protected classes
(b) Does not incite self-harm, violence, or criminal activity
(c) Does not violate constitutionally protected rights
(d) Complies with applicable provisions of the Texas Responsible 
    Artificial Intelligence Governance Act
```

**Documentation Obligations:**
- Vendor will provide and maintain current technical documentation
- Vendor will provide bias testing results upon request
- Vendor will notify LSHA of material changes to AI system

**Audit Rights:**
- LSHA may audit AI system compliance annually
- LSHA may request additional information for regulatory inquiries
- Third-party audit rights for High-Risk systems

**Incident Notification:**
- Vendor will notify LSHA within 48 hours of:
  - Security breaches affecting AI system
  - Discovery of bias or discrimination issues
  - Regulatory inquiries or enforcement actions
  - Material system failures

**Indemnification:**
- Vendor indemnifies LSHA for claims arising from vendor's AI system non-compliance
- Coverage for regulatory penalties, litigation costs, remediation expenses

### 4.2 Data Handling Terms

For vendors processing LSHA data:
- Data residency requirements (US-based)
- Encryption standards (at rest and in transit)
- Data retention and deletion obligations
- Prohibition on use of LSHA data for model training without consent
- Business Associate Agreement (for PHI)

### 4.3 Service Level Agreements

- System availability requirements
- Response time for support requests
- Escalation procedures
- Remediation timelines for identified issues

## 5. Ongoing Monitoring

### 5.1 Annual Compliance Attestation

Vendors must provide annual attestation confirming:
- Continued TRAIGA compliance
- No material changes to previously disclosed information
- No regulatory actions or litigation since last attestation
- Current security certifications

### 5.2 Periodic Review Schedule

| Vendor Risk Level | Review Frequency | Scope |
|-------------------|------------------|-------|
| High-Risk AI | Quarterly | Full compliance review |
| Limited-Risk AI | Semi-annually | Attestation + spot checks |
| Minimal-Risk AI | Annually | Attestation only |

### 5.3 Performance Monitoring

Monitor vendor AI systems for:
- Decision accuracy and consistency
- Bias indicators in outcomes
- System availability and reliability
- User complaints or concerns

### 5.4 Trigger-Based Review

Immediate review required when:
- Vendor reports security incident
- User complaints suggest bias or errors
- Regulatory guidance changes
- Vendor ownership or material business changes

## 6. Vendor Risk Register

### 6.1 Documentation

Maintain vendor risk register including:
- Vendor name and AI system inventory
- Risk classification
- Contract terms summary
- Compliance attestation status
- Last review date and findings
- Open issues and remediation status

### 6.2 Escalation

Escalate to AI Governance Committee when:
- Vendor fails to provide required attestation
- Audit identifies material compliance gaps
- Vendor experiences security breach
- Regulatory action against vendor

## 7. Non-Compliant Vendors

### 7.1 Remediation Process

When vendor compliance issues identified:
1. Document specific non-compliance
2. Notify vendor in writing with remediation requirements
3. Establish remediation timeline (typically 30 days)
4. Verify remediation completion
5. Document resolution

### 7.2 Contract Termination

Consider contract termination when:
- Vendor fails to remediate within agreed timeline
- Vendor provides false attestations
- Vendor's non-compliance creates material LSHA liability
- Vendor refuses to cooperate with audit

### 7.3 Transition Planning

Before terminating AI vendor:
- Identify replacement solution or manual process
- Plan data migration/deletion
- Communicate timeline to affected stakeholders
- Document transition for regulatory purposes

## 8. Roles and Responsibilities

| Role | Responsibility |
|------|----------------|
| Procurement | Lead vendor assessment, contract negotiation |
| AI Governance | Review High-Risk assessments, policy guidance |
| Legal | Contract review, compliance interpretation |
| IT Security | Technical and security assessment |
| Business Owner | Requirements definition, ongoing monitoring |

## 9. Policy Governance

### 9.1 Owner
The Chief Procurement Officer owns this policy.

### 9.2 Exceptions
Exceptions require written approval from CPO and General Counsel.

### 9.3 Review
Annual review or upon material changes to law or vendor landscape.

---

**Approval:**

___________________________ | Date: ___________
Chief Procurement Officer

___________________________ | Date: ___________
General Counsel
