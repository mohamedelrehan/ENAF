# Activities

## Purpose

The activities performed during the Current State stage provide a structured and repeatable methodology for assessing the organization's existing business and technology environment.

These activities guide Enterprise Architects through the process of collecting information, validating findings, assessing architectural domains, and establishing an approved Current State Architecture.

By following a consistent assessment methodology, organizations can ensure that architectural decisions are based on objective evidence, stakeholder collaboration, and a comprehensive understanding of the enterprise.

---

# Assessment Methodology

The Current State Assessment is performed through a series of structured activities that progressively develop an accurate understanding of the enterprise.

Each activity builds upon the previous one, ensuring that information is validated, architectural relationships are understood, and the resulting Current State Architecture accurately represents the organization's existing environment.

The methodology is collaborative, evidence-based, and aligned with enterprise architecture governance practices.

```text
Prepare Assessment
        │
        ▼
Collect Information
        │
        ▼
Assess Enterprise Domains
        │
        ▼
Validate Findings
        │
        ▼
Identify Risks & Opportunities
        │
        ▼
Establish Current State Architecture
```

---

# Assessment Activities

| Activity | Purpose | Primary Outcome |
|-----------|---------|-----------------|
| **Prepare the Assessment** | Define the scope, stakeholders, information sources, and assessment approach. | Assessment Plan |
| **Collect Enterprise Information** | Gather business and technical information from approved enterprise sources. | Assessment Evidence |
| **Assess Enterprise Domains** | Evaluate each architecture domain to understand the current environment. | Domain Assessments |
| **Validate Assessment Findings** | Confirm findings through evidence and stakeholder engagement. | Validated Findings |
| **Identify Risks and Opportunities** | Document strengths, weaknesses, constraints, technical debt, risks, and improvement opportunities. | Assessment Analysis |
| **Establish the Current State Architecture** | Consolidate validated findings into an approved architectural baseline. | Current State Architecture |

---

# Activity Details

## 1. Prepare the Assessment

The assessment begins by defining its scope, objectives, stakeholders, governance approach, and information sources.

Enterprise Architects identify the business units, technology teams, subject matter experts, documentation repositories, and enterprise platforms that will contribute to the assessment.

The objective of this activity is to ensure that the assessment is properly planned before information collection begins.

---

## 2. Collect Enterprise Information

Enterprise Architects gather information from approved enterprise sources, including business documentation, technical documentation, architecture repositories, operational systems, monitoring platforms, governance artifacts, and stakeholder interviews.

Information should be collected from multiple sources whenever possible to improve accuracy and completeness.

Every significant finding should be traceable to verifiable evidence.

---

## 3. Assess Enterprise Domains

Each architecture domain is assessed independently while considering its relationships with the broader enterprise architecture.

The assessment evaluates the current capabilities, maturity, dependencies, operational effectiveness, architectural alignment, and existing constraints within each domain.

Typical assessment domains include:

- Business
- Applications
- Infrastructure
- Network
- Cloud
- Security
- Operations
- Architecture Governance

---

## 4. Validate Assessment Findings

Assessment findings should be validated before becoming part of the Current State Architecture.

Validation includes:

- Reviewing collected evidence.
- Confirming findings with business stakeholders.
- Confirming technical observations with engineering teams.
- Resolving inconsistencies.
- Verifying architectural relationships.

The objective is to ensure that the architectural baseline accurately reflects the enterprise.

---

## 5. Identify Risks and Opportunities

Following validation, Enterprise Architects analyse the assessment results to identify:

- Architectural strengths
- Operational challenges
- Technology limitations
- Technical debt
- Security gaps
- Compliance concerns
- Business constraints
- Improvement opportunities

These findings provide important input for designing the Target State Architecture.

---

## 6. Establish the Current State Architecture

The final activity consolidates all validated assessment findings into a single architectural baseline.

The Current State Architecture represents the organization's approved view of its existing business and technology environment and becomes the primary reference for future architecture and transformation activities.

The architectural baseline should be reviewed through the organization's governance process before progressing to the Decision Gate.

---

# Assessment Principles

The Current State Assessment should be performed in accordance with the following principles.

| Principle | Description |
|-----------|-------------|
| **Evidence-Based** | Findings should be supported by objective and verifiable information. |
| **Business-Driven** | The assessment should focus on enabling business outcomes rather than documenting technology for its own sake. |
| **Enterprise-Wide** | The assessment should consider the enterprise as an integrated ecosystem rather than isolated systems. |
| **Collaborative** | Business and technology stakeholders should participate throughout the assessment process. |
| **Objective** | Conclusions should remain independent of vendors, products, and personal preferences. |
| **Traceable** | Significant findings should be traceable to approved enterprise sources. |
| **Repeatable** | The methodology should produce consistent results when applied across different transformation initiatives. |

---

# Success Considerations

The effectiveness of the Current State Assessment depends upon several critical success factors.

| Success Factor | Description |
|----------------|-------------|
| **Executive Sponsorship** | Leadership support enables enterprise-wide participation and access to information. |
| **Stakeholder Engagement** | Active involvement from business and technical stakeholders improves assessment quality. |
| **Reliable Information** | Assessment findings depend on accurate, current, and validated enterprise information. |
| **Cross-Domain Collaboration** | Collaboration across architecture domains provides a complete enterprise perspective. |
| **Governance** | Regular architectural reviews ensure assessment quality and consistency. |

---

# Relationship to Other Lifecycle Stages

The activities performed during the Current State stage establish the architectural baseline that supports all subsequent lifecycle stages.

```text
Strategy
      │
      ▼
Current State Activities
      │
      ▼
Current State Architecture
      │
      ▼
Target State
      │
      ▼
Architecture
      │
      ▼
Roadmap
```

Every architecture decision made during subsequent stages should be informed by the approved Current State Architecture.

---

# Summary

The activities of the Current State stage provide a structured methodology for understanding the enterprise as it exists today.

By following a consistent process of planning, information collection, domain assessment, validation, analysis, and architectural consolidation, Enterprise Architects establish a trusted Current State Architecture that supports informed decision-making, effective governance, and the successful design of the Target State Architecture.

The completion of these activities provides the evidence and confidence required to progress to **DG-CSA-01 Current State Decision Gate**, where the architectural baseline is formally reviewed and approved.
