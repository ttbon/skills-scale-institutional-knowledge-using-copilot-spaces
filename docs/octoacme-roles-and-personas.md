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

## Designer (UX/UI)

### Role Summary
Designers define user experience and interface direction so delivered solutions are usable, accessible, and aligned with product outcomes.

### Responsibilities
- Create and iterate wireframes, flows, mockups, and prototypes
- Partner with Product Managers to translate requirements into user-centered designs
- Collaborate with Developers on implementation feasibility and UX quality
- Define and validate usability and accessibility expectations
- Support QA with expected behavior for UI acceptance and regression checks

### Goals
- Deliver intuitive, accessible user experiences
- Reduce rework caused by unclear UX expectations
- Improve customer adoption and satisfaction

### Typical Communication
- Design reviews and async feedback in PRs/issues
- Planning sessions for scope and UX trade-offs
- Sprint demos and usability feedback sessions

---

## Quality Assurance Lead

### Role Summary
Quality Assurance Leads own testing strategy and quality gates across the lifecycle, ensuring delivered increments meet acceptance criteria and release standards.

### Responsibilities
- Define and maintain test strategy, plans, and quality gates
- Coordinate functional, integration, regression, and smoke testing
- Partner with Product Managers and Developers to refine testable acceptance criteria
- Track defect trends, validate fixes, and communicate release readiness
- Confirm pre-release validation and sign-off criteria are completed

### Goals
- Prevent critical defects from reaching production
- Make release readiness explicit and consistent
- Improve confidence in delivery quality across teams

### Typical Communication
- Test plan reviews during planning
- Ongoing QA status updates during execution
- Release go/no-go input before deployment

---

## Subject Matter Expert (SME)

### Role Summary
Subject Matter Experts provide domain knowledge, regulatory guidance, and solution validation for complex business and compliance-sensitive decisions.

### Responsibilities
- Clarify domain constraints, terminology, and business rules
- Validate requirements and proposed solutions during planning
- Identify regulatory, legal, or policy considerations early
- Review milestone outputs for domain accuracy
- Support decision-making when trade-offs affect business processes

### Goals
- Ensure solutions are feasible in the real operating context
- Reduce rework from missed domain or compliance requirements
- Improve stakeholder confidence in delivered outcomes

### Typical Communication
- Discovery and planning workshops
- Milestone reviews and decision checkpoints
- Targeted Q&A during execution for requirement clarifications

---

## Cross-Role Interaction Matrix

| Role | Primary Touchpoints | Decision Authority | Dependency Pattern | Typical Handoff |
| --- | --- | --- | --- | --- |
| Developers | Product Managers, Project Managers, Designer, QA Lead, SME | Implementation approach and technical trade-offs | Depend on prioritized backlog, UX specs, and acceptance criteria | Code + technical notes to QA; implementation feedback to PM/PdM |
| Product Managers | Developers, Project Managers, Designer, QA Lead, SME | Scope, priority, acceptance outcomes | Depend on SME validation, delivery estimates, and quality signals | Prioritized backlog and acceptance criteria to delivery team |
| Project Managers | Product Managers, Developers, Designer, QA Lead, SME | Delivery cadence, escalation, and coordination | Depend on team status, risk signals, and milestone readiness | Status updates, action items, and risk escalations to stakeholders |
| Designer (UX/UI) | Product Managers, Developers, QA Lead | UX direction, interaction patterns, accessibility standards | Depend on requirements clarity and technical constraints | Approved designs/prototypes and UX acceptance expectations |
| Quality Assurance Lead | Developers, Product Managers, Project Managers, Designer | Test strategy, quality gates, release readiness recommendation | Depend on build stability, acceptance criteria, and environment readiness | Test results, defect triage, and release validation summary |
| Subject Matter Expert (SME) | Product Managers, Project Managers, Developers, QA Lead | Domain correctness and compliance interpretation | Depend on timely review windows and clear requirement artifacts | Domain validation feedback and compliance constraints |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
