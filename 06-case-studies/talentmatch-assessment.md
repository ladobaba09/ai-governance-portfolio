# Case Study: TalentMatch Employment Screening AI

## TRAIGA Compliance Assessment

**System:** TalentMatch - Employment Screening  
**Assessment Date:** January 13, 2026  
**Assessor:** AI Governance Lead  
**Risk Level:** High  
**Regulatory Framework:** TRAIGA, EU AI Act

---

## Executive Summary

TalentMatch is an AI-powered resume screening system used by Lone Star Healthcare Analytics (LSHA) to evaluate job applicants. As a high-risk employment AI system, TalentMatch requires comprehensive TRAIGA compliance assessment, particularly around intent-based discrimination provisions.

This assessment identified three critical compliance gaps and recommends immediate remediation actions to establish safe harbor protections before regulatory scrutiny.

**Bottom Line:** TalentMatch can continue operating with enhanced documentation and monitoring, but requires immediate action on vendor attestation and intent documentation.

---

## System Overview

### Purpose and Functionality

TalentMatch analyzes resumes and application materials using natural language processing to:
- Extract skills, experience, and qualifications
- Score candidates against job requirements
- Rank applicants for hiring manager review
- Flag potential matches and concerns

### Decision Impact

| Metric | Value |
|--------|-------|
| Annual applicants processed | ~2,500 |
| Roles screened | All non-executive positions |
| Decision type | Semi-autonomous (AI ranks, human decides) |
| Rejection authority | AI can deprioritize; human confirms rejections |

### Data Inputs

- Resumes (PDF, Word, text)
- Cover letters
- Application questionnaire responses
- Job descriptions and requirements

### Vendor Information

| Attribute | Value |
|-----------|-------|
| Vendor | HireRight AI |
| Contract date | June 2024 |
| Deployment date | June 14, 2024 |
| Contract renewal | June 2025 |

---

## TRAIGA Compliance Analysis

### Applicable Provisions

**Section 551.054 - Prohibited Discriminatory Uses:**
TalentMatch falls under heightened scrutiny as an employment decision system. TRAIGA prohibits AI used "with intent to discriminate" against protected classes.

**Key Distinction:** TRAIGA uses intent-based liability, not pure disparate impact. Unintentional disparate impact alone does not establish violation—intent must be shown.

**Section 551.101 - Safe Harbor:**
Substantial compliance with NIST AI RMF provides affirmative defense against enforcement.

**Section 551.102 - Cure Period:**
60-day cure period available after AG notice for good-faith remediation.

### Prohibited Use Screening

| Prohibited Use | Applicable? | Assessment |
|----------------|-------------|------------|
| Discrimination with intent | ⚠️ Requires documentation | System designed for efficiency, not discrimination—but documentation insufficient |
| Behavioral manipulation | ✅ No | Not applicable to hiring context |
| Constitutional violations | ✅ No | No constitutional rights implicated |
| Non-consensual imagery | ✅ No | No image generation capability |

### Gap Analysis

#### GAP 1: Intent Documentation (Critical)

**Finding:** No formal documentation exists proving TalentMatch was designed and deployed without discriminatory intent.

**Risk:** Without affirmative documentation of non-discriminatory intent, LSHA lacks evidence for TRAIGA's intent-based defense. If disparate impact is discovered, proving lack of intent becomes difficult.

**Current State:**
- No business justification memo
- No design intent documentation
- No record of feature selection rationale

**Required State:**
- Written business justification establishing legitimate hiring efficiency purpose
- Design documentation showing non-discriminatory objectives
- Feature selection rationale with business necessity analysis

**Remediation:**
1. Draft Business Justification Memo (Target: January 20, 2026)
2. Interview original stakeholders to document design decisions
3. Create Intent Attestation for executive signature
4. Preserve all historical documentation

---

#### GAP 2: Proxy Variable Analysis (Critical)

**Finding:** Input features may correlate with protected characteristics, creating disparate impact risk.

**Identified Proxy Variables:**

| Input Feature | Potential Proxy For | Risk Level |
|---------------|---------------------|------------|
| Applicant name | Race, national origin, gender | High |
| Zip code | Race, socioeconomic status | High |
| Graduation year | Age | Medium |
| University name | Race, socioeconomic status | Medium |

**Current State:**
- No proxy variable analysis performed
- No feature importance assessment
- No demographic impact monitoring

**Required State:**
- Completed proxy variable audit
- Feature modification or removal where appropriate
- Ongoing adverse impact monitoring

**Remediation:**
1. Engage I/O psychologist for proxy variable audit (Target: January 31, 2026)
2. Implement name anonymization before AI scoring
3. Evaluate zip code removal or binning
4. Establish quarterly adverse impact analysis using 4/5ths rule

---

#### GAP 3: Vendor Compliance (High)

**Finding:** HireRight AI has not provided TRAIGA compliance attestation or bias testing documentation.

