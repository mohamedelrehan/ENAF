# How to Use ENAF

The Enterprise Network Architecture Framework (ENAF) provides a structured approach for designing, governing, implementing, and continuously improving enterprise network architectures.

Unlike traditional frameworks that focus primarily on methodology, ENAF provides a practical lifecycle that can be applied to projects of different sizes, technologies, and business objectives.

This document explains how to apply ENAF from the initial business request through implementation and continuous improvement.

---

## Purpose

The purpose of this document is to provide practical guidance for applying ENAF throughout an enterprise transformation initiative.

It describes the recommended sequence of activities, expected outcomes, governance checkpoints, and responsibilities for each stage of the lifecycle.

---

## Before You Start

Before applying ENAF, ensure the following information is available.

### Business Information

- Business objectives
- Project scope
- Executive sponsor
- Business stakeholders
- Success criteria

### Technical Information

- Existing architecture documentation
- Network diagrams
- Cloud architecture
- Security documentation
- Operational documentation
- Technology inventory

### Organizational Information

- Project team
- Architecture team
- Security team
- Operations team
- Governance process

Starting without understanding these inputs often leads to unnecessary redesign, delays, and increased project risk.

---

# Applying the ENAF Lifecycle

Every transformation should follow the ENAF lifecycle.

Although activities may vary depending on project size, the overall sequence remains the same.

---

# Step 1 — Understand the Business

## Objective

Understand why the project exists before discussing technology.

## Activities

- Meet business stakeholders
- Identify business drivers
- Define business goals
- Understand risks
- Define success criteria

## Inputs

- Business strategy
- Executive direction
- Existing business capabilities

## Outputs

- Business requirements
- Stakeholder map
- Business objectives

## Decision Gate

Business stakeholders agree that the problem is clearly understood.

---

# Step 2 — Assess the Current State

## Objective

Understand the existing environment.

## Activities

- Review documentation
- Interview technical teams
- Assess current architecture
- Identify risks
- Identify technical debt

## Inputs

- Existing environment
- Network diagrams
- Security documentation

## Outputs

- Current State Assessment
- Gap Analysis
- Risk Assessment

## Decision Gate

Current environment is sufficiently documented.

---

# Step 3 — Define the Target State

## Objective

Describe the desired future architecture.

## Activities

- Define target capabilities
- Identify architectural improvements
- Define operating model
- Validate business alignment

## Outputs

- Target Architecture
- Future Capabilities
- Success Criteria

## Decision Gate

Business and architecture teams approve the target state.

---

# Step 4 — Design the Architecture

## Objective

Translate the target state into implementable architecture.

## Activities

- Produce architecture diagrams
- Define standards
- Create reference architectures
- Define security architecture
- Produce Architecture Decision Records (ADR)

## Outputs

- High-Level Design
- Low-Level Design
- Reference Architecture
- Architecture Standards

## Decision Gate

Architecture Review Board approves the solution.

---

# Step 5 — Build the Roadmap

## Objective

Plan the transformation journey.

## Activities

- Prioritize initiatives
- Define implementation phases
- Identify dependencies
- Estimate effort
- Identify risks

## Outputs

- Transformation Roadmap
- Migration Plan
- Investment Plan

## Decision Gate

Roadmap approved for implementation.

---

# Step 6 — Implement

## Objective

Deploy the approved architecture.

## Activities

- Build infrastructure
- Configure services
- Automate deployments
- Validate functionality
- Perform testing

## Outputs

- Production Environment
- Automation Code
- Test Reports
- Deployment Documentation

## Decision Gate

Implementation successfully completed.

---

# Step 7 — Operate

## Objective

Operate and support the architecture.

## Activities

- Monitor services
- Manage incidents
- Perform maintenance
- Measure performance
- Review operational metrics

## Outputs

- Operational Dashboards
- Runbooks
- Service Reports
- Operational KPIs

## Decision Gate

Operational teams formally accept ownership.

---

# Step 8 — Govern

## Objective

Ensure long-term architectural consistency.

## Activities

- Review compliance
- Review standards
- Assess risks
- Manage exceptions
- Conduct architecture reviews

## Outputs

- Compliance Reports
- Review Records
- Exception Register
- Updated Standards

## Decision Gate

Architecture remains aligned with business objectives.

---

# Step 9 — Optimize

## Objective

Continuously improve the architecture.

## Activities

- Analyze metrics
- Review lessons learned
- Improve automation
- Modernize technologies
- Reduce operational complexity

## Outputs

- Optimization Roadmap
- Improvement Backlog
- Updated Architecture

## Decision Gate

Improvement opportunities become inputs for the next lifecycle.

---

# Choosing the Right ENAF Scope

Not every project requires the complete ENAF lifecycle.

The framework should be scaled according to the complexity and impact of the initiative.

| Project | Recommended Lifecycle |
|----------|----------------------|
| New Branch Office | Current State → Architecture → Implementation |
| Firewall Refresh | Current State → Architecture → Implementation |
| SD-WAN Deployment | Current State → Target State → Architecture → Roadmap → Implementation |
| Cloud Migration | Full Lifecycle |
| Zero Trust Program | Full Lifecycle |
| Enterprise Modernization | Full Lifecycle |
| Network Optimization | Operations → Governance → Optimization |

---

# Roles and Responsibilities

Successful architecture requires collaboration across multiple teams.

| Role | Primary Responsibility |
|------|-------------------------|
| Executive Sponsor | Business direction and funding |
| Enterprise Architect | Overall architecture governance |
| Network Architect | Network architecture and connectivity |
| Security Architect | Security architecture |
| Cloud Architect | Cloud architecture |
| Engineering Teams | Implementation |
| Operations Teams | Service operations |
| Architecture Review Board | Governance and approvals |

---

# Typical Governance Checkpoints

Each major stage should conclude with a governance review.

Typical checkpoints include:

- Business Approval
- Current State Validation
- Target State Approval
- Architecture Approval
- Roadmap Approval
- Implementation Validation
- Operational Acceptance
- Optimization Review

These checkpoints reduce project risk and improve decision quality.

---

# Common Mistakes

Organizations often encounter similar challenges during transformation.

Common mistakes include:

- Starting with technology instead of business requirements
- Skipping the current state assessment
- Designing without standards
- Ignoring governance
- Implementing without automation
- Delaying documentation
- Failing to involve operations early
- Treating architecture as a one-time activity

Avoiding these mistakes significantly improves project outcomes.

---

# Success Checklist

Before closing an initiative, verify that:

- Business objectives have been achieved
- Architecture has been approved
- Security requirements have been validated
- Documentation is complete
- Monitoring is operational
- Operational teams have accepted ownership
- Lessons learned have been documented
- Improvement opportunities have been identified

---

## Summary

ENAF provides a practical and repeatable methodology for enterprise network architecture.

By following the lifecycle, producing the expected deliverables, and applying governance throughout the transformation journey, organizations can consistently deliver secure, resilient, scalable, and business-aligned network architectures.

The framework is designed to support organizations of all sizes while remaining flexible enough to adapt to different technologies, operating models, and business priorities.

---

## Related Documents

- 04-Architecture-Lifecycle.md
- 06-Governance-Model.md
- 07-Architecture-Deliverables.md
