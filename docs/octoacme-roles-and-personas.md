# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. The goal is to clarify ownership and reduce ambiguity in cross-functional delivery so planning, execution, release, and stakeholder communication have clear accountable owners.

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

## Security / Compliance Lead

### Role Summary
The Security / Compliance Lead ensures delivery plans, architecture, and releases meet security and compliance expectations. They make security risks visible early so the team can address them without delaying execution late in the project lifecycle.

### Responsibilities
- Define security and compliance requirements for the project
- Review solution designs, threat areas, and release readiness for security risks
- Partner with Developers and QA to ensure security controls and validation are included in delivery plans
- Track remediation of security findings, audit actions, and compliance obligations
- Escalate unresolved high-risk issues that could affect customer trust, legal obligations, or production safety

### Goals
- Reduce security and compliance risk before release
- Improve delivery quality by identifying issues early in planning and execution
- Ensure security decisions and exceptions have clear ownership and documentation

### Key Interactions
- Project Manager: aligns security milestones, risks, and escalations with the project plan
- Product Manager: clarifies regulatory, customer, or policy requirements that affect scope and priorities
- Developers: reviews implementation approaches, mitigations, and secure coding considerations
- QA Lead / QA: confirms security validation is included in test strategy and release readiness checks
- Stakeholders: communicates material risks, required approvals, and any compliance impacts

### Decision Rights & Escalation
- Approves security readiness or documents exceptions that require explicit acceptance
- Can block or escalate releases that do not meet critical security or compliance requirements
- Escalation path: delivery team -> Project Manager -> Product Manager / Sponsor -> Security leadership or compliance owner for unresolved critical risks

### Typical Communication
- Security reviews, risk assessments, and mitigation plans
- Release readiness sign-off notes and exception tracking
- Incident or audit follow-ups with delivery leads and stakeholders

---

## QA Lead

### Role Summary
The QA Lead owns the quality strategy for the project and ensures acceptance criteria, test coverage, and release readiness standards are consistently applied across the delivery lifecycle.

### Responsibilities
- Define the test strategy, quality gates, and validation approach for the project
- Coordinate test planning across functional, integration, regression, and release validation activities
- Partner with Developers to improve testability, defect prevention, and definition of done
- Track defects, quality trends, and unresolved risks that affect delivery confidence
- Confirm acceptance criteria are objectively testable and validated before release

### Goals
- Increase confidence that delivered work meets quality expectations
- Reduce escaped defects and late-cycle rework
- Improve execution quality through repeatable validation and clear release criteria

### Key Interactions
- Project Manager: aligns test milestones, defect risk, and readiness reporting with the overall plan
- Product Manager: verifies acceptance criteria and expected user outcomes are testable and complete
- Developers: collaborates on test design, defect triage, and remediation priorities
- Security / Compliance Lead: coordinates security validation and risk-based testing where needed
- Stakeholders: communicates quality status, release confidence, and significant open issues

### Decision Rights & Escalation
- Recommends whether a feature, milestone, or release is ready based on agreed quality gates
- Can escalate when defect severity, test gaps, or validation failures create unacceptable delivery risk
- Escalation path: QA / delivery team -> Project Manager -> Product Manager and engineering leadership -> Sponsor if release trade-off decisions are required

### Typical Communication
- Test plans, defect triage notes, and quality dashboards
- Readiness updates during sprint reviews and release checkpoints
- Acceptance validation results shared with product and project leads

---

## Technical Architect

### Role Summary
The Technical Architect provides end-to-end solution guidance so the team can make sound technical decisions, manage dependencies, and maintain architectural consistency as delivery scales.

### Responsibilities
- Define and review architecture decisions, technical patterns, and system boundaries
- Identify cross-team dependencies, integration risks, and non-functional requirements
- Guide trade-off decisions involving scalability, reliability, maintainability, and security
- Support Developers with implementation direction for complex or high-risk work
- Ensure major technical decisions are documented and communicated to delivery leads

### Goals
- Improve execution quality through clear technical direction and early trade-off analysis
- Reduce rework caused by unclear architecture or unmanaged dependencies
- Support predictable delivery by aligning design decisions with project constraints

