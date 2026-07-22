# Current State

The Current State stage establishes a comprehensive understanding of the organization's existing business and technology environment.

Following the successful completion of the Strategy stage, Enterprise Architects perform a structured and evidence-based assessment to understand how the enterprise operates today, identify its current capabilities and limitations, and establish an approved architectural baseline.

This baseline becomes the foundation upon which all future architectural decisions, transformation initiatives, and implementation roadmaps are developed.

---

# Stage Overview

| Attribute | Description |
|-----------|-------------|
| **Lifecycle Stage** | 02 – Current State |
| **Purpose** | Establish the approved architectural baseline of the enterprise. |
| **Previous Stage** | Strategy |
| **Entry Decision Gate** | DG-STR-01 Strategy Decision Gate |
| **Exit Decision Gate** | DG-CSA-01 Current State Decision Gate |
| **Primary Output** | Current State Architecture |
| **Primary Consumer** | Target State Stage |

---

# Position within the ENAF Lifecycle

The Current State stage is the second stage of the Enterprise Network Architecture Framework (ENAF).

While the Strategy stage defines the business direction and transformation objectives, the Current State stage establishes a factual understanding of the organization's existing environment.

Together, these stages ensure that future architectural decisions are driven by both strategic intent and objective evidence.

```text
Strategy
      │
      ▼
DG-STR-01
      │
      ▼
Current State
      │
      ▼
DG-CSA-01
      │
      ▼
Target State
```

---

# Objectives

The Current State stage has the following objectives:

| Objective | Description |
|-----------|-------------|
| **Understand the Enterprise** | Develop a comprehensive understanding of the organization's current business and technology landscape. |
| **Establish the Architectural Baseline** | Produce an accurate representation of the existing enterprise architecture. |
| **Assess Enterprise Capabilities** | Evaluate current business, application, infrastructure, network, cloud, security, operational, and governance capabilities. |
| **Identify Risks and Constraints** | Discover architectural weaknesses, technical debt, dependencies, operational risks, and transformation constraints. |
| **Support Future Architecture** | Provide the factual foundation required to design the Target State Architecture. |

---

# Assessment Philosophy

The Current State Assessment is an evidence-based architectural assessment.

Enterprise Architects do not evaluate the enterprise based on assumptions or individual opinions. Every observation, finding, and recommendation should be supported by validated information obtained from approved enterprise sources.

The assessment combines documentation, stakeholder engagement, technical analysis, operational knowledge, and governance information to produce an objective and trusted representation of the current enterprise.

This architectural baseline becomes the reference point against which all future architectural decisions and transformation initiatives are evaluated.

---

# Assessment Scope

The assessment covers the complete enterprise architecture.

| Architecture Domain | Assessment Focus |
|---------------------|------------------|
| **Business** | Business capabilities, operating model, organizational structure, business processes, value streams. |
| **Applications** | Application portfolio, ownership, integrations, lifecycle, dependencies. |
| **Infrastructure** | Compute, storage, virtualization, hosting platforms, data centers, disaster recovery. |
| **Network** | Enterprise connectivity, WAN, LAN, Wireless, SD-WAN, Internet, DNS, Load Balancing. |
| **Cloud** | Landing Zones, cloud governance, connectivity, identity integration, platform services. |
| **Security** | Security architecture, Zero Trust, IAM, compliance, monitoring, risk management. |
| **Operations** | IT operations, service management, automation, monitoring, support processes. |
| **Architecture Governance** | Principles, standards, governance processes, architecture decisions, compliance. |

Each domain is assessed independently while considering its relationships and dependencies across the enterprise.

---

# Assessment Inputs

The Current State stage begins only after the successful approval of **DG-STR-01 Strategy Decision Gate**.

The Decision Gate authorizes the organization to begin assessing its existing environment and confirms that the Strategy stage has been completed and formally approved.

Following this approval, Enterprise Architects collect information from business units, technology teams, operational platforms, governance bodies, enterprise documentation, and subject matter experts to establish a complete understanding of the current enterprise.

Detailed input requirements are documented in **03-Inputs.md**.

---

# Assessment Methodology

The Current State Assessment follows a structured and repeatable methodology.

The assessment typically includes:

- Reviewing enterprise documentation.
- Conducting stakeholder interviews and workshops.
- Assessing each architecture domain.
- Validating findings using multiple information sources.
- Identifying risks, constraints, dependencies, and technical debt.
- Establishing the approved Current State Architecture.

Detailed assessment activities are documented in **04-Activities.md**.

---

# Deliverables

The Current State stage produces a collection of architectural deliverables that collectively describe the organization's existing environment.

These deliverables establish the approved architectural baseline and become the primary input for designing the Target State Architecture.

Detailed deliverables are documented in **07-Deliverables.md**.

---

# Decision Gate

The Current State stage concludes with **DG-CSA-01 Current State Decision Gate**.

The Decision Gate confirms that:

- The assessment has been completed.
- Assessment findings have been validated.
- Architectural deliverables have been reviewed and approved.
- The Current State Architecture accurately represents the enterprise.
- The organization is authorized to proceed to the Target State stage.

The Decision Gate provides the formal governance checkpoint between the Current State and Target State lifecycle stages.

---

# Document Structure

The Current State stage consists of the following documents:

| Document | Purpose |
|----------|---------|
| **01-Purpose.md** | Defines the purpose and value of the Current State stage. |
| **02-Objectives.md** | Defines the objectives and expected outcomes. |
| **03-Inputs.md** | Identifies all information required to perform the assessment. |
| **04-Activities.md** | Describes the assessment methodology and activities. |
| **05-Frameworks.md** | References supporting architecture frameworks and methodologies. |
| **06-Compliance.md** | Defines regulatory, governance, and compliance considerations. |
| **07-Deliverables.md** | Defines the approved outputs of the Current State stage. |
| **08-Decision-Gate.md** | Defines the approval criteria required to complete the stage. |
| **09-NorthStar.md** | Demonstrates the methodology using the NorthStar case study. |
| **10-Checklist.md** | Provides a structured checklist to verify stage completion. |

Together, these documents define the complete methodology for establishing the Current State Architecture.

---

# Relationship to Other Lifecycle Stages

The Current State stage provides the architectural baseline for the remainder of the ENAF lifecycle.

```text
Strategy
      │
      ▼
Current State
      │
      ▼
Target State
      │
      ▼
Architecture
      │
      ▼
Roadmap
      │
      ▼
Implementation
```

Every subsequent lifecycle stage depends upon the accuracy and completeness of the Current State Architecture.

---

# Summary

The Current State stage establishes the approved architectural baseline of the enterprise.

Through a structured, evidence-based assessment of business capabilities, technology platforms, operational processes, governance practices, and stakeholder knowledge, Enterprise Architects develop an accurate representation of the organization's existing environment.

This architectural baseline enables informed decision-making, reduces transformation risk, and provides the trusted foundation required to design a realistic, achievable, and business-aligned Target State Architecture.

The successful approval of **DG-CSA-01 Current State Decision Gate** confirms that the Current State Architecture has been validated, approved, and is ready to support the next stage of the ENAF lifecycle.
