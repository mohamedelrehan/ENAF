# Decision Gate

The Architecture Decision Gate (**AR-DG-01**) is the formal governance checkpoint that concludes the Architecture stage of the ENAF lifecycle.

Its purpose is to verify that the enterprise architecture has been completed, reviewed, and approved before progressing to the Roadmap stage.

The Decision Gate ensures that the enterprise architecture fully implements the approved Target State, provides consistent architectural guidance across all domains, and establishes the standards, principles, and reference architectures required to guide future transformation initiatives.

No work should begin in the Roadmap stage until the Architecture Decision Gate has been successfully approved.

---

# Purpose

The purpose of **AR-DG-01** is to:

- Verify that all Architecture activities have been completed.
- Confirm that all required Architecture deliverables have been produced.
- Validate alignment with the approved Strategy, Current State, and Target State outputs.
- Confirm that enterprise architecture principles and standards have been established.
- Ensure reusable reference architectures are available.
- Authorise progression to the Roadmap stage.

---

# Decision Gate Inputs

The following deliverables are reviewed during **AR-DG-01**.

| Deliverable ID | Deliverable |
|----------------|-------------|
| DEL-AR-01 | Business Architecture |
| DEL-AR-02 | Application Architecture |
| DEL-AR-03 | Data Architecture |
| DEL-AR-04 | Technology Architecture |
| DEL-AR-05 | Security Architecture |
| DEL-AR-06 | Network Architecture |
| DEL-AR-07 | Architecture Principles and Standards |
| DEL-AR-08 | Reference Architectures |
| DEL-AR-09 | Architecture Summary |

---

# Review Criteria

The Decision Gate should confirm that:

- The enterprise architecture supports the approved Target State.
- Enterprise architecture has been defined across all required domains.
- Architecture principles and standards have been established.
- Reference architectures are complete and reusable.
- Technology standards have been defined.
- Architectural assumptions and constraints have been documented.
- Compliance and governance requirements have been satisfied.
- Stakeholders have reviewed the enterprise architecture.
- The architecture is suitable to support roadmap development.

---

# Decision Outcomes

The governance board should record one of the following outcomes.

| Decision | Description |
|----------|-------------|
| **Approved** | The enterprise architecture is approved and the Roadmap stage may begin. |
| **Approved with Conditions** | Minor actions remain. The Roadmap stage may begin once the agreed conditions have been satisfied. |
| **Deferred** | Additional information or clarification is required before a decision can be made. |
| **Rejected** | Significant issues have been identified. The Architecture stage must be revisited before resubmission. |

---

# Participants

The Decision Gate should include representatives appropriate to the organisation, typically including:

- Executive Sponsor
- Enterprise Architect
- Business Leadership
- Domain Architects
- Solution Architecture Representatives
- Security Representatives
- Technology Leadership
- Governance or Architecture Review Board

---

# Approved Outputs

Following successful approval through **AR-DG-01**, the Architecture deliverables become the official approved outputs of the Architecture stage.

| Output ID | Approved Output |
|-----------|-----------------|
| AR-OUT-01 | Approved Business Architecture |
| AR-OUT-02 | Approved Application Architecture |
| AR-OUT-03 | Approved Data Architecture |
| AR-OUT-04 | Approved Technology Architecture |
| AR-OUT-05 | Approved Security Architecture |
| AR-OUT-06 | Approved Network Architecture |
| AR-OUT-07 | Approved Architecture Principles and Standards |
| AR-OUT-08 | Approved Reference Architectures |
| AR-OUT-09 | Approved Architecture Summary |

These approved outputs become the mandatory inputs for the Roadmap stage.

---

# Governance Responsibilities

The Enterprise Architect is responsible for:

- Presenting the completed Architecture deliverables.
- Demonstrating alignment with the approved Target State.
- Explaining architecture principles, standards, and reference architectures.
- Documenting architectural assumptions, constraints, and key decisions.
- Recording any agreed actions resulting from the Decision Gate.

The governance board is responsible for approving, deferring, or rejecting the proposed enterprise architecture.

---

# Lifecycle Traceability

The movement of information through the Architecture governance process follows the ENAF lifecycle.

```text
Architecture Activities
        │
        ▼
DEL-AR Deliverables
        │
        ▼
AR-DG-01
        │
        ▼
AR-OUT Approved Outputs
        │
        ▼
Roadmap Stage Inputs
```

---

# Summary

The Architecture Decision Gate (**AR-DG-01**) provides formal governance approval for the organisation's enterprise architecture.

Following successful approval, the Architecture deliverables become approved Architecture outputs and establish the authorised enterprise architecture baseline used to develop the transformation roadmap.

---

# Next Step

Continue with **09-NorthStar.md** to see how the Architecture stage is applied within the NorthStar case study and how the enterprise architecture is developed from the approved Target State.