### Key Interactions
- Project Manager: surfaces technical dependencies, sequencing risks, and design decisions that affect the plan
- Product Manager: translates product goals into feasible technical options and trade-offs
- Developers: provides implementation guidance, reviews designs, and supports problem solving
- QA Lead: aligns architecture decisions with test strategy, environments, and quality risks
- Stakeholders: explains major technical constraints, decisions, and impacts in accessible terms

### Decision Rights & Escalation
- Recommends or approves target architecture patterns and key technical trade-offs within the project scope
- Can escalate when delivery commitments conflict with critical architectural, reliability, or security constraints
- Escalation path: Developers / delivery lead -> Technical Architect -> Project Manager and Product Manager -> engineering leadership for unresolved strategic trade-offs

### Typical Communication
- Architecture diagrams, design reviews, and decision records
- Dependency and integration planning sessions
- Technical risk updates during planning and execution reviews

---

## Release Manager / Deployment Lead

### Role Summary
The Release Manager / Deployment Lead coordinates release preparation and deployment execution so changes move to production safely, predictably, and with clear communication before, during, and after release.

### Responsibilities
- Own the release plan, deployment checklist, and release coordination activities
- Confirm pre-release requirements such as approvals, smoke tests, rollback plans, and stakeholder notifications
- Coordinate deployment windows, environment readiness, and post-deploy verification
- Manage release communications, release notes, and incident handoffs if deployment issues occur
- Track release blockers and escalate readiness risks before production impact occurs

### Goals
- Reduce deployment risk and improve release consistency
- Improve execution quality through clear readiness criteria and rollback planning
- Ensure production releases have accountable coordination and timely communication

### Key Interactions
- Project Manager: aligns release milestones, blockers, and cutover timing with the delivery plan
- Product Manager: confirms release scope, timing, and customer-facing communications
- Developers: coordinates deployment steps, rollback support, and post-release fixes if needed
- QA Lead / QA: verifies smoke tests, acceptance validation, and release confidence inputs
- Stakeholders: shares release schedules, status updates, and incident communications

### Decision Rights & Escalation
- Recommends go / no-go readiness based on checklist completion, validation results, and open risk
- Can pause or escalate a deployment when readiness criteria, rollback plans, or production safety checks are incomplete
- Escalation path: release team -> Project Manager -> Product Manager and engineering leadership -> incident or sponsor escalation for critical release risk

### Typical Communication
- Release calendars, deployment checklists, and go / no-go summaries
- Stakeholder release announcements and status updates
- Post-release verification notes and incident follow-up actions

---

## Customer Success / Stakeholder Liaison

### Role Summary
The Customer Success / Stakeholder Liaison represents customer and business context throughout delivery, helping the team maintain alignment on expectations, communication, adoption needs, and operational readiness.

### Responsibilities
- Gather and synthesize customer feedback, stakeholder concerns, and adoption requirements
- Clarify communication needs for internal teams such as support, sales, and operations
- Partner with Product Managers to ensure delivery decisions reflect customer outcomes and readiness impacts
- Help coordinate launch messaging, enablement, and follow-up actions after release
- Escalate gaps in expectations, communication, or stakeholder alignment before they become delivery blockers

### Goals
- Improve project outcomes by keeping customer and stakeholder needs visible throughout execution
- Reduce ambiguity in ownership for stakeholder communications and follow-through
- Increase adoption readiness and confidence around releases and project milestones

### Key Interactions
- Project Manager: aligns stakeholder updates, risks, and action owners with the project cadence
- Product Manager: shares customer insights, validates expected outcomes, and informs prioritization trade-offs
- Developers: provides context on customer workflows, support issues, and usability concerns
- QA Lead: highlights customer-critical scenarios that should be included in validation
- Stakeholders: maintains two-way communication, captures decisions, and ensures follow-up on open questions

### Decision Rights & Escalation
- Recommends stakeholder communication plans, readiness actions, and customer follow-up priorities
- Can escalate when customer commitments, launch readiness, or stakeholder expectations are at risk
- Escalation path: stakeholder liaison -> Project Manager -> Product Manager / Sponsor -> executive stakeholder owners for unresolved external alignment issues

### Typical Communication
- Stakeholder briefings, customer-readiness notes, and feedback summaries
- Launch coordination updates with support, sales, and operations
- Follow-up actions and decision logs for open stakeholder questions

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Use the expanded set of personas to clarify ownership, reduce ambiguity, and improve accountability across cross-functional delivery work.
