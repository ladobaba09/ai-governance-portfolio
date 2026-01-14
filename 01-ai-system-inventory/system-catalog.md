# AI System Inventory

**Organization:** Lone Star Healthcare Analytics (LSHA)  
**Last Updated:** January 13, 2026  
**Total Systems:** 6

---

## High-Risk Systems

### UC-3: TalentMatch - Employment Screening

| Attribute | Details |
|-----------|---------|
| **Purpose** | AI-powered resume screening and candidate ranking |
| **Risk Level** | High |
| **Framework** | EU AI Act |
| **Owner** | HR Department |
| **Vendor** | HireRight AI |
| **Status** | Production |
| **Deployment Date** | June 14, 2024 |
| **Affected Population** | ~2,500 applicants annually |

**Description:**  
NLP-based system that analyzes resumes and application materials to score and rank candidates against job requirements. Provides hiring managers with a shortlist of recommended candidates.

**Decision Type:** Semi-autonomous. Human review required before rejecting any candidate.

**Data Inputs:** Resumes, cover letters, application questionnaire responses, job descriptions

**TRAIGA Considerations:**
- Employment decisions = high scrutiny under Section 551.054
- Requires documented non-discriminatory intent
- Proxy variable analysis mandatory
- Vendor attestation needed

---

### UC-4: ClinAssist - Clinical Decision Support

| Attribute | Details |
|-----------|---------|
| **Purpose** | Diagnostic suggestions and treatment recommendations |
| **Risk Level** | High |
| **Framework** | EU AI Act |
| **Owner** | Clinical Operations |
| **Vendor** | DiagnosticAI Inc. |
| **Status** | Production |
| **Deployment Date** | January 9, 2025 |
| **Affected Population** | ~30,000 patient encounters annually |

**Description:**  
Clinical decision support system that analyzes patient data to provide diagnostic suggestions and treatment recommendations to healthcare providers.

**Decision Type:** Advisory only. Providers make all final clinical decisions.

**Data Inputs:** Patient symptoms, medical history, lab results, imaging data

**TRAIGA Considerations:**
- Healthcare decisions affecting individuals
- SB 1188 disclosure requirements
- Bias testing across demographic groups critical
- FDA regulatory considerations for vendor

---

## Limited-Risk Systems

### UC-5: ClaimSense - Claims Processing

| Attribute | Details |
|-----------|---------|
| **Purpose** | Automated claims review and processing |
| **Risk Level** | Limited |
| **Framework** | EU AI Act |
| **Owner** | Revenue Cycle |
| **Vendor** | MedClaim AI |
| **Status** | Production |
| **Deployment Date** | August 19, 2024 |
| **Affected Population** | ~120,000 claims annually |

**Description:**  
NLP system that automates initial claims review, extracts key information, and routes claims for processing. Auto-approves high-confidence claims; flags others for human review.

**Decision Type:** Semi-autonomous. Auto-approves >95% confidence scores; human review on all denials.

**Data Inputs:** Claims documents, medical records, procedure codes, payer rules

**TRAIGA Considerations:**
- Financial impact on patients/providers
- Denial pattern monitoring required
- Vendor PHI handling under BAA

---

### UC-7: VoiceBot TX - Customer Service Chatbot

| Attribute | Details |
|-----------|---------|
| **Purpose** | Customer service inquiries and appointment scheduling |
| **Risk Level** | Limited |
| **Framework** | NIST AI RMF |
| **Owner** | Customer Success |
| **Vendor** | Google DialogFlow |
| **Status** | Production |
| **Deployment Date** | October 31, 2024 |
| **Affected Population** | ~80,000 interactions annually |

**Description:**  
Conversational AI handling initial customer service inquiries via phone and web chat. Handles appointment scheduling, account questions, and general information requests.

**Decision Type:** Autonomous for routine inquiries; escalates complex issues to human agents.

**Data Inputs:** Customer voice/text input, account information, appointment availability

**TRAIGA Considerations:**
- Emotion/frustration detection feature requires legal review
- Section 551.056 emotion recognition provisions may apply
- Escalation procedures must be robust

---

## Minimal-Risk Systems

### UC-6: PatientFlow Pro - Scheduling Optimization

| Attribute | Details |
|-----------|---------|
| **Purpose** | Appointment scheduling optimization |
| **Risk Level** | Minimal |
| **Framework** | NIST AI RMF |
| **Owner** | Operations |
| **Vendor** | Internal Development |
| **Status** | Production |
| **Deployment Date** | March 14, 2023 |
| **Affected Population** | ~45,000 patients annually |

**Description:**  
ML system that predicts appointment no-show probability and recommends overbooking factors to optimize clinic scheduling and reduce gaps.

**Decision Type:** Advisory only. Scheduling staff make final decisions.

**Data Inputs:** Historical appointment data, patient demographics, appointment type, weather, day of week

**TRAIGA Considerations:**
- Lower risk but monitor for socioeconomic proxies
- Zip code as input may correlate with protected characteristics
- Access equity monitoring recommended

---

### UC-8: FraudShield - Fraud Detection

| Attribute | Details |
|-----------|---------|
| **Purpose** | Anomaly detection for fraud prevention |
| **Risk Level** | Minimal |
| **Framework** | NIST AI RMF |
| **Owner** | Compliance |
| **Vendor** | Internal Development |
| **Status** | Production |
| **Deployment Date** | April 9, 2023 |
| **Affected Population** | ~500 provider relationships |

**Description:**  
Anomaly detection system that identifies potentially fraudulent claims patterns and billing irregularities, flagging them for compliance team investigation.

**Decision Type:** Advisory only. Compliance team investigates all flags; no automated actions.

**Data Inputs:** Claims data, billing patterns, provider information, historical fraud cases

**TRAIGA Considerations:**
- Lower direct patient impact
- False positive management important for provider relationships
- Model drift monitoring needed

---

## Risk Distribution Summary

| Risk Level | Count | Systems |
|------------|-------|---------|
| High | 2 | TalentMatch, ClinAssist |
| Limited | 2 | ClaimSense, VoiceBot TX |
| Minimal | 2 | PatientFlow Pro, FraudShield |

---

## Inventory Maintenance

- **Review Frequency:** Quarterly
- **Next Review:** April 2026
- **Owner:** AI Governance Lead
- **New System Process:** All AI deployments require inventory entry before production
