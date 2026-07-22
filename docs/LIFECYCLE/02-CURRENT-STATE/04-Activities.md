# Activities

The Activities document defines the work performed during the Current State stage.

The purpose of these activities is to answer the fundamental ENAF question:

> **Where are we today?**

Each activity contributes to building a trusted architectural baseline by assessing one or more Enterprise Assessment Domains.

The activities should be completed in sequence, although some may be performed in parallel depending on the size and complexity of the organization.

---

# ACT-CSA-01 Understand the Business

## Purpose

Develop a comprehensive understanding of how the organization creates value, delivers products and services, and achieves its strategic objectives.

## Why It Is Performed

Enterprise Architecture must begin with the business rather than the technology.

Understanding the business ensures that every future architectural decision supports measurable business outcomes.

## Key Tasks

- Review the business model.
- Understand products and services.
- Identify business capabilities.
- Review organizational structure.
- Understand business processes.
- Identify business stakeholders.
- Understand strategic priorities.

## Participants

- Business Leadership
- Business Owners
- Enterprise Architect

## Inputs

- IN-CSA-01 Approved Strategy
- IN-CSA-02 Business Documentation

## Outputs

Supports:

- DEL-CSA-01 Current State Assessment
- DEL-CSA-02 Business Capability Assessment

## Success Criteria

- Business model understood.
- Business capabilities identified.
- Major business processes documented.
- Stakeholders identified.

## Related Enterprise Domains

- Business

---

# ACT-CSA-02 Assess the Application Landscape

## Purpose

Develop a complete understanding of the applications supporting the enterprise.

## Why It Is Performed

Applications enable business capabilities and often represent significant operational complexity and technical debt.

## Key Tasks

- Inventory applications.
- Identify business owners.
- Review integrations.
- Understand dependencies.
- Review application lifecycle.
- Identify redundant applications.

## Participants

- Application Owners
- Enterprise Applications Team
- Enterprise Architect

## Inputs

- IN-CSA-03 Application Documentation

## Outputs

Supports:

- DEL-CSA-03 Application Inventory

## Success Criteria

- Application inventory completed.
- Critical integrations documented.
- Major dependencies identified.

## Related Enterprise Domains

- Applications

---

# ACT-CSA-03 Assess Infrastructure

## Purpose

Understand the organization's existing infrastructure platforms and supporting technologies.

## Why It Is Performed

Infrastructure provides the foundation for enterprise services and directly influences scalability, resilience, and operational efficiency.

## Key Tasks

- Assess compute platforms.
- Assess storage.
- Assess virtualization.
- Review backup.
- Review disaster recovery.
- Identify infrastructure dependencies.

## Participants

- Infrastructure Team
- Platform Engineering
- Enterprise Architect

## Inputs

- IN-CSA-04 Infrastructure Documentation

## Outputs

Supports:

- DEL-CSA-04 Infrastructure Assessment

## Success Criteria

- Infrastructure inventory completed.
- Platform dependencies identified.
- Major risks documented.

## Related Enterprise Domains

- Infrastructure

---

# ACT-CSA-04 Assess Network Architecture

## Purpose

Develop a complete understanding of the enterprise connectivity architecture.

## Why It Is Performed

The network enables communication between users, applications, services, cloud platforms, and external partners.

A clear understanding of the existing network is essential before designing future connectivity.

## Key Tasks

- Review WAN architecture.
- Review LAN architecture.
- Review wireless architecture.
- Review Internet connectivity.
- Review SD-WAN.
- Review remote access.
- Review DNS.
- Review load balancing.
- Review network resilience.
- Identify dependencies.

## Participants

- Network Engineering
- Network Operations
- Enterprise Architect

## Inputs

- IN-CSA-05 Network Documentation

## Outputs

Supports:

- DEL-CSA-05 Network Assessment

## Success Criteria

- Network topology understood.
- Connectivity documented.
- Network dependencies identified.
- Risks documented.

## Related Enterprise Domains

- Network

---

# ACT-CSA-05 Assess Cloud Platforms

## Purpose

Understand the organization's cloud architecture and operational maturity.

## Key Tasks

- Assess cloud landing zones.
- Assess subscriptions.
- Assess networking.
- Assess governance.
- Assess identity integration.
- Assess operational maturity.

## Participants

- Cloud Team
- Cloud Operations
- Enterprise Architect

## Inputs

- IN-CSA-06 Cloud Documentation

## Outputs

Supports:

- DEL-CSA-06 Cloud Assessment

## Success Criteria

- Cloud environments understood.
- Governance documented.
- Risks identified.

## Related Enterprise Domains

- Cloud

---

# ACT-CSA-06 Assess Security

## Purpose

Understand the organization's current security capabilities.

## Key Tasks

- Assess IAM.
- Assess network security.
- Assess endpoint protection.
- Assess monitoring.
- Assess compliance.
- Review Zero Trust initiatives.
- Review security operations.

## Participants

- Security Team
- SOC
- Enterprise Architect

## Inputs

- IN-CSA-07 Security Documentation

## Outputs

Supports:

- DEL-CSA-07 Security Assessment

## Success Criteria

- Security architecture understood.
- Security gaps identified.
- Compliance posture documented.

## Related Enterprise Domains

- Security

---

# ACT-CSA-07 Assess Operations

## Purpose

Understand how enterprise services are operated and supported.

## Key Tasks

- Review monitoring.
- Review automation.
- Review incident management.
- Review problem management.
- Review change management.
- Review operational maturity.

## Participants

- Operations Team
- Service Management
- Enterprise Architect

## Inputs

- IN-CSA-08 Operational Documentation

## Outputs

Supports:

- DEL-CSA-08 Operations Assessment

## Success Criteria

- Operational processes documented.
- Service management maturity understood.
- Automation opportunities identified.

## Related Enterprise Domains

- Operations

---

# ACT-CSA-08 Assess Governance

## Purpose

Understand how technology decisions are governed across the enterprise.

## Key Tasks

- Review architecture standards.
- Review policies.
- Review governance boards.
- Review decision processes.
- Review compliance.
- Review documentation standards.

## Participants

- Enterprise Architecture
- Governance Board
- Risk Management

## Inputs

- IN-CSA-09 Governance Documentation

## Outputs

Supports:

- DEL-CSA-01 Current State Assessment

## Success Criteria

- Governance model understood.
- Standards documented.
- Decision-making process understood.

## Related Enterprise Domains

- Governance

---

# ACT-CSA-09 Identify Risks and Technical Debt

## Purpose

Identify the business and technical factors that may affect the transformation.

## Why It Is Performed

Understanding risk early enables better architectural decisions and more realistic transformation planning.

## Key Tasks

- Identify business risks.
- Identify technical risks.
- Identify operational risks.
- Identify architectural constraints.
- Identify technical debt.
- Document improvement opportunities.

## Participants

- Enterprise Architect
- Domain Architects
- Business Representatives
- Technical SMEs

## Inputs

- Findings from ACT-CSA-01 through ACT-CSA-08

## Outputs

Supports:

- DEL-CSA-09 Technical Debt Register
- DEL-CSA-10 Current State Summary

## Success Criteria

- Risks documented.
- Constraints identified.
- Technical debt prioritized.

## Related Enterprise Domains

- Business
- Applications
- Infrastructure
- Network
- Cloud
- Security
- Operations
- Governance

---

# Activity Summary

The Current State activities establish the architectural baseline by systematically assessing every Enterprise Assessment Domain.

The outputs produced by these activities become the evidence used to create the Current State Assessment, validate the architectural baseline, and provide the foundation for the Target State stage.
