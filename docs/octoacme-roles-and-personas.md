# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

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

## UX/UI Designer or User Researcher

### Role Summary
UX/UI Designers and User Researchers translate customer needs into usable product experiences and clear interaction patterns. They ensure the solution is understandable, accessible, and aligned to user goals.

### Responsibilities
- Conduct user research, interviews, usability testing, and feedback synthesis
- Define personas, journeys, and interaction flows
- Collaborate on wireframes, mockups, and design review
- Validate that user experience decisions support the product goals and acceptance criteria
- Identify usability risks early and propose design mitigation

### Key decisions and accountability
- Own design quality, accessibility, and user-centered decision-making within scoped product areas
- Partner with Product to confirm problem framing and with Developers to ensure feasibility and implementation fidelity
- Escalate major trade-offs that affect user experience or strategic goals to Product and PM

### Typical Communication
- Product discovery meetings and design reviews
- Usability testing summaries and design feedback loops
- Design specs, mocks, and interaction notes shared in PRs or design docs

### How this role interacts with existing roles
- With Product Managers: aligns on user needs, opportunity areas, and success metrics
- With Developers: provides UX specs and validates implementation against intended behavior
- With Project Managers: contributes to scope, sequencing, and milestone planning for design-dependent work
- With QA: helps define usability and accessibility acceptance checks

---

## QA / Quality Engineer

### Role Summary
QA and Quality Engineers protect product quality by validating that the delivered solution meets requirements, behaves reliably, and is ready for release.

### Responsibilities
- Define and execute test plans, regression suites, and acceptance checks
- Review requirements and acceptance criteria for clarity and testability
- Work with Developers to reproduce defects and verify fixes
- Support release-readiness validation, smoke tests, and post-deployment checks
- Identify quality risks, operational concerns, and gaps in observability

### Key decisions and accountability
- Own quality validation strategy for the feature or release area
- Confirm whether a change is ready for handoff to QA, staging, or production
- Escalate unresolved defects, release risks, or unclear acceptance criteria to Product and PM

### Typical Communication
- Test plans, release checklists, and bug triage discussions
- QA sign-off during sprint reviews and pre-release readiness reviews
- Defect tracking and verification notes in the project board or issue tracker

### How this role interacts with existing roles
- With Product Managers: aligns on measurable outcomes and acceptance criteria
- With Developers: partners on testability, defect triage, and validation of fixes
- With Project Managers: supports schedule and release-risk visibility
- With Stakeholders: communicates quality confidence and known limitations for decision-making

---

## Tech Lead / Architect

### Role Summary
A Tech Lead or Architect guides technical direction, design trade-offs, and implementation quality across the delivery team. They ensure the solution remains maintainable, scalable, and aligned with long-term platform goals.

### Responsibilities
- Define architectural patterns, technical constraints, and integration points
- Review design decisions and provide technical guidance for implementation
- Identify technical debt, platform risks, and cross-team dependencies
- Support estimation and sequencing for complex or high-risk work
- Mentor developers and support decision quality in code review and design discussions

### Key decisions and accountability
- Own technical standards and architecture decisions for a solution or domain
- Recommend go/no-go on design choices that affect risk, performance, or reuse
- Escalate platform or dependency risks that could affect scope, timeline, or reliability

### Typical Communication
- Architecture discussions, design reviews, and technical decision records
- Risk updates to PMs and stakeholders when technical complexity changes
- Dependency and integration planning with cross-functional teams

### How this role interacts with existing roles
- With Product Managers: translates product intent into feasible technical decisions and trade-offs
- With Developers: coaches implementation standards, reviews solutions, and resolves technical ambiguity
- With Project Managers: informs schedule, staffing, and dependency planning
- With QA and Operations: aligns on testability, deployment readiness, and monitoring needs

---

## DevOps / Platform Engineer

### Role Summary
DevOps or Platform Engineers build and maintain the delivery foundations that enable reliable build, deployment, and runtime operations. They support stable team workflows and production readiness.

