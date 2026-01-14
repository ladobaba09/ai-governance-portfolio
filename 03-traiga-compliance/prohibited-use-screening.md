# TRAIGA Prohibited Use Screening

**Organization:** Lone Star Healthcare Analytics  
**Screening Date:** January 13, 2026  
**Regulation:** Texas Responsible Artificial Intelligence Governance Act (TRAIGA)  
**Effective Date:** January 1, 2026

---

## Overview

This document screens all LSHA AI systems against TRAIGA prohibited uses (Sections 551.051-551.057) to identify any systems requiring modification or discontinuation.

## Prohibited Uses Under TRAIGA

### For All Entities (Section 551.051-551.054)

1. **Intentional Discrimination:** AI designed or deployed with intent to discriminate against protected classes
2. **Behavioral Manipulation:** AI that incites self-harm, violence, or criminal activity
3. **Constitutional Violations:** AI that violates constitutionally protected rights
4. **Non-Consensual Imagery:** AI generating intimate imagery without consent or CSAM

### Government-Specific (Section 551.055-551.056)

5. **Social Scoring:** Assigning scores to individuals based on behavior patterns
6. **Biometric ID Without Consent:** Biometric identification in public spaces without consent

### Emotion Recognition (Section 551.056)

7. **Emotion Recognition Restrictions:** Limitations on emotion inference in certain contexts

---

## System-by-System Screening

### TalentMatch - Employment Screening

| Prohibited Use | Applicable? | Analysis | Status |
|----------------|-------------|----------|--------|
| Intentional discrimination | Review Required | System designed for hiring efficiency, not discrimination. Intent documentation needed to prove non-discriminatory purpose. | ⚠️ Documentation Gap |
| Behavioral manipulation | No | Not applicable—hiring context only | ✅ Clear |
| Constitutional violations | No | No constitutional rights implicated in employment screening | ✅ Clear |
| Non-consensual imagery | No | No image generation capability | ✅ Clear |
| Social scoring | No | Not government entity; not scoring behavior | ✅ Clear |
| Biometric ID | No | No biometric processing | ✅ Clear |
| Emotion recognition | No | No emotion inference | ✅ Clear |

**Overall Status:** ⚠️ CONDITIONAL PASS - Requires intent documentation

**Required Actions:**
- [ ] Complete Business Justification Memo
- [ ] Document non-discriminatory design intent
- [ ] Establish adverse impact monitoring

---

### ClinAssist - Clinical Decision Support

| Prohibited Use | Applicable? | Analysis | Status |
|----------------|-------------|----------|--------|
| Intentional discrimination | Review Required | System designed to improve diagnosis, not discriminate. Must document non-discriminatory purpose. | ⚠️ Documentation Gap |
| Behavioral manipulation | No | Clinical advisory only | ✅ Clear |
| Constitutional violations | No | Healthcare decisions don't implicate constitutional rights in this context | ✅ Clear |
| Non-consensual imagery | No | No image generation | ✅ Clear |
| Social scoring | No | Not government; clinical decisions ≠ social scoring | ✅ Clear |
| Biometric ID | No | No biometric identification | ✅ Clear |
| Emotion recognition | No | No emotion inference | ✅ Clear |

**Overall Status:** ⚠️ CONDITIONAL PASS - Requires intent documentation

**Required Actions:**
- [ ] Document clinical improvement purpose
- [ ] Establish demographic outcome monitoring
- [ ] Ensure SB 1188 disclosure compliance

---

### ClaimSense - Claims Processing

| Prohibited Use | Applicable? | Analysis | Status |
|----------------|-------------|----------|--------|
| Intentional discrimination | Review Required | System designed for processing efficiency. Denial patterns require monitoring. | ⚠️ Monitoring Required |
| Behavioral manipulation | No | Claims processing only | ✅ Clear |
| Constitutional violations | No | No constitutional rights in claims processing | ✅ Clear |
| Non-consensual imagery | No | No image generation | ✅ Clear |
| Social scoring | No | Not scoring behavior | ✅ Clear |
| Biometric ID | No | No biometric processing | ✅ Clear |
| Emotion recognition | No | No emotion inference | ✅ Clear |

