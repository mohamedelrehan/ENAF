# Inputs

The Target State stage begins after the successful completion and approval of the Current State stage.

Its purpose is to define the future-state business and technology architecture required to achieve the transformation objectives established during the Strategy stage while addressing the findings identified during the Current State Assessment.

Only approved outputs from previous lifecycle stages should be used as inputs to ensure governance, traceability, and architectural consistency throughout the ENAF lifecycle.

---

# Purpose

The purpose of this document is to identify the mandatory inputs required before beginning the Target State stage.

These inputs provide the approved business direction, validated architectural baseline, stakeholder expectations, and governance decisions required to design the future-state enterprise architecture.

---

# Input Sources

The Target State stage receives approved outputs from two previous lifecycle stages.

```text
Strategy Stage
        │
        ▼
Approved Strategy Outputs
        │
        ▼
Current State Stage
        │
        ▼
Approved Current State Outputs
        │
        ▼
Target State Stage
```

---

# Mandatory Inputs from the Strategy Stage

The following approved Strategy outputs provide the business direction for the Target State architecture.

| Input ID | Source | Description |
|----------|--------|-------------|
| STR-OUT-01 | Approved Business Context Document | Provides the organisational context and strategic business environment. |
| STR-OUT-02 | Approved Business Drivers Register | Defines the business drivers requiring transformation. |
| STR-OUT-03 | Approved Business Objectives Document | Defines the business outcomes the Target State must support. |
| STR-OUT-04 | Approved Scope Statement | Defines the approved scope and transformation boundaries. |
| STR-OUT-05 | Approved Stakeholder Register | Identifies the stakeholders who influence or approve the Target State. |
| STR-OUT-06 | Approved Financial Assessment | Defines the approved financial assumptions and investment constraints. |
| STR-OUT-07 | Approved Organisational Readiness Assessment | Identifies organisational capabilities and readiness considerations. |
| STR-OUT-08 | Approved Initial Risk and Constraints Register | Identifies strategic risks and constraints that influence the future architecture. |
| STR-OUT-09 | Approved Strategy Summary | Provides the consolidated strategic direction for the Target State stage. |

---

# Mandatory Inputs from the Current State Stage

The following approved Current State outputs establish the architectural baseline from which the future architecture will be designed.

| Input ID | Source | Description |
|----------|--------|-------------|
| CS-OUT-01 | Approved Business Architecture Assessment | Defines the current business architecture baseline. |
| CS-OUT-02 | Approved Application Architecture Assessment | Defines the current application landscape. |
| CS-OUT-03 | Approved Data Architecture Assessment | Defines the current data architecture baseline. |
| CS-OUT-04 | Approved Technology Architecture Assessment | Defines the current technology architecture baseline. |
| CS-OUT-05 | Approved Security Architecture Assessment | Defines the current security architecture baseline. |
| CS-OUT-06 | Approved Network Architecture Assessment | Defines the current network architecture baseline. |
| CS-OUT-07 | Approved Operational Assessment | Defines the current operational capabilities and processes. |
| CS-OUT-08 | Approved Gap Assessment | Identifies the gaps between business needs and the current environment. |
| CS-OUT-09 | Approved Current State Summary | Provides the consolidated assessment of the current enterprise architecture. |

---

# Input Validation

Before beginning the Target State stage, confirm that:

- All Strategy outputs have been approved through **STR-DG-01**.
- All Current State outputs have been approved through **CS-DG-01**.
- The approved outputs are complete and available.
- Business objectives remain valid.
- Transformation scope has not changed.
- Significant assumptions or constraints have been reviewed.
- Executive sponsorship remains in place.

If any of these conditions are not met, the relevant lifecycle stage should be reviewed before proceeding.

---

# Governance

The Enterprise Architect is responsible for confirming that only approved lifecycle outputs are used as Target State inputs.

No draft documents, working papers, or unapproved assessments should be used when defining the future-state architecture.

This governance approach ensures that every architectural decision can be traced back to an approved business requirement or validated assessment completed during the earlier lifecycle stages.

---

# Lifecycle Traceability

The movement of information into the Target State stage follows the approved ENAF governance model.

```text
Strategy Activities
        │
        ▼
Strategy Deliverables
        │
        ▼
STR-DG-01
        │
        ▼
Approved Strategy Outputs
        │
        ▼
Current State Activities
        │
        ▼
Current State Deliverables
        │
        ▼
CS-DG-01
        │
        ▼
Approved Current State Outputs
        │
        ▼
Target State Inputs
```

---

# Summary

The Target State stage depends on approved outputs from both the Strategy and Current State stages.

These approved outputs provide the business direction, governance decisions, and validated architectural baseline required to design the future-state enterprise architecture while maintaining full lifecycle traceability across ENAF.

---

# Next Step

Continue with **04-Activities.md** to define the activities required to design the Target State architecture and produce the Target State deliverables.
