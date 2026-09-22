# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. A person may hold more than one persona on smaller projects; teams should make ownership and handoffs explicit when roles are combined.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Engineering Leads / Tech Leads

### Role Summary
Engineering Leads or Tech Leads provide technical direction and help the team make sound architecture and implementation decisions.

### Responsibilities
- Establish technical approach, architecture guidance, and engineering standards
- Review technical risks, dependencies, and trade-offs
- Support estimation and break work into implementable increments
- Facilitate technical design and code reviews
- Coach Developers and identify maintainability or scalability concerns

### Interaction with Existing Roles
- Partner with Product Managers to assess feasibility, sequencing, and technical trade-offs
- Partner with Project Managers to surface technical risks and dependency impacts
- Guide Developers while preserving clear individual ownership
- Collaborate with QA/Testing on testability and quality risks
- Explain technical decisions and implications to Stakeholders in accessible terms

---

## UX/UI Designers and Researchers

### Role Summary
UX/UI Designers and Researchers represent user needs and help teams validate that proposed solutions are usable, accessible, and aligned with real-world workflows.

### Responsibilities
- Conduct or synthesize user research
- Create user flows, wireframes, prototypes, and interaction designs
- Define usability and accessibility considerations
- Validate designs with users and incorporate feedback
- Document design decisions and open questions

### Interaction with Existing Roles
- Work with Product Managers to connect user needs to product outcomes and acceptance criteria
- Work with Developers and Engineering Leads to confirm feasibility and implementation details
- Work with QA/Testing to make usability and accessibility expectations testable
- Provide Project Managers with design dependencies and review milestones
- Incorporate Stakeholder feedback without allowing it to replace validated user evidence

---

## Business Analysts / Product Operations

### Role Summary
Business Analysts and Product Operations partners translate business needs into clear requirements, workflows, decisions, and measurable outcomes.

### Responsibilities
- Document current and future-state workflows
- Clarify requirements, assumptions, constraints, and edge cases
- Facilitate alignment when business needs are ambiguous or conflicting
- Maintain requirement traceability to outcomes and acceptance criteria
- Support backlog refinement and operational readiness

### Interaction with Existing Roles
- Help Product Managers refine problems, scope, and priorities
- Give Developers and QA/Testing a shared understanding of behavior and edge cases
- Help Project Managers track decisions, dependencies, and requirement changes
- Validate business workflows with Stakeholders and identify approval needs

---

## Release Managers / Delivery Leads

### Role Summary
Release Managers or Delivery Leads coordinate release readiness, deployment dependencies, communications, and rollback planning.

### Responsibilities
- Maintain release plans, readiness checklists, and go/no-go inputs
- Coordinate deployment windows and cross-team dependencies
- Confirm release notes, migration steps, smoke tests, and rollback plans
- Track unresolved release risks and escalation decisions
- Coordinate post-release verification and stakeholder announcements

### Interaction with Existing Roles
- Work with Project Managers on milestones, risks, and communications
- Work with Developers and Engineering Leads on deployment and rollback readiness
- Work with QA/Testing on test completion, defects, and smoke-test coverage
- Work with Product Managers on scope, customer impact, and release messaging
- Keep Stakeholders informed about readiness, decisions, and known issues

---

## Site Reliability Engineers / Operations Leads

### Role Summary
Site Reliability Engineers and Operations Leads ensure that solutions are supportable, observable, reliable, and safe to operate in production.

### Responsibilities
- Define production-readiness and observability requirements
- Review capacity, availability, resilience, and operational risks
- Maintain runbooks, alerts, dashboards, and incident procedures
- Support deployment verification and incident coordination
- Feed operational learnings into planning and continuous improvement

### Interaction with Existing Roles
- Work with Developers and Engineering Leads on reliability, performance, and instrumentation
- Work with QA/Testing on resilience and operational test scenarios
- Work with Release Managers on deployment verification and rollback triggers
- Work with Project Managers to track operational dependencies and risks
- Work with Product Managers and Stakeholders to communicate customer impact and service health

---

## Security, Privacy, and Compliance Partners

### Role Summary
Security, Privacy, and Compliance Partners identify control requirements and help the team manage security, privacy, legal, and regulatory risks throughout delivery.

### Responsibilities
- Identify applicable security, privacy, and compliance requirements
- Review designs, data flows, access controls, and threat models
- Define required assessments, approvals, and evidence
- Track findings, mitigations, exceptions, and residual risk
- Advise on incident response and notification obligations when needed

### Interaction with Existing Roles
- Work with Product Managers and Stakeholders to understand regulatory and business obligations
- Work with Developers and Engineering Leads to design and implement controls
- Work with QA/Testing to make security and compliance checks verifiable
- Work with Project Managers to record risks, owners, due dates, and approval gates
- Work with Release Managers to confirm required sign-offs before deployment

---

## Customer Success, Support, and Enablement Representatives

### Role Summary
Customer Success, Support, and Enablement Representatives bring customer impact, service readiness, and feedback into project decisions and releases.

### Responsibilities
- Represent customer workflows, adoption concerns, and support needs
- Review release communications, documentation, training, and known issues
- Prepare support teams and escalation paths for launch
- Capture post-release feedback, recurring issues, and adoption signals
- Share customer insights that inform future backlog decisions

### Interaction with Existing Roles
- Work with Product Managers to validate customer value and prioritize feedback
- Work with Project Managers and Release Managers on readiness and communications
- Work with Developers and QA/Testing to reproduce and prioritize customer-impacting issues
- Work with UX/UI Designers and Researchers to identify usability gaps
- Keep Stakeholders informed about customer readiness and early outcomes

---

## Data and Analytics Partners

### Role Summary
Data and Analytics Partners define how teams will measure outcomes, instrument experiences, and use evidence to guide decisions.

### Responsibilities
- Translate success metrics into measurement plans and instrumentation needs
- Define data quality, reporting, and interpretation requirements
- Establish baselines and support experiment or outcome analysis
- Create dashboards or recurring reports for key signals
- Identify limitations, uncertainty, and privacy considerations in analysis

### Interaction with Existing Roles
- Work with Product Managers to define measurable outcomes and decision thresholds
- Work with Developers and Engineering Leads to plan telemetry and event instrumentation
- Work with Project Managers to track measurement dependencies and milestones
- Work with UX/UI Designers and Researchers to combine behavioral and qualitative evidence
- Help Stakeholders interpret results and decide whether to iterate, scale, or stop

---

## Role Collaboration and Accountability

- At project initiation, the Project Manager and Product Manager should identify which personas are involved and name accountable owners.
- During planning, each persona should record its key deliverables, dependencies, decision rights, and handoffs in the project plan or backlog.
- During execution, risks and unresolved ownership questions should be raised in the project board, standup, or weekly delivery sync.
- Before release, Release Managers, QA/Testing, Operations, Security, and Support should confirm their readiness criteria or explicitly document exceptions.
- After release, Product Managers, Project Managers, Customer Success/Support, Operations, and Data/Analytics should review outcomes and feed actions into the backlog or retrospective.

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Adapt the set of personas to the project; one person may perform multiple roles, but accountability for each decision and deliverable should remain explicit.
