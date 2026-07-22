# NorthStar Case Study

The NorthStar case study demonstrates how the Current State stage is applied within a realistic enterprise transformation program.

Rather than presenting theory alone, this case study illustrates how Enterprise Architects gather information, analyze the existing environment, identify risks, and establish a trusted architectural baseline before designing the future state.

The purpose is not to provide a complete solution, but to demonstrate how the ENAF methodology is applied in practice.

---

# Company Overview

NorthStar Retail Group is a global fashion retailer operating across Europe, North America, Asia, and Australia.

The company manages:

- Over 2,000 retail stores
- Regional distribution centers
- Global e-commerce platforms
- Corporate offices
- Manufacturing partners
- Public cloud platforms
- Multiple data centers

During the last decade, NorthStar expanded rapidly through acquisitions, resulting in a diverse technology landscape with varying standards, duplicated platforms, and inconsistent governance.

To remain competitive, the executive leadership launched a multi-year Enterprise Transformation Program focused on modernization, cloud adoption, security, operational efficiency, and business agility.

Before defining the future architecture, the Enterprise Architecture team was asked a simple question:

> **"Where are we today?"**

Answering that question became the objective of the Current State stage.

---

# The Engagement Begins

The Enterprise Architecture team starts by meeting key business and technology stakeholders.

Instead of discussing future technologies or solution designs, the team focuses on understanding the organization as it currently operates.

Over several weeks, architects conduct interviews, workshops, document reviews, and technical assessments across the enterprise.

Their objective is to establish facts rather than assumptions.

---

# Assessing the Enterprise

The assessment is organized using the ENAF Enterprise Assessment Domains.

## Business

The architects identify NorthStar's core business capabilities, strategic objectives, operating model, and organizational structure.

They discover that many business capabilities are duplicated across regions following previous acquisitions.

Several departments perform similar functions using different operating models.

---

## Applications

More than 600 business applications are identified.

Many applications provide overlapping functionality.

Several critical systems have reached end-of-life but remain in production because of business dependencies.

Application ownership is inconsistent, and integration documentation is incomplete.

---

## Infrastructure

Infrastructure assessments reveal a mixture of traditional data centers, virtualized environments, and public cloud platforms.

Hardware standards vary between regions.

Disaster recovery capabilities differ significantly across business units.

---

## Network

The global network consists of MPLS, SD-WAN, Internet VPN, regional hubs, cloud connectivity, and multiple security platforms.

Different regions have adopted different network standards.

Network visibility and documentation are inconsistent.

Several critical dependencies are discovered during workshops.

---

## Cloud

NorthStar operates workloads across Microsoft Azure and AWS.

Cloud adoption has accelerated without consistent governance.

Different business units have implemented their own landing zones, identity models, and networking approaches.

Cloud costs are increasing, while operational visibility remains limited.

---

## Security

Security controls differ across acquired companies.

Identity platforms are fragmented.

Network segmentation is inconsistent.

Several legacy authentication mechanisms remain in use.

Compliance requirements are understood but implemented differently across regions.

---

## Operations

Monitoring platforms, ITSM processes, and operational procedures vary significantly.

Automation maturity differs between teams.

Incident management is well established, but proactive monitoring remains inconsistent.

---

## Governance

Architecture governance exists but is not applied consistently.

Technology standards differ between business units.

Decision records are difficult to locate, making previous architectural decisions challenging to understand.

---

# Key Findings

After completing the assessment, the Enterprise Architecture team identifies several common themes.

## Strengths

- Strong executive sponsorship
- Experienced engineering teams
- Mature cloud adoption in several business units
- Well-established global operations
- Clear business transformation objectives

---

## Challenges

- Technology duplication following acquisitions
- Inconsistent architecture standards
- Legacy applications and infrastructure
- Fragmented identity platforms
- Multiple cloud operating models
- Limited enterprise-wide visibility
- Technical debt across several domains

---

# Current State Baseline

The findings are consolidated into the Current State Assessment.

This architectural baseline provides a trusted view of the enterprise across all assessment domains.

For the first time, executives, architects, and engineering teams share a common understanding of the organization's current environment.

The baseline becomes the foundation for all future architecture decisions.

---

# Decision Gate

The Enterprise Architecture team presents the assessment to the Architecture Governance Board.

The Board reviews:

- Assessment findings
- Risks
- Technical debt
- Domain assessments
- Current State deliverables

Following review, the Board approves **DG-CSA-01** and authorizes the team to begin the Target State stage.

---

# Lessons Learned

The NorthStar case study demonstrates several important principles.

- Architects should understand the current environment before designing the future.
- Decisions should be based on validated information rather than assumptions.
- Every Enterprise Assessment Domain contributes to the architectural baseline.
- Governance provides confidence that the assessment is complete.
- A well-executed Current State Assessment reduces transformation risk and improves the quality of future architecture decisions.

---

# Transition to the Next Stage

With the Current State Assessment approved, the Enterprise Architecture team now understands the organization's existing business and technology landscape.

The next question is no longer:

> **"Where are we today?"**

Instead, the transformation program moves to the next stage of the ENAF lifecycle:

> **"Where do we want to be?"**

The answer begins in the **Target State** stage.