**Current State:**
- Standard SaaS contract without AI-specific terms
- No TRAIGA representations or warranties
- No bias testing results provided
- No audit rights for AI system

**Required State:**
- Vendor TRAIGA compliance attestation
- Bias testing methodology and results
- Contract amendment with AI-specific terms
- Audit rights established

**Remediation:**
1. Send TRAIGA compliance questionnaire to HireRight AI (Target: January 15, 2026)
2. Request bias testing documentation
3. Negotiate contract amendment with TRAIGA terms
4. Establish annual attestation requirement

---

## Risk Assessment

### Risk Matrix

| Risk | Likelihood | Severity | Score | Priority |
|------|------------|----------|-------|----------|
| Proxy discrimination | Medium (3) | High (4) | 12 | Critical |
| Vendor compliance gap | Medium (3) | High (4) | 12 | Critical |
| Intent documentation gap | High (4) | Medium (3) | 12 | Critical |
| Adverse impact discovery | Medium (3) | Medium (3) | 9 | High |

### Compliance Risk Assessment

**Overall TRAIGA Compliance Status:** ⚠️ PARTIAL

| Requirement | Status | Gap |
|-------------|--------|-----|
| No discriminatory intent | ⚠️ Undocumented | Documentation needed |
| No prohibited uses | ✅ Compliant | None |
| NIST AI RMF alignment | ⚠️ Partial | Framework adoption in progress |
| Vendor compliance | ⚠️ Pending | Attestation needed |

---

## Remediation Plan

### Immediate Actions (By January 20, 2026)

| Action | Owner | Due Date | Status |
|--------|-------|----------|--------|
| Draft Business Justification Memo | AI Governance Lead | Jan 20 | In Progress |
| Send vendor compliance questionnaire | Procurement | Jan 15 | Not Started |
| Implement name anonymization | IT | Jan 20 | Not Started |
| Brief executive team | AI Governance Lead | Jan 17 | Scheduled |

### Short-Term Actions (By January 31, 2026)

| Action | Owner | Due Date | Status |
|--------|-------|----------|--------|
| Complete proxy variable audit | HR Director + I/O Psych | Jan 31 | Not Started |
| Negotiate vendor contract amendment | Legal + Procurement | Jan 31 | Not Started |
| Establish adverse impact baseline | HR Analytics | Jan 31 | Not Started |
| Document feature selection rationale | AI Governance Lead | Jan 31 | Not Started |

### Ongoing Actions

| Action | Owner | Frequency |
|--------|-------|-----------|
| Adverse impact analysis | HR Analytics | Quarterly |
| Vendor compliance attestation | Procurement | Annual |
| System audit | AI Governance | Annual |
| Intent documentation review | Legal | Annual |

---

## Safe Harbor Strategy

### NIST AI RMF Alignment

To establish affirmative defense under TRAIGA Section 551.101:

| NIST Function | TalentMatch Actions |
|---------------|---------------------|
| GOVERN | Establish AI governance oversight for hiring AI |
| MAP | Document system context, stakeholders, risks |
| MEASURE | Implement bias metrics, adverse impact tracking |
| MANAGE | Create response procedures for identified issues |

### Documentation Package

Maintain documentation package for potential AG inquiry:
1. Business Justification Memo
2. Design Intent Attestation (executive-signed)
3. Proxy Variable Audit Report
4. Adverse Impact Analysis (quarterly)
5. Vendor Compliance Attestation
6. Testing and Validation Records
7. Incident Response Records

---

## Recommendations

### Continue Operation: YES, with conditions

TalentMatch may continue operating provided:
1. Business Justification Memo completed by January 20, 2026
2. Name anonymization implemented by January 20, 2026
3. Vendor compliance questionnaire sent by January 15, 2026
4. Proxy variable audit initiated by January 31, 2026

### Escalation Triggers

Pause system operation if:
- Vendor refuses to provide compliance attestation
- Proxy audit reveals severe disparate impact (>20% deviation)
- Discrimination complaint received
- AG inquiry initiated

### Success Metrics

| Metric | Target | Measurement |
|--------|--------|-------------|
| Intent documentation complete | 100% | By Jan 20, 2026 |
| Vendor attestation received | Yes | By Jan 31, 2026 |
| Adverse impact within 4/5ths | Yes | Quarterly analysis |
| NIST AI RMF alignment score | >70% | By March 31, 2026 |

---

## Conclusion

TalentMatch presents manageable TRAIGA compliance risk with prompt remediation. The primary gaps are documentation-related rather than fundamental system issues. By implementing the recommended actions, LSHA can establish a strong safe harbor position and demonstrate good-faith compliance.

The intent-based liability framework under TRAIGA actually provides flexibility—our documentation strategy focuses on affirmatively proving non-discriminatory intent rather than eliminating all disparate impact (which may be impossible for any hiring tool).

**Next Review:** April 2026 (post-remediation assessment)

---

*Assessment completed by AI Governance Lead, January 13, 2026*
