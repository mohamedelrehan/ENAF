# Deliverables

The Deliverables document defines the architecture artifacts produced during the Current State stage.

These deliverables represent the validated outputs of the Current State Assessment and establish the architectural baseline for the organization.

Each deliverable is created through one or more Current State activities and serves as an input to the Target State stage.

Collectively, these deliverables provide a comprehensive understanding of the organization's current business and technology landscape.

---

# Primary Deliverable

The primary deliverable of the Current State stage is the **Current State Assessment**.

This assessment consolidates the findings from all Enterprise Assessment Domains into a single architectural baseline that accurately represents the organization as it exists today.

The Current State Assessment becomes the official reference for all future architecture and transformation decisions.

---

# Deliverables

## DEL-CSA-01 Current State Assessment

### Purpose

Provides a consolidated view of the organization's current enterprise architecture across all Enterprise Assessment Domains.

### Produced By

- ACT-CSA-01 through ACT-CSA-09

### Owner

Enterprise Architect

### Consumed By

Target State Stage

---

## DEL-CSA-02 Business Capability Assessment

### Purpose

Documents the current business capabilities, business processes, organizational structure, and business maturity.

### Produced By

- ACT-CSA-01 Understand the Business

### Owner

Enterprise Architect

### Consumed By

Target State Stage

---

## DEL-CSA-03 Application Assessment

### Purpose

Documents the current application landscape, business ownership, integrations, lifecycle, and dependencies.

### Produced By

- ACT-CSA-02 Assess the Application Landscape

### Owner

Enterprise Applications Team

### Consumed By

Target State Stage

---

## DEL-CSA-04 Infrastructure Assessment

### Purpose

Documents the existing infrastructure environment, including compute, storage, virtualization, backup, resilience, and platform dependencies.

### Produced By

- ACT-CSA-03 Assess Infrastructure

### Owner

Infrastructure Team

### Consumed By

Target State Stage

---

## DEL-CSA-05 Network Assessment

### Purpose

Documents the organization's current network architecture, connectivity services, resilience, dependencies, and operational characteristics.

### Produced By

- ACT-CSA-04 Assess Network Architecture

### Owner

Network Architecture Team

### Consumed By

Target State Stage

---

## DEL-CSA-06 Cloud Assessment

### Purpose

Documents the current cloud platforms, landing zones, governance model, networking, identity integration, and operational maturity.

### Produced By

- ACT-CSA-05 Assess Cloud Platforms

### Owner

Cloud Architecture Team

### Consumed By

Target State Stage

---

## DEL-CSA-07 Security Assessment

### Purpose

Documents the current security architecture, security capabilities, compliance posture, and identified security gaps.

### Produced By

- ACT-CSA-06 Assess Security

### Owner

Security Architecture Team

### Consumed By

Target State Stage

---

## DEL-CSA-08 Operations Assessment

### Purpose

Documents the operational model, service management capabilities, monitoring, automation, and operational maturity.

### Produced By

- ACT-CSA-07 Assess Operations

### Owner

Operations Team

### Consumed By

Target State Stage

---

## DEL-CSA-09 Governance Assessment

### Purpose

Documents the current governance model, architecture standards, policies, decision-making processes, and governance maturity.

### Produced By

- ACT-CSA-08 Assess Governance

### Owner

Enterprise Architecture

### Consumed By

Target State Stage

---

## DEL-CSA-10 Risk and Technical Debt Register

### Purpose

Documents identified business risks, technical risks, architectural constraints, and technical debt that may affect the transformation.

### Produced By

- ACT-CSA-09 Identify Risks and Technical Debt

### Owner

Enterprise Architect

### Consumed By

Target State Stage

---

# Deliverable Relationships

The Current State deliverables collectively establish the architectural baseline for the enterprise.

Each deliverable contributes to the overall Current State Assessment and provides domain-specific knowledge that will be used to design the future enterprise architecture.

| Deliverable | Primary Consumer |
|-------------|------------------|
| DEL-CSA-01 Current State Assessment | Target State |
| DEL-CSA-02 Business Capability Assessment | Target State |
| DEL-CSA-03 Application Assessment | Target State |
| DEL-CSA-04 Infrastructure Assessment | Target State |
| DEL-CSA-05 Network Assessment | Target State |
| DEL-CSA-06 Cloud Assessment | Target State |
| DEL-CSA-07 Security Assessment | Target State |
| DEL-CSA-08 Operations Assessment | Target State |
| DEL-CSA-09 Governance Assessment | Target State |
| DEL-CSA-10 Risk and Technical Debt Register | Target State |

---

# Relationship to the ENAF Lifecycle

The deliverables produced during the Current State stage provide the validated baseline required to design the future enterprise.

Within the ENAF lifecycle:

- Objectives define what should be achieved.
- Inputs provide the information required.
- Activities perform the assessment.
- Frameworks guide the assessment.
- Compliance ensures regulatory alignment.
- Deliverables capture the assessment results.
- Decision Gates verify readiness before progressing to the Target State stage.

---

# Summary

The Current State deliverables represent the official architectural baseline of the organization.

They provide a structured and validated view of the enterprise across all Enterprise Assessment Domains, enabling informed decision-making during the Target State stage.

By producing consistent and traceable architecture artifacts, ENAF ensures that every transformation initiative is based on a clear understanding of the existing environment.
