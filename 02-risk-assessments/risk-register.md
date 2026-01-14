# AI Risk Register

**Organization:** Lone Star Healthcare Analytics  
**Last Updated:** January 13, 2026  
**Total Risks:** 14

---

## Risk Scoring Methodology

**Likelihood Scale:**
- Very Low (1): <10% probability
- Low (2): 10-30% probability
- Medium (3): 30-60% probability
- High (4): 60-85% probability
- Very High (5): >85% probability

**Severity Scale:**
- Very Low (1): Negligible impact
- Low (2): Minor impact, easily addressed
- Medium (3): Moderate impact, requires response
- High (4): Significant impact, major response needed
- Very High (5): Critical impact, existential threat

**Risk Score:** Likelihood × Severity

---

## High-Priority Risks (Score ≥ 12)

### RISK-001: Proxy Variable Discrimination
| Attribute | Value |
|-----------|-------|
| **System** | TalentMatch |
| **Category** | Fairness/Bias |
| **Likelihood** | Medium (3) |
| **Severity** | High (4) |
| **Risk Score** | 12 |
| **Status** | Open |
| **Owner** | HR Director |
| **Target Date** | January 31, 2026 |

**Description:**  
Input features including applicant name, zip code, and graduation year may correlate with protected characteristics (race, national origin, age), potentially causing disparate impact even without discriminatory intent.

**Mitigation Plan:**
1. Engage I/O psychologist for proxy variable audit
2. Implement name and address anonymization before AI scoring
3. Establish quarterly adverse impact analysis using 4/5ths rule
4. Document business necessity for all input features

---

### RISK-002: Vendor TRAIGA Compliance Gap
| Attribute | Value |
|-----------|-------|
| **System** | TalentMatch |
| **Category** | Third-Party/Vendor |
| **Likelihood** | Medium (3) |
| **Severity** | High (4) |
| **Risk Score** | 12 |
| **Status** | Open |
| **Owner** | Procurement |
| **Target Date** | January 15, 2026 |

**Description:**  
HireRight AI has not provided attestation regarding TRAIGA prohibited uses or bias testing methodology. Vendor compliance gaps create liability exposure for LSHA as deployer.

**Mitigation Plan:**
1. Send formal TRAIGA compliance questionnaire to vendor
2. Request bias testing documentation and validation data
3. Amend contract with TRAIGA representations and warranties
4. Establish contractual audit rights for AI systems

---

### RISK-003: Diagnostic Bias Across Demographics
| Attribute | Value |
|-----------|-------|
| **System** | ClinAssist |
| **Category** | Fairness/Bias |
| **Likelihood** | Medium (3) |
| **Severity** | High (4) |
| **Risk Score** | 12 |
| **Status** | Open |
| **Owner** | Chief Medical Officer |
| **Target Date** | February 28, 2026 |

**Description:**  
Clinical algorithms may perform differently across demographic groups due to training data representation gaps, potentially leading to diagnostic disparities.

**Mitigation Plan:**
1. Request vendor validation data stratified by demographics
2. Implement internal outcome monitoring by patient demographics
3. Establish clinical review triggers for edge cases
4. Conduct literature review on known algorithmic bias in similar tools

---

## Medium-Priority Risks (Score 6-11)

### RISK-004: Insufficient Intent Documentation
| Attribute | Value |
|-----------|-------|
| **System** | TalentMatch |
| **Category** | Compliance/Documentation |
| **Likelihood** | High (4) |
| **Severity** | Medium (3) |
| **Risk Score** | 12 |
| **Status** | In Progress |
| **Owner** | AI Governance Lead |
| **Target Date** | January 20, 2026 |

**Description:**  
No formal documentation exists proving non-discriminatory design intent, weakening TRAIGA safe harbor defense under the intent-based liability framework.

**Mitigation Plan:**
1. Draft Business Justification Memo documenting legitimate hiring purpose
2. Preserve all design decision records and meeting notes
3. Document feature selection rationale
4. Create intent attestation for executive signature

---

### RISK-005: SB 1188 Disclosure Compliance
| Attribute | Value |
|-----------|-------|
| **System** | ClinAssist |
| **Category** | Regulatory Compliance |
| **Likelihood** | Low (2) |
| **Severity** | High (4) |
| **Risk Score** | 8 |
| **Status** | In Progress |
| **Owner** | Compliance Officer |
| **Target Date** | January 31, 2026 |

**Description:**  
Texas SB 1188 requires patient disclosure when AI is used in treatment decisions. Current disclosure process is informal and inconsistent.

**Mitigation Plan:**
1. Develop standardized patient disclosure language
2. Integrate disclosure into clinical workflow/EHR
3. Train providers on disclosure requirements
4. Audit compliance monthly

---

### RISK-006: Provider Over-Reliance
| Attribute | Value |
|-----------|-------|
| **System** | ClinAssist |
| **Category** | Human Oversight |
| **Likelihood** | Medium (3) |
| **Severity** | Medium (3) |
| **Risk Score** | 9 |
| **Status** | Open |
| **Owner** | Clinical Operations Director |
| **Target Date** | March 15, 2026 |

**Description:**  
Providers may defer excessively to AI recommendations without adequate independent clinical judgment, creating patient safety risks.