### Responsibilities
- Manage CI/CD pipelines, environment provisioning, deployment workflows, and automation
- Support monitoring, logging, alerting, and operational health across environments
- Define environment standards, release readiness checks, and rollback practices
- Partner with Developers and QA to improve developer experience and release confidence
- Help identify infrastructure and security risks tied to deployment or platform reliability

### Key decisions and accountability
- Own platform reliability and delivery automation for the project or service area
- Decide on environment and deployment standards within agreed team guardrails
- Escalate operational or platform risks that impact delivery or production stability

### Typical Communication
- Deployment coordination, release checklists, and incident response channels
- Platform health discussions and improvements to automation and observability
- Operational readiness input during planning and release reviews

### How this role interacts with existing roles
- With Developers: supports build, release, and environment needs for efficient delivery
- With QA: aligns on staging environments, smoke testing, and validation workflows
- With Project Managers: advises on release windows, deployment dependencies, and operational risk
- With Security/Privacy: coordinates controls, access patterns, and auditability requirements

---

## Security / Privacy Lead

### Role Summary
Security and Privacy Leads ensure that projects comply with policy, reduce risk, and protect user and company data throughout the lifecycle.

### Responsibilities
- Review requirements and designs for security and privacy implications
- Define security controls, risk mitigations, and compliance expectations
- Support threat modeling, access review, data handling decisions, and privacy impact assessment
- Advise on incident handling, escalation paths, and remediation prioritization
- Align project needs with organizational standards and policy requirements

### Key decisions and accountability
- Own security and privacy risk review for the initiative within the agreed governance model
- Determine when a risk requires escalation, additional controls, or hold/review before release
- Partner with Product and PM to balance customer value with acceptable risk levels

### Typical Communication
- Security review meetings, risk assessments, and policy updates
- Privacy and compliance checkpoints before release or data handling changes
- Escalation communication during incidents or high-risk findings

### How this role interacts with existing roles
- With Product Managers: influences priority trade-offs and acceptable risk thresholds
- With Developers and Tech Leads: reviews implementation choices and secure coding patterns
- With Project Managers: provides risk visibility and escalation needs for delivery decisions
- With Stakeholders and Sponsors: communicates material risk, regulatory impacts, and governance decisions

---

## Business Sponsor / Executive Stakeholder

### Role Summary
Business Sponsors and Executive Stakeholders provide strategic direction, funding, and decision-making support for the initiative. They help ensure the work remains aligned with business priorities and organizational value.

### Responsibilities
- Clarify strategic goals, investment priorities, and desired outcomes
- Resolve escalations, trade-offs, and cross-functional conflicts affecting scope or delivery
- Sponsor key milestones, stakeholder alignment, and executive communication
- Confirm success measures and review business impact after delivery

### Key decisions and accountability
- Own executive sponsorship and strategic prioritization for the initiative
- Make decisions on major trade-offs when business impact, budget, or risk require executive input
- Escalate or unblock dependencies that cross team or organizational boundaries

### Typical Communication
- Weekly or milestone status updates, steering committee check-ins, and decision forums
- Business impact reviews and stakeholder communications
- Escalations for major risks, delays, or strategic changes

### How this role interacts with existing roles
- With Product Managers: aligns on strategy, priority, and outcome definition
- With Project Managers: receives status and escalations, supports decision-making on cross-functional issues
- With Developers, QA, and Tech Leads: focuses on delivery health and risk rather than task execution
- With Security and Risk stakeholders: supports governance decisions when risk or compliance issues affect business impact

---

## Role combinations and tailoring

Not every project requires every role listed above. Small teams may combine responsibilities—for example, one person may serve as both Product Manager and Business Sponsor, or a developer may also support QA or DevOps responsibilities. The key is to define ownership clearly, document who is accountable for decisions, and adapt the operating model to the size and complexity of the work.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- These roles are intended to provide a shared vocabulary for planning, delivery, risk management, and stakeholder communication.
