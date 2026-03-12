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

---

## Risk Manager

### Role Summary
The Risk Manager proactively identifies, documents, assesses, and tracks project risks. They own the risk register and ensure that risk mitigation strategies are defined and implemented before issues escalate.

### Responsibilities
- Proactively identify and document risks across all project phases
- Perform risk assessments (likelihood, impact, priority)
- Own and maintain the risk register
- Recommend and coordinate mitigation strategies
- Trigger escalation when risk thresholds are met

### Goals
- Minimize the probability and impact of project risks
- Ensure all risks have defined owners and mitigation plans
- Keep the team and stakeholders informed of the current risk landscape

### Typical Communication
- Bi-weekly risk register reviews with the Project Manager
- Risk escalation notifications to the Stakeholder Liaison for external impacts
- Risk status updates in weekly delivery syncs

### Interactions with Existing Roles
| Role | Nature of Interaction |
|---|---|
| Project Manager | Feeds risk reports into status meetings; escalates high-priority risks |
| Team Leads | Coordinates implementation of mitigation actions |
| Stakeholder Liaison | Notifies of risks with external or stakeholder impact |
| Developers | Collaborates to identify technical risks |
| Scrum Master | Surfaces impediments that may become risks |

### RACI Mapping

| Activity | Risk Manager |
|---|---|
| Initiation | Consulted |
| Planning | Responsible |
| Risk Management | Accountable |
| Execution | Responsible |
| Release | Consulted |
| Retrospective | Consulted |

### When to Engage This Persona
- At project kickoff to seed the initial risk register
- During planning to assess risks associated with scope, timeline, or resources
- Whenever a new risk or issue is identified during execution
- Before a release to confirm that all risks are mitigated or accepted
- After incidents to conduct a risk retrospective

---

## Stakeholder Liaison

### Role Summary
The Stakeholder Liaison serves as the single point of contact for all project stakeholders. They gather requirements and feedback, schedule stakeholder reviews, and track approvals and concerns to ensure stakeholder alignment throughout the project lifecycle.

### Responsibilities
- Serve as the single point of contact for internal and external stakeholders
- Gather stakeholder requirements and feedback
- Schedule and facilitate stakeholder review meetings
- Track stakeholder approvals, decisions, and outstanding concerns
- Communicate project updates, milestones, and decisions back to stakeholders

### Goals
- Maintain clear and consistent stakeholder communication
- Ensure stakeholder input is captured and actioned
- Reduce misalignment and late-stage requirement changes

### Typical Communication
- Regular stakeholder update cadence (weekly or bi-weekly)
- Meeting notes and approval records distributed after stakeholder sessions
- Coordinated messaging with Project Manager for milestone announcements

### Interactions with Existing Roles
| Role | Nature of Interaction |
|---|---|
| Project Manager | Partners on messaging, milestone communication, and escalation paths |
| Product Owner/Manager | Collects stakeholder input; communicates decisions and feedback |
| Risk Manager | Receives notifications for risks with external stakeholder impact |
| Developers | Relays stakeholder requirements and acceptance criteria |
| Operations | Coordinates stakeholder-facing release and deployment communication |

### RACI Mapping

| Activity | Stakeholder Liaison |
|---|---|
| Initiation | Responsible |
| Planning | Consulted |
| Risk Management | Informed |
| Execution | Responsible |
| Release | Accountable |
| Retrospective | Consulted |

### When to Engage This Persona
- At project initiation to identify and onboard all relevant stakeholders
- During planning to gather and validate stakeholder requirements
- At key milestones to obtain stakeholder approvals
- When risks or issues arise that may affect external parties
- During release to coordinate stakeholder sign-off and communications

---

## Quality Assurance Lead

### Role Summary
The Quality Assurance (QA) Lead defines acceptance criteria and quality gates, owns the test strategy and verification activities, and approves release readiness from a quality perspective.

### Responsibilities
- Define acceptance criteria and quality gates for all deliverables
- Own and maintain the test strategy, test plans, and verification activities
- Oversee execution of test cycles (unit, integration, end-to-end, regression)
- Approve or reject release readiness based on quality outcomes
- Track defects and ensure resolution before release

### Goals
- Ensure all deliverables meet defined acceptance criteria and quality standards
- Minimize defect escape rate to production
- Maintain complete test coverage for critical flows

### Typical Communication
- QA status updates in weekly delivery syncs
- Defect triage meetings with Developers and Team Leads
- Release readiness sign-off reports to PM and Stakeholder Liaison

### Interactions with Existing Roles
| Role | Nature of Interaction |
|---|---|
| Developers | Collaborates to define test plans; reviews defect fixes |
| Team Leads | Aligns on quality expectations and test coverage targets |
| Project Manager | Reports QA status and release readiness |
| Stakeholder Liaison | Communicates quality outcomes relevant to stakeholders |
| Scrum Master | Flags QA blockers as sprint impediments |

### RACI Mapping

| Activity | QA Lead |
|---|---|
| Initiation | Consulted |
| Planning | Responsible |
| Risk Management | Consulted |
| Execution | Accountable |
| Release | Accountable |
| Retrospective | Consulted |

### When to Engage This Persona
- During planning to define the test strategy and acceptance criteria
- At the start of each sprint or iteration to review definition of done
- During execution for ongoing test execution and defect management
- Before a release to validate that all quality gates are met
- After incidents or major bugs to refine test coverage

---

## Agile Coach

### Role Summary
The Agile Coach mentors teams on agile practices, facilitates continuous improvement, helps resolve process impediments, and optimizes ceremonies to maximize team effectiveness.

### Responsibilities
- Mentor teams on agile principles and practices (Scrum, Kanban, SAFe, etc.)
- Facilitate retrospectives and continuous improvement initiatives
- Help identify and resolve process impediments
- Coach ceremonies (standups, sprint planning, reviews, retrospectives) for effectiveness
- Support teams in self-organization and cross-functional collaboration

### Goals
- Build a sustainable agile culture within the team
- Continuously improve team velocity, predictability, and quality
- Remove systemic process impediments that hinder delivery

### Typical Communication
- Regular 1:1 coaching sessions with Scrum Master(s) and Team Leads
- Retrospective facilitation and action item tracking
- Process health reporting to Project Manager and leadership

### Interactions with Existing Roles
| Role | Nature of Interaction |
|---|---|
| Scrum Master | Coaches and mentors on facilitation and agile practices |
| Team Leads | Supports alignment of iteration planning and team retrospectives |
| Project Manager | Advises on agile process optimization and team health |
| Developers | Facilitates team ceremonies and removes process blockers |
| Product Owner/Manager | Coaches on effective backlog management and prioritization |

### RACI Mapping

| Activity | Agile Coach |
|---|---|
| Initiation | Consulted |
| Planning | Consulted |
| Risk Management | Informed |
| Execution | Responsible |
| Release | Informed |
| Retrospective | Accountable |

### When to Engage This Persona
- When adopting or scaling agile practices for the first time
- During sprint planning or retrospectives to facilitate and improve ceremony quality
- When the team is experiencing recurring impediments or low velocity
- When onboarding new team members to agile ways of working
- After major incidents or delivery failures to facilitate process improvements

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