**Mitigation Plan:**
1. Implement decision documentation requirements
2. Conduct provider training on AI limitations
3. Audit AI recommendation override rates
4. Establish minimum override rate thresholds

---

### RISK-007: Denial Pattern Bias
| Attribute | Value |
|-----------|-------|
| **System** | ClaimSense |
| **Category** | Fairness/Bias |
| **Likelihood** | Medium (3) |
| **Severity** | Medium (3) |
| **Risk Score** | 9 |
| **Status** | Open |
| **Owner** | Revenue Cycle Director |
| **Target Date** | February 15, 2026 |

**Description:**  
Auto-denial patterns may disproportionately affect certain procedure types or patient populations, creating fairness concerns.

**Mitigation Plan:**
1. Analyze denial rates by procedure type and patient demographics
2. Adjust confidence thresholds based on analysis
3. Enhance human review triggers for edge cases
4. Establish appeals tracking by demographic

---

### RISK-008: Vendor Data Handling
| Attribute | Value |
|-----------|-------|
| **System** | ClaimSense |
| **Category** | Privacy/Security |
| **Likelihood** | Low (2) |
| **Severity** | High (4) |
| **Risk Score** | 8 |
| **Status** | Open |
| **Owner** | Privacy Officer |
| **Target Date** | January 31, 2026 |

**Description:**  
MedClaim AI processes PHI; data handling practices and security controls not fully documented in current agreements.

**Mitigation Plan:**
1. Conduct vendor security assessment
2. Update BAA with AI-specific provisions
3. Verify data residency and encryption standards
4. Establish data retention/deletion requirements

---

### RISK-009: Emotion Recognition Regulatory Scope
| Attribute | Value |
|-----------|-------|
| **System** | VoiceBot TX |
| **Category** | Regulatory Compliance |
| **Likelihood** | Medium (3) |
| **Severity** | Medium (3) |
| **Risk Score** | 9 |
| **Status** | In Progress |
| **Owner** | Legal Counsel |
| **Target Date** | February 15, 2026 |

**Description:**  
Frustration detection feature may fall under TRAIGA Section 551.056 emotion recognition provisions; regulatory scope is unclear.

**Mitigation Plan:**
1. Legal review of TRAIGA emotion recognition provisions
2. Document that feature improves service quality, doesn't cause adverse treatment
3. Monitor Texas AI Council guidance
4. Prepare alternative implementation if required

---

### RISK-010: Escalation Failure
| Attribute | Value |
|-----------|-------|
| **System** | VoiceBot TX |
| **Category** | Operational |
| **Likelihood** | Low (2) |
| **Severity** | Medium (3) |
| **Risk Score** | 6 |
| **Status** | Open |
| **Owner** | Customer Success Manager |
| **Target Date** | February 28, 2026 |

**Description:**  
Complex inquiries may not be properly escalated to human agents, leading to customer harm or complaint escalation.

**Mitigation Plan:**
1. Audit escalation rates and patterns
2. Review and enhance escalation triggers
3. Implement customer satisfaction monitoring
4. Establish escalation SLA metrics

---

## Lower-Priority Risks (Score < 6)

### RISK-011: Socioeconomic Proxy in No-Show Prediction
| Attribute | Value |
|-----------|-------|
| **System** | PatientFlow Pro |
| **Category** | Fairness/Bias |
| **Likelihood** | Medium (3) |
| **Severity** | Low (2) |
| **Risk Score** | 6 |
| **Status** | Open |
| **Owner** | Operations Manager |
| **Target Date** | March 31, 2026 |

---

### RISK-012: Scheduling Access Equity
| Attribute | Value |
|-----------|-------|
| **System** | PatientFlow Pro |
| **Category** | Fairness/Access |
| **Likelihood** | Low (2) |
| **Severity** | Low (2) |
| **Risk Score** | 4 |
| **Status** | Open |
| **Owner** | Operations Manager |
| **Target Date** | April 30, 2026 |

---

### RISK-013: False Positive Provider Impact
| Attribute | Value |
|-----------|-------|
| **System** | FraudShield |
| **Category** | Operational |
| **Likelihood** | Medium (3) |
| **Severity** | Low (2) |
| **Risk Score** | 6 |
| **Status** | Open |
| **Owner** | Compliance Manager |
| **Target Date** | March 31, 2026 |

---

### RISK-014: Model Drift Detection
| Attribute | Value |
|-----------|-------|
| **System** | FraudShield |
| **Category** | Technical/Performance |
| **Likelihood** | Medium (3) |
| **Severity** | Low (2) |
| **Risk Score** | 6 |
| **Status** | Open |
| **Owner** | Data Science Lead |
| **Target Date** | April 30, 2026 |

---

## Risk Summary by Category

| Category | Count | Highest Score |
|----------|-------|---------------|
| Fairness/Bias | 5 | 12 |
| Regulatory Compliance | 2 | 9 |
| Third-Party/Vendor | 2 | 12 |
| Human Oversight | 1 | 9 |
| Privacy/Security | 1 | 8 |
| Operational | 2 | 6 |
| Technical | 1 | 6 |

---

## Risk Register Maintenance

- **Review Frequency:** Monthly
- **Escalation Threshold:** Score ≥ 12 reported to AI Governance Committee
- **Closure Criteria:** Mitigation complete and verified effective
