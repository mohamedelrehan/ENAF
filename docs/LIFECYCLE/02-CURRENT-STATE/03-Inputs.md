# Inputs

The Current State stage begins only after the successful completion and formal approval of the Strategy stage.

The purpose of this document is to define the information, documentation, stakeholders, and organizational knowledge required to perform a comprehensive and evidence-based Current State Assessment.

These inputs provide Enterprise Architects with the factual information needed to understand how the organization operates today. Together, they establish the architectural baseline that supports all subsequent stages of the ENAF lifecycle.

---

# Primary Input

The primary input to the Current State stage is the approved Strategy Decision Gate.

The Strategy Decision Gate confirms that the Strategy stage has been successfully completed, all mandatory activities have been performed, all required deliverables have been approved, and the transformation has been formally authorized to proceed.

The Current State stage therefore begins with confidence that the strategic direction, business objectives, governance approval, and transformation scope have already been established.

Rather than revalidating the outputs of the Strategy stage, the Current State Assessment builds upon them by collecting factual information about the organization's existing business and technology landscape.

---

# Assessment Inputs

While the approved Strategy Decision Gate authorizes the Current State Assessment to begin, Enterprise Architects must also collect information from across the enterprise to understand the organization's current business and technology landscape.

To establish a complete architectural baseline, Enterprise Architects must gather information from multiple business and technology domains.

Each input represents a trusted source of enterprise information that contributes to one or more assessment domains. Together, these inputs enable Enterprise Architects to understand how the organization currently operates, identify architectural strengths and weaknesses, discover risks and technical debt, and document opportunities for improvement.

The Current State Assessment is evidence-based. Every finding, observation, and recommendation should be supported by verified information collected from approved enterprise sources rather than assumptions or personal opinions.

The required inputs are grouped into the following categories:

- Strategy Governance
- Business
- Applications
- Infrastructure
- Network
- Cloud
- Security
- Operations
- Architecture Governance
- Stakeholder Knowledge

Together, these inputs provide a complete understanding of the current enterprise and establish the trusted baseline required to design the Target State Architecture.

---

# Required Inputs

## IN-CSA-01 Strategy Decision Gate Approval

### Source

Strategy Stage

### Purpose

Confirms that the Strategy stage has been successfully completed and formally approved.

The approval of **DG-STR-01 Strategy Decision Gate** certifies that all mandatory Strategy activities have been completed, all required Strategy deliverables have been reviewed and approved, and the organization is authorized to begin the Current State Assessment.

### Used By

Entire Current State Assessment

---

## IN-CSA-02 Business Documentation

### Source

Business Owners

Business Units

Enterprise Leadership

### Purpose

Provides an understanding of how the organization operates today from a business perspective.

Typical documentation includes:

- Business capability maps
- Business processes
- Organizational structure
- Operating model
- Products and services
- Customer journeys
- Value streams

### Used By

Business Assessment

---

## IN-CSA-03 Application Documentation

### Source

Application Owners

Enterprise Applications Team

### Purpose

Provides information about the current application landscape, application ownership, integrations, and business dependencies.

Typical documentation includes:

- Application inventory
- Application architecture
- Integration documentation
- Application lifecycle
- Vendor information
- Business ownership
- Application dependencies

### Used By

Application Assessment

---

## IN-CSA-04 Infrastructure Documentation

### Source

Infrastructure Team

Platform Engineering

### Purpose

Provides information about the organization's current infrastructure platforms and hosting environments.

Typical documentation includes:

- Data centers
- Compute platforms
- Virtualization platforms
- Storage platforms
- Backup solutions
- Disaster Recovery environments

### Used By

Infrastructure Assessment

---

## IN-CSA-05 Network Documentation

### Source

Network Engineering

Network Operations

### Purpose

Provides information about the current enterprise connectivity architecture and network services.

Typical documentation includes:

- Network topology
- WAN
- LAN
- Wireless
- SD-WAN
- Internet connectivity
- VPN
- DNS
- Load balancing
- Network services

### Used By

Network Assessment

---

## IN-CSA-06 Cloud Documentation

### Source

Cloud Platform Team

Cloud Operations

### Purpose

Provides information about existing cloud platforms, services, governance, and connectivity.

Typical documentation includes:

- Landing Zones
- Cloud networking
- Resource organization
- Connectivity
- Governance
- Identity integration

### Used By

Cloud Assessment

---

## IN-CSA-07 Security Documentation

### Source

Cyber Security

Information Security

Security Operations

### Purpose

Provides an understanding of the organization's current security capabilities and security posture.

Typical documentation includes:

- Security architecture
- Identity and Access Management
- Zero Trust initiatives
- Security policies
- Risk assessments
- Compliance reports
- Vulnerability assessments
- Security monitoring

### Used By

Security Assessment

---

## IN-CSA-08 Operational Documentation

### Source

Operations

Service Management

Platform Operations

### Purpose

Provides information about how enterprise services are operated, supported, monitored, and maintained.

Typical documentation includes:

- Operating procedures
- Monitoring
- Incident Management
- Problem Management
- Change Management
- Automation
- Service Level Agreements

### Used By

Operations Assessment

---

## IN-CSA-09 Governance Documentation

### Source

Enterprise Architecture

Governance Board

Risk Management

### Purpose

Provides visibility into how technology decisions are governed and controlled across the enterprise.

Typical documentation includes:

- Architecture principles
- Technology standards
- Policies
- Governance processes
- Decision records
- Compliance requirements

### Used By

Governance Assessment

---

## IN-CSA-10 Stakeholder Knowledge

### Source

Business Stakeholders

Technical Subject Matter Experts

Enterprise Architects

Operations Teams

### Purpose

Not every aspect of the enterprise is formally documented.

Interviews, workshops, and knowledge-sharing sessions provide valuable business and technical context that complements formal documentation and help validate assessment findings.

Stakeholder engagement is therefore considered a mandatory input to the Current State Assessment.

### Used By

All Enterprise Assessment Domains

---

# Input Validation

Before beginning the Current State Assessment, Enterprise Architects should verify that:

- DG-STR-01 Strategy Decision Gate has been approved.
- The assessment scope has been confirmed.
- Key stakeholders have been identified.
- Required documentation is available.
- Subject Matter Experts have been identified.
- Assessment workshops have been scheduled.
- Information gaps have been identified and documented.

Any missing inputs should be documented and addressed before the assessment proceeds.

---

# Relationship to the ENAF Lifecycle

The Current State stage begins only after the successful approval of the Strategy Decision Gate.

```
Strategy
      ↓
DG-STR-01
      ↓
Current State
      ↓
DG-CSA-01
      ↓
Target State
```

This governance model ensures that each lifecycle stage begins only after the previous stage has been formally reviewed, approved, and authorized to proceed, maintaining governance and traceability throughout the ENAF lifecycle.

---

# Summary

The quality of the Current State Assessment depends on the quality of its inputs.

By combining the approved Strategy Decision Gate with verified business, technology, security, operational, governance, and stakeholder information, Enterprise Architects establish a trusted architectural baseline that accurately represents the current enterprise and provides a solid foundation for designing the Target State Architecture.
