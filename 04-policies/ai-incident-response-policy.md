# AI Incident Response Policy

**Policy ID:** LSHA-AI-003  
**Version:** 1.0  
**Effective Date:** January 1, 2026  
**Owner:** Chief Information Security Officer  
**Review Cycle:** Annual  
**Next Review:** January 1, 2027

---

## 1. Purpose

This policy establishes procedures for identifying, responding to, and learning from AI-related incidents, including procedures for responding to Texas Attorney General inquiries under TRAIGA.

## 2. Scope

This policy applies to all AI-related incidents affecting LSHA systems, including:
- Internally developed AI systems
- Vendor-provided AI systems
- AI systems in development, testing, or production

## 3. Incident Definition

### 3.1 AI Incident Categories

**Category A - Discrimination/Bias:**
- Complaints alleging AI-based discrimination
- Evidence of disparate impact in AI decisions
- Bias discovered through internal testing

**Category B - System Failure:**
- AI system producing incorrect outputs at scale
- Unexpected system behavior affecting decisions
- Model performance degradation

**Category C - Security/Privacy:**
- Data breach involving AI system or training data
- Unauthorized access to AI models
- Privacy violations related to AI processing

**Category D - Regulatory:**
- Texas AG inquiry or notice of violation
- Other regulatory inquiries regarding AI
- Litigation involving AI decisions

**Category E - Vendor:**
- Vendor-reported incidents affecting LSHA
- Vendor security breaches
- Vendor compliance failures

### 3.2 Incident Severity Levels

| Level | Definition | Response Time |
|-------|------------|---------------|
| Critical | AG enforcement action, active litigation, major breach | Immediate |
| High | Discrimination complaint, system failure affecting decisions | 4 hours |
| Medium | Performance issues, minor bias indicators | 24 hours |
| Low | Documentation gaps, procedural issues | 72 hours |

## 4. Incident Response Team

### 4.1 Core Team

| Role | Responsibility |
|------|----------------|
| Incident Commander | Overall coordination, decision authority |
| AI Governance Lead | Technical assessment, compliance guidance |
| Legal Counsel | Legal strategy, regulatory communication |
| System Owner | System-specific knowledge, remediation |
| Communications | Internal/external messaging |

### 4.2 Escalation Matrix

| Severity | Initial Response | Escalation |
|----------|-----------------|------------|
| Critical | CISO + General Counsel | CEO + Board within 4 hours |
| High | AI Governance Lead | CTO + General Counsel within 24 hours |
| Medium | System Owner | AI Governance Lead within 48 hours |
| Low | System Owner | Monthly governance report |

## 5. Response Procedures

### 5.1 Detection and Reporting

**Internal Detection:**
1. Employee identifies potential incident
2. Report to ai-incidents@lsha.example.com within 4 hours
3. Include: System name, description, affected individuals, evidence

**External Report:**
1. Complaint received from customer, patient, or applicant
2. Customer service escalates to AI Governance within 4 hours
3. Document complaint verbatim

**Vendor Notification:**
1. Vendor reports incident affecting LSHA
2. Vendor management escalates immediately
3. Activate vendor incident provisions

### 5.2 Initial Assessment (0-4 hours)

1. **Triage:** Assign severity level
2. **Scope:** Identify affected systems, populations, timeframe
3. **Containment:** Determine if system should be paused
4. **Team Assembly:** Activate appropriate response team
5. **Documentation:** Begin incident log

### 5.3 Investigation (4-72 hours)

1. **Root Cause Analysis:**
   - Review system logs and decision records
   - Analyze patterns in affected decisions
   - Interview relevant personnel
   - Engage technical experts as needed

2. **Impact Assessment:**
   - Quantify affected individuals
   - Assess harm severity
   - Identify regulatory implications
   - Evaluate reputational impact

3. **Evidence Preservation:**
   - Preserve system logs
   - Document system state
   - Retain relevant communications
   - Maintain chain of custody

