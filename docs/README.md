# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation suite. This folder contains the core processes, roles, and guidance that enable our teams to deliver projects efficiently and collaboratively.

## Quick Start

New to OctoAcme projects? Start with the [Project Management Overview](#project-management-overview) to understand our approach, then dive into specific processes as needed.

## Core Processes

### 1. **Initiation** — Get started with a new project
- [Project Initiation Guide](./octoacme-project-initiation.md)
  - Validate business need, identify stakeholders, define success criteria, and make the go/no-go decision.

### 2. **Planning** — Build an actionable delivery plan
- [Project Planning](./octoacme-project-planning.md)
  - Break work into shippable increments, estimate scope, identify dependencies, and create your release plan.

### 3. **Execution & Tracking** — Manage day-to-day delivery
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
  - Run standups, manage the project board, track metrics, and escalate blockers.

### 4. **Risk & Communication** — Identify and manage risks
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
  - Maintain a risk register, communicate status, and escalate issues.

### 5. **Release & Deployment** — Safely ship to production
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
  - Prepare for release, deploy with confidence, and handle rollbacks.

### 6. **Retrospectives** — Learn and improve
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
  - Capture learnings, convert them to action items, and drive incremental improvements.

## Reference Materials

### Project Management Overview
- [Project Management Overview](./octoacme-project-management-overview.md)
  - High-level introduction to OctoAcme's approach, principles, roles, and artifacts.

### Roles & Personas
- [OctoAcme Personas](./octoacme-roles-and-personas.md)
  - Definitions of key roles (Product Manager, Project Manager, Developer, QA/Testing) and their responsibilities.

## OctoAcme Project Management Approach

OctoAcme operates on a structured five-phase project lifecycle designed to maximize customer value while maintaining clear ownership and data-informed decision-making.

### Project Lifecycle

1. **Initiation**: Validate business need, identify stakeholders, and create a lightweight one-pager with problem statements, success metrics, and initial timelines.
2. **Planning**: Break work into shippable increments with clear acceptance criteria, prioritized backlogs, and estimated scope.
3. **Execution**: Maintain a rhythm of daily standups, weekly delivery syncs, and demos at sprint/milestone boundaries using GitHub Projects for workflow management.
4. **Release**: Prepare releases with passing CI/security scans, smoke tests, and rollback plans; deploy to staging then production with post-deploy verification.
5. **Close & Retrospective**: Capture learnings and convert them into actionable improvements for future projects.

### Key Workflows

**Execution & Delivery**:
- Use GitHub Projects with standardized columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow: small PRs (≤400 lines), include issue links and acceptance criteria, automated CI testing/linting, require at least one approval before merging
- Daily standups (15 min) focusing on progress, blockers, and dependencies
- Weekly delivery syncs showing progress, updates, and flagged risks
- Sprint/iteration planning with timeboxed sessions and clear Definition of Done

**Quality Assurance**:
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed
- All acceptance criteria verified before release

### Roles & Responsibilities

OctoAcme defines clear ownership across core personas:

- **Project Managers**: Coordinate delivery, manage schedules, risks, and communications; maintain project documentation and enable efficient execution
- **Product Managers**: Define outcomes, prioritize the backlog, measure success metrics, and validate solutions through user research
- **Developers**: Implement features, write tests, participate in design/code reviews, and identify technical risks
- **QA/Testing**: Validate quality and acceptance criteria through comprehensive testing strategies

### Communication & Risk Management

- **Communication Cadence**: Weekly syncs between PM and Product Manager, twice-weekly standups for delivery teams, monthly stakeholder updates, ad-hoc escalations as needed
- **Risk Escalation**: Three-level pathway—team-level triage in standups → PM escalation to Product Lead and dependent teams → sponsor-level escalation for business-impacting issues
- **Single Source of Truth**: Project README or release documentation ensures consistent status reporting across stakeholder groups
- **Status Reporting**: Weekly updates include progress, next steps, risks/blockers, and decisions needed

### Continuous Improvement

- Structured retrospectives after each sprint, release, or milestone (45–75 minutes)
- Capture what went well, what could improve, and prioritize 2–3 actionable items
- Clear ownership and due dates for action items reviewed in weekly PM syncs
- Blameless incident retrospectives to drive organizational learning
- Data-informed decision-making based on success metrics, velocity, burndown, and dashboards

## Core Principles

Our project management approach is built on these core principles:

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Key Artifacts

- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items
