# AI Risk Matrix

**Organization:** Lone Star Healthcare Analytics  
**Date:** January 13, 2026  
**Total Risks:** 14

---

## Risk Heat Map

```
                              SEVERITY
              │ Very Low │   Low   │  Medium │   High  │Very High│
              │   (1)    │   (2)   │   (3)   │   (4)   │   (5)   │
    ──────────┼──────────┼─────────┼─────────┼─────────┼─────────│
    Very High │          │         │         │         │         │
       (5)    │          │         │         │         │         │
    ──────────┼──────────┼─────────┼─────────┼─────────┼─────────│
L      High   │          │         │   [1]   │         │         │
I      (4)    │          │         │ RISK-004│         │         │
K   ──────────┼──────────┼─────────┼─────────┼─────────┼─────────│
E    Medium   │          │  [4]    │   [3]   │   [3]   │         │
L      (3)    │          │R11,12,  │R06,07,  │R01,02,  │         │
I             │          │  13,14  │   09    │   03    │         │
H   ──────────┼──────────┼─────────┼─────────┼─────────┼─────────│
O      Low    │          │         │  [1]    │   [2]   │         │
O      (2)    │          │         │  R10    │R05,08   │         │
D   ──────────┼──────────┼─────────┼─────────┼─────────┼─────────│
    Very Low  │          │         │         │         │         │
       (1)    │          │         │         │         │         │
    ──────────┴──────────┴─────────┴─────────┴─────────┴─────────│
```

---

## Risk Distribution

### By Risk Score

| Score Range | Risk Level | Count | Risks |
|-------------|------------|-------|-------|
| 16-25 | Very High | 0 | — |
| 12-15 | High | 4 | RISK-001, 002, 003, 004 |
| 8-11 | Medium | 4 | RISK-005, 006, 007, 009 |
| 4-7 | Low | 6 | RISK-008, 010, 011, 012, 013, 014 |
| 1-3 | Very Low | 0 | — |

### By Category

| Category | Count | % of Total |
|----------|-------|------------|
| Fairness/Bias | 5 | 36% |
| Regulatory Compliance | 2 | 14% |
| Third-Party/Vendor | 2 | 14% |
| Human Oversight | 1 | 7% |
| Privacy/Security | 1 | 7% |
| Operational | 2 | 14% |
| Technical | 1 | 7% |

### By System

| System | Risk Level | Count | High-Severity Risks |
|--------|------------|-------|---------------------|
| TalentMatch | High | 3 | Proxy discrimination, Vendor gap, Documentation |
| ClinAssist | High | 3 | Diagnostic bias, SB 1188, Over-reliance |
| ClaimSense | Limited | 2 | Denial bias, Data handling |
| VoiceBot TX | Limited | 2 | Emotion recognition, Escalation |
| PatientFlow Pro | Minimal | 2 | Socioeconomic proxy, Access equity |
| FraudShield | Minimal | 2 | False positives, Model drift |

---

## Priority Actions

### Critical (Score 12+)

| Risk ID | Risk | Score | Due Date | Owner |
|---------|------|-------|----------|-------|
| RISK-001 | Proxy Variable Discrimination | 12 | Jan 31, 2026 | HR Director |
| RISK-002 | Vendor TRAIGA Compliance Gap | 12 | Jan 15, 2026 | Procurement |
| RISK-003 | Diagnostic Bias | 12 | Feb 28, 2026 | CMO |
| RISK-004 | Insufficient Intent Documentation | 12 | Jan 20, 2026 | AI Gov Lead |

### High Priority (Score 8-11)

| Risk ID | Risk | Score | Due Date | Owner |
|---------|------|-------|----------|-------|
| RISK-005 | SB 1188 Disclosure | 8 | Jan 31, 2026 | Compliance |
| RISK-006 | Provider Over-Reliance | 9 | Mar 15, 2026 | Clinical Ops |
| RISK-007 | Denial Pattern Bias | 9 | Feb 15, 2026 | Revenue Cycle |
| RISK-009 | Emotion Recognition Scope | 9 | Feb 15, 2026 | Legal |

---

## Trend Analysis

### Risk Status Over Time

*To be updated monthly*

| Month | Open | In Progress | Mitigated | Closed |
|-------|------|-------------|-----------|--------|
| Jan 2026 | 11 | 3 | 0 | 0 |
| Feb 2026 | — | — | — | — |
| Mar 2026 | — | — | — | — |

### Target State

By Q2 2026:
- All Critical risks mitigated or closed
- No new Critical risks without immediate mitigation plan
- Quarterly risk review cadence established

---

*Risk matrix maintained by AI Governance Lead*
