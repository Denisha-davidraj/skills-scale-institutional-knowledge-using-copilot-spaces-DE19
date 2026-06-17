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

## Release Manager

### Role Summary
The Release Manager coordinates release readiness across teams and ensures deployments follow OctoAcme's release checklist, timing, and rollback expectations.

### Responsibilities
- Maintain the release plan, deployment window, and go-live checklist
- Confirm release notes, rollback steps, and post-deploy verification plans are complete
- Consolidate readiness inputs from Developers, QA, the Technical Lead, and the Security Reviewer
- Coordinate release announcements with PM, PdM, and support-facing teams

### Decision Authority / Sign-off
- Recommends go / no-go based on checklist completion, known risks, and rollback readiness
- Signs off that operational release readiness is complete before production deployment proceeds

### Typical Communication & Handoffs
- Partners with the PM on scheduling, stakeholder timing, and escalation decisions
- Works with Developers and QA to confirm acceptance criteria, smoke tests, and deployment steps are complete
- Confirms with the PdM that customer-facing release notes and launch expectations are aligned
- Example handoff: the Release Manager collects readiness confirmation from QA, Technical Lead, and Security Reviewer, then gives the final release-readiness sign-off and coordinates the stakeholder announcement

---

## Technical Lead

### Role Summary
The Technical Lead guides technical direction for the work, helps the team make sound implementation decisions, and keeps delivery aligned with quality, scalability, and maintainability standards.

### Responsibilities
- Lead technical design decisions and review significant implementation trade-offs
- Clarify technical scope, dependencies, and sequencing during planning
- Coach Developers on architecture, code quality, and testability
- Surface technical risks early and propose mitigation or rollback options

### Decision Authority / Sign-off
- Approves major technical design choices and implementation approach within the agreed scope
- Signs off that the solution is technically ready for release handoff when architecture, observability, and supportability expectations are met

### Typical Communication & Handoffs
- Works closely with Developers during design, implementation, and code review
- Partners with the PM and PdM to explain technical risk, effort, and trade-offs that affect plan or scope
- Coordinates with QA on test strategy for high-risk changes
- Example handoff: the Technical Lead provides the Release Manager with technical readiness input, including outstanding risks, rollback considerations, and any required production monitoring

---

## Security Reviewer

### Role Summary
The Security Reviewer verifies that changes meet OctoAcme security expectations before release and that security risks are documented, mitigated, or escalated appropriately.

### Responsibilities
- Review high-risk changes for security concerns and validate remediation plans
- Verify security scans, dependency checks, and relevant access-control considerations
- Document open security risks and recommend mitigations or compensating controls
- Escalate suspected incidents or critical findings through the security incident path

### Decision Authority / Sign-off
- Provides security sign-off for releases or features that require formal review
- Can block release readiness when critical vulnerabilities or unresolved security risks remain

### Typical Communication & Handoffs
- Works with Developers and the Technical Lead to review findings and mitigation options
- Updates the PM and Release Manager on security risks that affect timeline or launch readiness
- Escalates critical issues to Security on-call and provides inputs for incident communications
- Example handoff: when a severe issue is discovered, the Security Reviewer provides the triage summary and recommended actions to the PM, who coordinates broader stakeholder communication using the incident template

---

## Customer Success Liaison

### Role Summary
The Customer Success Liaison brings customer context into delivery decisions and helps ensure customers, support teams, and stakeholders are prepared for changes that affect adoption or satisfaction.

### Responsibilities
- Gather recurring customer feedback, support themes, and adoption risks
- Highlight customer-facing impacts, training needs, and communication considerations
- Coordinate launch messaging, enablement, and follow-up feedback collection for major releases
- Help identify customers or segments to include in validation or rollout feedback loops

### Decision Authority / Sign-off
- Recommends customer readiness actions and communication needs before launch
- Signs off on customer communication inputs when a release requires coordinated outreach or support preparation

### Typical Communication & Handoffs
- Works with the PdM to translate customer feedback into problem statements, backlog inputs, and prioritization discussions
- Coordinates with the PM on rollout timing, support readiness, and stakeholder communications
- Shares release context with Developers and QA when customer workflows or usability concerns require extra validation
- Example handoff: customer feedback is summarized by the Customer Success Liaison, reviewed with the PdM, and then converted into prioritized backlog items or release follow-ups with PM visibility

---

## Data Analyst

### Role Summary
The Data Analyst helps the team define, instrument, and validate success metrics so OctoAcme decisions remain grounded in evidence before and after release.

### Responsibilities
- Define measurable success criteria with the PdM and PM
- Validate that required tracking, dashboards, and reporting are ready before launch
- Analyze delivery, adoption, quality, or business metrics after release
- Provide insight on trends, experiment results, and unintended impacts

### Decision Authority / Sign-off
- Signs off that agreed success metrics are defined and that the team has a clear validation approach for post-release measurement
- Recommends whether follow-up analysis supports scaling, iteration, or rollback of a change

### Typical Communication & Handoffs
- Partners with the PdM on outcome definition and with Developers on instrumentation needs
- Supports the PM with status inputs when success metrics or quality trends affect stakeholder decisions
- Shares findings with stakeholders to validate whether expected outcomes were achieved
- Example handoff: the PdM defines target outcomes, the Data Analyst validates how those outcomes will be measured, and post-release results are fed back into prioritization and retrospective decisions

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

These added personas complement the core roles by making release ownership, technical decision-making, security review, customer feedback loops, and metric validation more explicit across the OctoAcme delivery lifecycle.