### 5.4 Remediation

1. **Immediate Actions:**
   - System pause if warranted
   - Manual review process implementation
   - Affected individual notification (if required)

2. **Technical Fixes:**
   - Model adjustments
   - Threshold modifications
   - Feature removal
   - Retraining (if needed)

3. **Process Improvements:**
   - Policy updates
   - Training enhancements
   - Monitoring additions

4. **Validation:**
   - Test remediation effectiveness
   - Document testing results
   - Obtain sign-off before resuming

### 5.5 Recovery

1. Gradual system restoration (if paused)
2. Enhanced monitoring period
3. Stakeholder communication
4. Documentation completion

## 6. Attorney General Inquiry Response

### 6.1 TRAIGA Enforcement Framework

Under TRAIGA, the Texas Attorney General has exclusive enforcement authority. Key provisions:
- AG may issue notice of suspected violation
- 60-day cure period available for good-faith remediation
- Penalties: $10,000-$200,000 per violation; $2,000-$40,000 per day continuing

### 6.2 AG Inquiry Response Procedure

**Day 0 - Receipt:**
1. Any AG communication routed immediately to General Counsel
2. General Counsel notifies CEO and CISO
3. Activate Critical incident response
4. Acknowledge receipt (within 5 business days)

**Days 1-7 - Assessment:**
1. Assemble response team (Legal, AI Governance, System Owner)
2. Preserve all relevant documentation
3. Analyze AG's specific allegations
4. Assess factual basis and compliance posture

**Days 8-30 - Response Preparation:**
1. Prepare written response to AG
2. Document existing compliance measures
3. Identify any actual violations
4. Develop remediation plan if needed

**Days 31-60 - Cure Period (if violation exists):**
1. Implement remediation measures
2. Document all remediation activities
3. Test and validate fixes
4. Prepare cure period compliance report

**Post-60 Days:**
1. Submit cure compliance documentation to AG
2. Implement ongoing monitoring
3. Update policies and procedures
4. Conduct lessons learned

### 6.3 Safe Harbor Documentation

Maintain documentation supporting affirmative defenses:
- NIST AI RMF substantial compliance evidence
- Good-faith compliance efforts
- Testing and validation records
- Training records

## 7. Communication Guidelines

### 7.1 Internal Communication

- Need-to-know basis during active investigation
- Regular updates to executive team for High/Critical
- All-hands communication only with CEO approval

### 7.2 External Communication

- All external statements approved by Legal and Communications
- No admission of liability without Legal approval
- Regulatory communications only through Legal
- Customer notifications per approved templates

### 7.3 Documentation Standards

All incident documentation must include:
- Chronological event log
- Decision rationale
- Evidence references
- Approvals and sign-offs

## 8. Post-Incident Activities

### 8.1 Lessons Learned

Within 30 days of incident closure:
1. Conduct post-incident review
2. Document root cause and contributing factors
3. Identify process improvements
4. Update policies if needed
5. Share lessons (appropriately sanitized) with relevant teams

### 8.2 Metrics and Reporting

Track and report quarterly:
- Incident count by category and severity
- Mean time to detection
- Mean time to resolution
- Regulatory inquiries received
- Cure period utilization

## 9. Training and Testing

### 9.1 Training Requirements

- Annual incident response training for core team
- Tabletop exercises semi-annually
- AG inquiry simulation annually

### 9.2 Plan Testing

- Test communication trees quarterly
- Validate contact information monthly
- Review and update procedures annually

## 10. Policy Governance

### 10.1 Owner
The Chief Information Security Officer owns this policy.

### 10.2 Review
Annual review or after any significant incident.

### 10.3 Exceptions
No exceptions to AG inquiry response procedures.

---

**Approval:**

___________________________ | Date: ___________
Chief Information Security Officer

___________________________ | Date: ___________
General Counsel