**Overall Status:** ⚠️ CONDITIONAL PASS - Requires outcome monitoring

**Required Actions:**
- [ ] Analyze denial patterns by demographics
- [ ] Document business justification for auto-denial thresholds
- [ ] Establish appeals tracking

---

### PatientFlow Pro - Scheduling Optimization

| Prohibited Use | Applicable? | Analysis | Status |
|----------------|-------------|----------|--------|
| Intentional discrimination | Low Risk | Advisory system for scheduling efficiency. Lower consequential impact. | ✅ Clear |
| Behavioral manipulation | No | Scheduling only | ✅ Clear |
| Constitutional violations | No | No constitutional implications | ✅ Clear |
| Non-consensual imagery | No | No image generation | ✅ Clear |
| Social scoring | No | Not behavior scoring | ✅ Clear |
| Biometric ID | No | No biometric processing | ✅ Clear |
| Emotion recognition | No | No emotion inference | ✅ Clear |

**Overall Status:** ✅ PASS

**Recommended Actions:**
- [ ] Monitor for access equity issues (optional)

---

### VoiceBot TX - Customer Service Chatbot

| Prohibited Use | Applicable? | Analysis | Status |
|----------------|-------------|----------|--------|
| Intentional discrimination | No | No consequential decisions | ✅ Clear |
| Behavioral manipulation | No | Customer service only | ✅ Clear |
| Constitutional violations | No | No constitutional implications | ✅ Clear |
| Non-consensual imagery | No | No image generation | ✅ Clear |
| Social scoring | No | Not behavior scoring | ✅ Clear |
| Biometric ID | No | No biometric identification | ✅ Clear |
| Emotion recognition | ⚠️ Review | Frustration detection feature may fall under Section 551.056 | ⚠️ Legal Review Needed |

**Overall Status:** ⚠️ CONDITIONAL PASS - Emotion recognition review required

**Required Actions:**
- [ ] Legal review of frustration detection feature
- [ ] Document that detection improves service, doesn't cause adverse treatment
- [ ] Monitor Texas AI Council guidance on emotion recognition scope

---

### FraudShield - Fraud Detection

| Prohibited Use | Applicable? | Analysis | Status |
|----------------|-------------|----------|--------|
| Intentional discrimination | Low Risk | Internal fraud detection; advisory only; compliance team investigates all flags | ✅ Clear |
| Behavioral manipulation | No | Fraud detection only | ✅ Clear |
| Constitutional violations | No | No constitutional implications | ✅ Clear |
| Non-consensual imagery | No | No image generation | ✅ Clear |
| Social scoring | No | Fraud patterns ≠ social scoring | ✅ Clear |
| Biometric ID | No | No biometric processing | ✅ Clear |
| Emotion recognition | No | No emotion inference | ✅ Clear |

**Overall Status:** ✅ PASS

---

## Summary

| System | Status | Priority Actions |
|--------|--------|------------------|
| TalentMatch | ⚠️ Conditional | Intent documentation required |
| ClinAssist | ⚠️ Conditional | Intent documentation required |
| ClaimSense | ⚠️ Conditional | Outcome monitoring required |
| PatientFlow Pro | ✅ Pass | None required |
| VoiceBot TX | ⚠️ Conditional | Emotion recognition legal review |
| FraudShield | ✅ Pass | None required |

## Conclusion

No LSHA AI systems currently violate TRAIGA prohibited uses. However, three high/limited-risk systems require enhanced documentation to establish non-discriminatory intent, and one system requires legal review of a feature that may fall under emotion recognition provisions.

**Recommended Immediate Actions:**
1. Prioritize intent documentation for TalentMatch (highest risk)
2. Initiate legal review of VoiceBot TX frustration detection
3. Establish outcome monitoring for ClaimSense
4. Document clinical purpose for ClinAssist

---

*Screening completed by AI Governance Lead, January 13, 2026*
