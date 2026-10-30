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

## Engineering Managers

### Role Summary
Engineering Managers provide operational leadership for the delivery team, helping maintain technical health, team capacity, and execution quality across the project lifecycle.

### Responsibilities
- Align engineering work with roadmap priorities and delivery commitments
- Support team planning, staffing, and workload balancing
- Remove blockers and improve delivery flow for engineers
- Maintain coaching, quality expectations, and technical standards
- Partner with PM and Product on trade-offs, resourcing, and risk

### Goals
- Improve delivery predictability and team health
- Maintain consistent execution quality and technical rigor
- Enable engineers to focus on high-value work without avoidable friction

### Typical Communication
- Team planning and capacity discussions
- Weekly engineering status updates
- Escalations around staffing, roadmap conflicts, and technical risks

### Interactions with other roles
- Works with Product Managers on prioritization and sequencing
- Coordinates with Project Managers on milestones, dependencies, and delivery status
- Supports Developers with technical planning, decision-making, and engineering leadership
- Escalates cross-team issues when delivery capacity or technical constraints affect commitments

---

## Security and Compliance Lead

### Role Summary
The Security and Compliance Lead ensures that project work meets required security, privacy, and regulatory standards throughout planning, build, and release.

### Responsibilities
- Review architecture, data handling, and feature designs for risk
- Define security requirements, controls, and review checkpoints
- Coordinate compliance validation, audits, and remediation follow-up
- Help assess and mitigate security issues and incident impacts
- Partner with engineering and stakeholders on risk acceptance decisions

### Goals
- Reduce security and compliance exposure
- Ensure controls are built in early rather than bolted on late
- Support safe, policy-aligned release decisions

### Typical Communication
- Design review checkpoints and security triage meetings
- Risk escalation and incident communication
- Release-readiness discussions with PM, engineering, and leadership

### Interactions with other roles
- Advises Product and PM on security constraints, requirements, and release gating
- Reviews implementation risks with Developers and Engineering Managers
- Provides escalation path for critical vulnerabilities or compliance concerns
- Collaborates with Stakeholders and Business Owners on risk tolerance and approval needs

---

## QA Lead

### Role Summary
The QA Lead ensures the team validates quality, readiness, and acceptance across features, fixes, and releases. They maintain test strategy and quality checks aligned to delivery goals.

### Responsibilities
- Define test strategy, quality gates, and acceptance validation plans
- Prioritize test coverage for critical user journeys and high-risk changes
- Coordinate manual QA, regression testing, and release validation
- Partner with Developers and Product on defect triage and release readiness
- Track quality trends and support continuous improvement in testing practices

### Goals
- Catch defects before release and reduce production issues
- Ensure quality expectations align with product requirements
- Improve confidence in milestone and release decisions

### Typical Communication
- Sprint planning and acceptance review meetings
- Bug triage and quality risk updates
- Release readiness sign-off and post-release feedback loops

### Interactions with other roles
- Works closely with Product Managers to validate acceptance criteria
- Coordinates with Developers on testability, automation, and defect ownership
- Supports Project Managers in risk communication and release timing decisions
- Provides evidence for stakeholder confidence and operational readiness

---

## Data and Analytics Lead

### Role Summary
The Data and Analytics Lead provides measurement, instrumentation, and insight support so the team can validate impact, monitor adoption, and improve decisions based on evidence.

### Responsibilities
- Define success metrics, dashboards, and measurement plans
- Identify required instrumentation, events, and reporting for product changes
- Help assess whether outcomes are being achieved and where further iteration is needed
- Partner with Product and PM on reporting needs and stakeholder updates
- Support analysis for release decisions, experiments, and incident follow-up

### Goals
- Ensure product decisions are grounded in measurable outcomes
- Reduce uncertainty in roadmap and release trade-offs
- Improve visibility into operational and user-impact signals

### Typical Communication
- Metrics reviews and milestone check-ins
- Reporting for stakeholder briefings and leadership syncs
- Analytics-driven discussions during roadmap and release planning

### Interactions with other roles
- Helps Product Managers define and track success metrics
- Provides PMs with evidence for timeline and scope decisions
- Works with Developers to validate instrumentation, analysis quality, and data correctness
- Supports QA and Release Managers by monitoring post-deploy health and feature impact

---

## Release Manager

### Role Summary
The Release Manager coordinates readiness, rollout, and operational communication for production changes so releases happen with minimal risk and clear accountability.

### Responsibilities
- Coordinate deployment windows, release checklists, and readiness reviews
- Confirm pre-release criteria, rollback plans, and stakeholder communications
- Monitor rollout progress and support incident handling if issues arise
- Maintain release notes, operational updates, and post-release verification
- Partner with engineering, QA, and stakeholders on go/no-go decisions

### Goals
- Reduce release risk and deployment surprises
- Improve operational clarity and stakeholder confidence
- Promote repeatable, traceable release practices

### Typical Communication
- Release readiness reviews and deployment briefings
- Post-release verification updates and incident notifications
- Stakeholder comms tied to launch timing or operational impact

### Interactions with other roles
- Works with Project Managers on timing, dependencies, and communications
- Coordinates with QA Lead and Engineering Managers on sign-off and rollback criteria
- Aligns with Product Managers on launch messaging and release priorities
- Supports Security and Compliance Lead for sensitive or regulated deployment controls

---

## Customer and Stakeholder Representative / Business Owner

### Role Summary
The Customer and Stakeholder Representative, or Business Owner, represents the business need and helps ensure the delivered solution aligns with customer value, priority, and organizational goals.

### Responsibilities
- Clarify user needs, business context, and expected outcomes
- Review priorities, trade-offs, and stakeholder concerns
- Approve scope decisions, milestones, and business readiness
- Provide feedback on usability, customer impact, and adoption concerns
- Support communication between delivery teams and broader stakeholders

### Goals
- Ensure the solution delivers meaningful customer and business value
- Support timely decisions and clear accountability for outcomes
- Maintain alignment between delivery teams and stakeholder expectations

### Typical Communication
- Weekly or milestone-based status reviews
- Decision and approval checkpoints
- Escalation of business impact, customer concerns, or priority changes

### Interactions with other roles
- Partners with Product Managers to define customer value and success metrics
- Provides business context and approval support to Project Managers and Release Managers
- Reviews risks and trade-offs raised by Engineering, QA, and Security leads
- Helps align release readiness, adoption plans, and stakeholder communications

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- These additional roles help define ownership boundaries, decision-making authority, and handoff expectations across planning, execution, release, and operational support.
- The goal is not to duplicate existing responsibilities, but to clarify where accountability belongs as project complexity grows and cross-functional collaboration becomes more important.

---

## Ownership and Collaboration Model

As project complexity increases, the team should keep these principles in mind:
- Product and business stakeholders define value, priorities, and success measures.
- Project Managers coordinate delivery, dependencies, and communication.
- Engineering Managers support execution quality, staffing, and technical leadership.
- QA, Security, and Data roles provide quality and risk validation across the lifecycle.
- Release Managers and Business Owners help sustain safe, aligned, and value-driven deployment decisions.

This structure improves accountability by making handoffs explicit, clarifying decision authority, and providing clear escalation paths across roles.

