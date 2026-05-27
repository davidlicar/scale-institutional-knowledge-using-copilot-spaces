# OctoAcme Project Management Docs

Welcome! This README helps you navigate all OctoAcme project management process documentation and summarizes our approach to running successful, customer-focused projects.

## What is OctoAcme Project Management?

OctoAcme's project management approach balances **customer-first delivery**, **iterative execution**, **clear roles and ownership**, and **strong communication**. Our framework ensures that teams can execute efficiently while maintaining transparency and alignment across stakeholders.

### Core Principles
- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments and gather feedback early
- **Clear ownership**: Each project has named owners (Project Manager and Product Manager) with explicit responsibilities
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

### Project Lifecycle

OctoAcme projects follow a five-phase lifecycle:

1. **Initiation** — Validate business need, align stakeholders, and create a lightweight Project One-pager defining the problem, goals, success metrics, and key dependencies
2. **Planning** — Break work into shippable increments with clear acceptance criteria, estimate scope, identify risks and dependencies, and establish a release plan
3. **Execution & Tracking** — Manage day-to-day delivery through standups, sprint boards, and continuous testing, with escalation paths for blockers
4. **Release & Deployment** — Standardize how features move to production with pre-release checklists, smoke tests, and rollback playbooks
5. **Retrospective & Continuous Improvement** — Capture learnings, convert them into actionable improvements, and track impact

### Key Roles

- **Project Manager (PM)**: Coordinates delivery, manages schedules, risks, and communications; ensures transparent reporting and on-time delivery
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, owns success metrics, and validates solutions through research and data
- **Developers**: Implement features with high quality standards, collaborate on design and testability, participate in planning and risk identification
- **QA/Testing**: Validate quality and acceptance criteria through unit tests, integration tests, and end-to-end smoke tests
- **Stakeholders**: Provide inputs, approvals, and context; receive regular status updates and are involved in key decision gates

### Communication Cadence

OctoAcme maintains a structured communication rhythm to keep teams aligned without creating overhead:

- **Daily standups** (15 min) — Team-level focus on progress, blockers, and dependencies
- **Weekly PM + PdM sync** — Review progress, update risks, and align on priorities
- **Twice-weekly delivery standups** — For engineering and QA teams (or as agreed)
- **Weekly stakeholder updates** — Status, risks, and asks (or milestone-based as appropriate)
- **Monthly executive updates** — High-level progress and business impact
- **Ad-hoc escalations** — For critical issues following defined escalation paths

### Quality & Testing

Quality is embedded throughout execution:

- **Unit tests** for new logic
- **Integration tests** where applicable
- **End-to-end smoke tests** for critical flows before release
- **Security scanning** in CI/CD pipelines
- **Manual QA** for feature acceptance when needed
- **Definition of Done** established during planning to ensure consistent quality standards

### Risk & Dependency Management

Risks are actively managed throughout the project lifecycle:

- **Risk Register** maintained with: ID, Description, Impact, Likelihood, Owner, Mitigation plan, and Status
- **Weekly review** at PM syncs to monitor status and adjust mitigation strategies
- **Escalation path** for high-impact risks: Team → PM → Product Lead → Sponsor
- **Dependencies mapped** in project boards and flagged in weekly syncs

### Continuous Improvement

- **Retrospectives** held after each sprint, release, or milestone to capture learnings
- **Action items** tracked in the backlog with clear owners and due dates
- **Impact measured** to validate improvements and celebrate wins
- **Process refined** through iterative, small changes based on real project experience

---

## Documentation Index

Navigate to each process document below for detailed guidance:

### Overviews & Frameworks
- **[Project Management Overview](octoacme-project-management-overview.md)** — Concise introduction to OctoAcme's approach, roles, and key artifacts

### Project Phases
- **[Project Initiation](octoacme-project-initiation.md)** — Steps to validate and authorize work, align stakeholders, and create a lightweight plan
- **[Project Planning](octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day execution, track progress, and escalate blockers
- **[Release & Deployment](octoacme-release-and-deployment.md)** — Standardize how features move to production with safety checks and incident response
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements

### Cross-Cutting Concerns
- **[Risks & Communication](octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks; maintain stakeholder alignment
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Detailed responsibility breakdown for Developers, Product Managers, and Project Managers

---

## Getting Started

**New to OctoAcme?** Start here:
1. Read the [Project Management Overview](octoacme-project-management-overview.md) for a concise introduction
2. Review [Roles & Personas](octoacme-roles-and-personas.md) to understand your responsibilities
3. Navigate to the phase-specific docs as you progress through your project

**Leading a new project?** Follow this sequence:
1. [Project Initiation](octoacme-project-initiation.md) — Create your Project One-pager and secure stakeholder buy-in
2. [Project Planning](octoacme-project-planning.md) — Build your backlog, estimate scope, and identify risks
3. [Execution & Tracking](octoacme-execution-and-tracking.md) — Execute sprints and maintain momentum
4. [Release & Deployment](octoacme-release-and-deployment.md) — Prepare and ship your work safely
5. [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and improve

---

## Questions or Feedback?

These process docs are living artifacts. If you see gaps, unclear sections, or best practices that should be added, please [create an issue](https://github.com/davidlicar/scale-institutional-knowledge-using-copilot-spaces/issues/new?template=add-update-content-to-process-docs.yml) to request updates.
