# Compliance

The Strategy stage establishes the compliance context for the transformation initiative.

Before architectural decisions are made, architects must understand the legal, regulatory, contractual, and organizational obligations that will influence the future solution.

Compliance should not be treated as a final validation activity. It should be considered from the beginning of the architecture lifecycle to reduce project risk, avoid costly redesigns, and ensure that business objectives can be achieved within the required regulatory framework.

---

## Purpose

The purpose of this document is to identify the compliance obligations that may affect the transformation initiative and ensure they are considered during strategic planning.

Understanding compliance requirements early allows architects to incorporate them into future architecture decisions rather than attempting to address them during implementation.

---

# Compliance Categories

Compliance requirements typically fall into several categories.

## Legal and Regulatory

Requirements imposed by governments or regulatory authorities.

Examples include:

- GDPR
- NIS2
- DORA
- HIPAA
- SOX
- Local data protection laws
- Telecommunications regulations

These requirements may influence:

- Data residency
- Identity management
- Logging
- Encryption
- Network segmentation
- Business continuity

---

## Industry Standards

Organizations often adopt internationally recognized standards to improve governance and security.

Examples include:

- ISO 27001
- ISO 22301
- ISO 20000
- PCI DSS
- CIS Controls

These standards influence future architecture principles and operational practices.

---

## Internal Policies

Every organization has internal governance requirements.

Examples include:

- Enterprise Architecture Principles
- Security Standards
- Cloud Strategy
- Network Standards
- Technology Standards
- Risk Policies
- Data Classification Policies

These internal requirements are often as important as external regulations.

---

## Contractual Obligations

Business contracts frequently introduce additional compliance requirements.

Examples include:

- Customer security requirements
- Service Level Agreements (SLAs)
- Vendor agreements
- Data processing agreements
- Audit rights
- Confidentiality requirements

Architects should understand these obligations before defining the target architecture.

---

## Geographic Requirements

Global organizations often operate across multiple countries.

Compliance obligations may vary depending on:

- Country
- Region
- Business Unit
- Cloud Region
- Data Location

Examples include:

- Data sovereignty
- Cross-border data transfers
- Regional security regulations
- Government restrictions

These requirements may influence future hosting and connectivity decisions.

---

# Compliance Assessment Activities

During the Strategy stage, architects should:

- Identify applicable regulations.
- Review internal governance policies.
- Consult compliance and legal teams.
- Identify contractual obligations.
- Review audit findings.
- Understand security requirements.
- Identify data protection obligations.
- Document known compliance risks.

The objective is not to perform a compliance audit, but to establish the compliance context for the transformation.

---

# Compliance Considerations Across ENAF Activities

| ENAF Activity | Compliance Focus |
|--------------|------------------|
| STR-01 Understand the Business | Regulatory environment |
| STR-02 Identify Business Drivers | Compliance-driven initiatives |
| STR-03 Define Business Objectives | Regulatory business goals |
| STR-04 Define Scope | Regulatory boundaries |
| STR-05 Identify Stakeholders | Compliance stakeholders |
| STR-06 Financial Constraints | Regulatory investment requirements |
| STR-07 Organizational Readiness | Governance capabilities |
| STR-08 Risks and Constraints | Compliance risks |
| STR-09 Business Alignment | Executive compliance commitment |

---

# Key Questions

Architects should be able to answer the following questions before leaving the Strategy stage.

### Regulatory

- Which regulations apply?
- Which countries are affected?
- Are there mandatory security controls?

### Organizational

- Which internal policies apply?
- Are architecture standards already defined?
- Are there mandatory technology standards?

### Data

- Where will data be stored?
- Are there residency requirements?
- Are there classification requirements?

### Risk

- What are the major compliance risks?
- Have previous audits identified issues?
- Are there known regulatory concerns?

### Governance

- Who owns compliance?
- Who approves exceptions?
- How will compliance be validated later?

---

# Outputs

The Strategy stage should produce:

- Initial Compliance Assessment
- Applicable Regulations Register
- Internal Policy Register
- Compliance Risks
- Compliance Assumptions
- Compliance Constraints

These outputs become inputs for the Current State Assessment and future architecture activities.

---

# Success Criteria

The compliance activity is considered complete when:

- Applicable regulations have been identified.
- Internal policies have been reviewed.
- Compliance stakeholders have been engaged.
- Major compliance risks have been documented.
- Compliance assumptions have been validated.
- Regulatory constraints have been communicated to the architecture team.

---

## Summary

Compliance is a business requirement that shapes architecture from the beginning of the transformation journey.

By identifying legal, regulatory, contractual, and organizational obligations during the Strategy stage, architects can ensure that future designs support business objectives while meeting governance and compliance expectations.

---

## Next Step

Continue with **07-Deliverables.md** to understand the artifacts and documentation that should be produced as outputs of the Strategy stage.
