# Current State

The Current State stage is the second stage of the Enterprise Network Architecture Framework (ENAF) lifecycle.

Following the approval of the Strategy stage, the purpose of the Current State stage is to establish a complete understanding of the organization's existing business and technology environment before defining the future Target State.

Successful transformation begins with facts rather than assumptions.

Enterprise Architects must understand how the organization currently operates, which capabilities already exist, what technologies support the business, where risks and technical debt exist, and which constraints will influence future architectural decisions.

The objective of this stage is not to design the future architecture or recommend technologies. Instead, it is to create a validated architectural baseline that accurately represents the current enterprise.

By the end of this stage, the organization has a shared understanding of its existing capabilities, strengths, weaknesses, risks, and opportunities, providing the foundation for the Target State design.

---

# Purpose

The Current State stage establishes the architectural baseline for the transformation.

Rather than making assumptions about the existing environment, Enterprise Architects perform a structured assessment of the enterprise to understand what currently exists, how it supports the business, and where improvements are required.

This stage answers questions such as:

- How does the business operate today?
- Which business capabilities currently exist?
- Which applications support the business?
- How is the infrastructure designed?
- How is the enterprise network connected?
- How are cloud platforms being used?
- How is security implemented?
- How are services operated and supported?
- What governance processes currently exist?
- What are the major risks, constraints, and areas of technical debt?

---

# Stage Objectives

The objectives of the Current State stage are to:

- Understand the existing business environment.
- Assess enterprise capabilities.
- Assess business processes.
- Inventory applications and services.
- Assess infrastructure platforms.
- Assess network architecture.
- Assess cloud environments.
- Assess security capabilities.
- Assess operational maturity.
- Assess governance maturity.
- Identify technical debt.
- Identify business and technical risks.
- Establish a validated architectural baseline.

---

# Learning Outcomes

After completing this stage, you should be able to:

- Explain how the organization currently operates.
- Understand the existing enterprise architecture.
- Identify strengths and weaknesses across all enterprise domains.
- Understand business and technical dependencies.
- Identify architectural risks and technical debt.
- Produce a complete Current State Assessment.
- Establish a trusted baseline for designing the Target State.

---

# Lifecycle Position

The Current State stage follows the approved Strategy stage.

```text
Foundation
      │
      ▼
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
      │
      ▼
Operations
      │
      ▼
Governance
      │
      ▼
Optimization
```

The outputs produced during the Strategy stage become mandatory inputs for the Current State Assessment.

The outputs of the Current State stage become mandatory inputs for the Target State stage.

---

# Current State Workflow

Every ENAF lifecycle stage follows the same governance model.

```text
Inputs
      │
      ▼
Assessment Activities
      │
      ▼
Deliverables
      │
      ▼
Checklist
      │
      ▼
Decision Gate
      │
      ▼
Next Lifecycle Stage
```

This governance model ensures that architectural decisions are based on verified information rather than assumptions.

---

# Enterprise Assessment Domains

ENAF introduces **Enterprise Assessment Domains** to ensure that every transformation is evaluated from a complete enterprise perspective rather than focusing on technology alone.

These domains provide a consistent structure for understanding the organization and are reused throughout the entire ENAF lifecycle.

During the Current State stage, each domain is assessed to establish the organization's architectural baseline.

| Domain | Purpose |
|----------|----------|
| Business | Assess business capabilities, services, organizational structure, and business processes. |
| Applications | Assess business applications, integrations, dependencies, and application lifecycle. |
| Infrastructure | Assess compute, storage, virtualization, backup, and data center environments. |
| Network | Assess WAN, LAN, wireless, Internet connectivity, remote access, network services, and resilience. |
| Cloud | Assess cloud platforms, landing zones, connectivity, governance, and cloud operations. |
| Security | Assess identity, access management, network security, endpoint protection, monitoring, and compliance controls. |
| Operations | Assess monitoring, automation, service management, operational processes, and support capabilities. |
| Governance | Assess architecture standards, policies, documentation, lifecycle management, and governance maturity. |

These Enterprise Assessment Domains become the common structure used throughout ENAF.

| Lifecycle Stage | Enterprise Domains |
|-----------------|--------------------|
| Current State | Assess |
| Target State | Design |
| Architecture | Define |
| Roadmap | Prioritize |
| Implementation | Build |
| Operations | Operate |
| Governance | Govern |
| Optimization | Improve |

This approach ensures consistency across every stage of the transformation lifecycle.

---

# Documents

The Current State stage consists of the following documents.

| Document | Description |
|----------|-------------|
| 01-Purpose | Explains why the Current State stage exists. |
| 02-Objectives | Defines the expected outcomes of the assessment. |
| 03-Inputs | Identifies the information required before the assessment begins. |
| 04-Activities | Describes the assessment activities performed during this stage. |
| 05-Frameworks | Maps industry frameworks to the Current State activities. |
| 06-Compliance | Identifies governance and compliance considerations during the assessment. |
| 07-Deliverables | Defines the outputs produced during the assessment. |
| 08-Decision-Gate | Defines the governance approval required before progressing. |
| 09-NorthStar | Demonstrates the Current State Assessment using the NorthStar case study. |
| 10-Checklist | Confirms readiness before requesting the Decision Gate. |

The documents should be completed in numerical order.

---

# Deliverables

Successful completion of the Current State stage produces the following deliverables.

| ID | Deliverable |
|----|-------------|
| DEL-CSA-01 | Current State Assessment Report |
| DEL-CSA-02 | Business Capability Assessment |
| DEL-CSA-03 | Application Inventory |
| DEL-CSA-04 | Infrastructure Assessment |
| DEL-CSA-05 | Network Assessment |
| DEL-CSA-06 | Cloud Assessment |
| DEL-CSA-07 | Security Assessment |
| DEL-CSA-08 | Operations Assessment |
| DEL-CSA-09 | Technical Debt Register |
| DEL-CSA-10 | Current State Summary |

These deliverables establish the architectural baseline for defining the Target State.

---

# Governance

The Current State stage cannot be completed until the required governance activities have been performed.

The governance process consists of:

1. Completing all assessment activities.
2. Producing the required deliverables.
3. Completing the Current State Checklist.
4. Passing Decision Gate **DG-CSA-01**.

Only after formal approval should the project proceed to the Target State stage.

---

# NorthStar Case Study

The NorthStar case study demonstrates how an Enterprise Architecture team performs a structured Current State Assessment using the ENAF Enterprise Assessment Domains.

The case study focuses exclusively on understanding the existing enterprise.

No future architecture, technology selection, migration planning, or implementation decisions are made during this stage.

The findings produced here become the foundation for designing the Target State.

---

# Related Stages

| Stage | Relationship |
|--------|--------------|
| Strategy | Provides the approved business objectives, scope, stakeholders, and governance required to begin the Current State Assessment. |
| Target State | Uses the validated Current State Assessment to define the future enterprise architecture and transformation vision. |

---

# Next Stage

After completing the Current State Checklist and receiving approval through **Decision Gate DG-CSA-01**, continue to the **Target State** stage.

The Target State stage defines the future enterprise by designing the business capabilities, technology architecture, and transformation vision required to achieve the strategic objectives established during the Strategy stage and informed by the Current State Assessment.
