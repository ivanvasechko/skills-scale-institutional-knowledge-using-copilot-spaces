# OctoAcme Project Management Docs

This folder is the onboarding entry point for OctoAcme's project management process. The overall model is customer-first, iterative, and data-informed: teams start by defining the problem, desired outcome, success metrics, stakeholders, and initial risks, then use that shared context to decide whether work is ready to move from initiation into planning. Each project has clear ownership, with a named Project Manager and Product Lead guiding delivery and decision-making.

Once work is approved, planning turns the initiative into a prioritized backlog, milestone map, and release plan. The planning docs emphasize shippable increments, explicit acceptance criteria, a documented Definition of Done, realistic team capacity, and early identification of dependencies and integration points. Core artifacts include the project one-pager, roadmap and release plan, sprint or iteration backlog, acceptance criteria, risk register, and retrospective action items.

Execution is managed through a regular team rhythm, project board workflow, and lightweight reporting. Teams track work from backlog through review, QA, and done; they use small pull requests, CI validation, automated tests, security scanning, manual QA when needed, and milestone demos to keep delivery reliable. Progress is measured against delivery signals such as velocity, burndown, and the success metrics defined during initiation, while risks and blockers are reviewed continuously rather than only at the end of a project.

Communication and learning are built into the lifecycle. Stakeholders receive regular updates through weekly or milestone-based status reporting, while PM and Product Manager alignment, delivery syncs, standups, and demos help the team make timely decisions. Escalations move from team-level triage to the PM, Product Lead, and sponsor when business impact grows, with security incidents following the security incident runbook and Security on-call path. Releases require release notes, rollback planning, smoke testing, deployment verification, and clear announcements, and every sprint, release, or major milestone should end with a retrospective that turns lessons learned into a small set of owned improvement actions.

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

## Core Roles and Ownership

- **Project Manager (PM):** coordinates schedules, delivery plans, risks, dependencies, status reporting, meeting cadence, and cross-team communication.
- **Product Manager (PdM):** defines the problem, outcomes, and success metrics; prioritizes the roadmap and backlog; and guides trade-off decisions based on customer and business value.
- **Developers:** design, build, test, review, and document the solution; help estimate work; and surface technical risks and mitigations.
- **QA / Testing:** validates quality and acceptance criteria through planned test coverage, integration checks, smoke testing for critical flows, and manual acceptance testing when needed.
- **Stakeholders / Sponsors:** provide business context, input, approvals, and escalation support at key decision points and milestone reviews.
