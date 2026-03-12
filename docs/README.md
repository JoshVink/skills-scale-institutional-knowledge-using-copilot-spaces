# OctoAcme Project Management Overview

OctoAcme runs projects with a lightweight, iterative process that moves initiatives from a one‑pager through planning, execution, release, and retrospective. Work is organized on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and backlog items use a consistent template (title, description, acceptance criteria, priority, estimate, owner). Planning includes a kickoff, prioritized backlog with estimates, a clear Definition of Done, and a release plan with milestones. Pull request conventions encourage small, focused PRs (targeting ~<=400 lines), link to the originating issue and acceptance criteria, require CI (tests, linting, security scans) to pass, and at least one approval before merge.

Roles and responsibilities are explicit: Product Managers define the problem, goals, success metrics and prioritize the backlog; Project Managers coordinate schedules, risks, and communications; Developers implement and test features; QA validates acceptance criteria and quality; stakeholders provide input and approvals. These personas are used to assign clear owners for artifacts such as the Project One‑pager, Risk Register, Definition of Done, and release notes so ownership and handoffs are predictable during planning and execution.

Communication is cadence‑driven and templated to keep stakeholders aligned. The team practices daily standups for progress and blockers, a weekly delivery sync to surface progress and risks, sprint/demo reviews at milestone ends, and monthly stakeholder updates. Status and incident communications use simple templates (weekly status: progress, next steps, risks/blockers, asks) and an escalation path (team → PM → Product Lead → Sponsor). Risk management is centralized in a Risk Register (ID, impact/likelihood, owner, mitigation, status) and reviewed regularly.

Quality assurance and release practices emphasize automated coverage plus manual verification for critical flows. New logic should have unit tests, with integration tests as applicable and end‑to‑end smoke tests for key flows; CI runs tests, linting, and security scans before review. Releases follow a checklist (staging smoke tests, automated production deploy where possible, post‑deploy verifications, rollback plan) and include release notes and mitigation steps. Continuous improvement is reinforced through regular retrospectives that capture action items, track their impact, and feed improvements back into the backlog and documentation.

## Where to find more

Detailed process documentation is available in the `docs/` folder:

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Risks & Communication](octoacme-risks-and-communication.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
