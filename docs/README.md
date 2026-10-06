# OctoAcme Project Management Docs

## Overview

This folder contains the comprehensive project management framework and process documentation for OctoAcme. Use these guides to understand how we run projects, coordinate teams, and deliver value to customers.

## Quick Links to Process Docs

### Core Processes
- **[Project Management Overview](./octoacme-project-management-overview.md)** — Introduction to OctoAcme's approach, core roles, and key artifacts
- **[Project Initiation](./octoacme-project-initiation.md)** — How to start a new project and validate business need
- **[Project Planning](./octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Day-to-day execution, team rhythm, and progress tracking
- **[Release & Deployment](./octoacme-release-and-deployment.md)** — Standardized release processes and deployment checklists

### Supporting Processes
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Risk identification, escalation paths, and stakeholder communication
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and drive ongoing improvements
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Definitions of core project roles and responsibilities

## OctoAcme Project Management Overview

OctoAcme operates projects through a structured lifecycle that emphasizes customer value, iterative delivery, and clear ownership. The organization follows five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During initiation, teams validate business needs and create a lightweight Project One-pager that defines the problem statement, success metrics, and stakeholder alignment—this serves as the decision gate for moving forward. Once approved, the planning phase breaks work into shippable increments with prioritized backlogs, acceptance criteria, and a Definition of Done. This disciplined approach ensures that teams have clarity on scope, dependencies, and timelines before development begins.

Execution and delivery are coordinated through well-defined communication rhythms and governance structures. Teams conduct daily standups (15 minutes), weekly delivery syncs, and milestone-based demos to track progress using GitHub Projects boards with columns spanning Backlog, Ready, In Progress, In Review, QA, and Done. Quality is enforced through mandatory unit and integration tests, security scanning in CI/CD pipelines, and a pull request workflow requiring small PRs (≤400 lines) with at least one approval before merging. Risks are actively managed through a Risk Register maintained at weekly syncs, with escalation paths moving from team-level triage to PM to Product Lead to sponsor level for business-impacting issues.

OctoAcme defines clear roles to ensure accountability and reduce ambiguity. **Project Managers** coordinate delivery, manage schedules and risks, and facilitate communications; **Product Managers** define what should be built, prioritize the backlog, and measure outcomes; **Developers** implement features, write tests, and collaborate on design; and **QA/Testing** validates quality against acceptance criteria. Weekly syncs between PM and Product Manager, along with twice-weekly standups for delivery teams, keep stakeholders aligned and enable rapid decision-making. This role clarity, combined with data-driven metrics (velocity, burndown, usage dashboards), ensures that projects remain on track and that decisions are informed by evidence rather than assumptions.

Finally, OctoAcme embeds continuous improvement into every project cycle. After each sprint, release, or significant milestone, teams conduct blameless retrospectives to capture what went well, what could improve, and identify 2–3 actionable items with clear owners and due dates. Release and deployment follow a standardized checklist that includes pre-release verification, smoke testing, rollback plans, and post-deploy monitoring. This commitment to reflection, learning, and incremental refinement—combined with transparent communication to stakeholders and the use of shared artifacts like project charters and risk registers—enables OctoAcme to deliver reliably while building a culture of psychological safety and collective ownership.

## OctoAcme Project Management Principles

- **Customer-first:** Prioritize customer value and usability in all decisions
- **Iterative delivery:** Deliver small, testable increments and gather feedback
- **Clear ownership:** Each project has a named Project Manager and Product Lead
- **Data-informed decisions:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback, learning, and continuous improvement

## Key Artifacts You'll Work With

- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Project Lifecycle (High-Level)

1. **Initiation** → Define problem, stakeholders, and timeline
2. **Planning** → Break into shippable increments and identify dependencies
3. **Execution** → Build, test, review, and iterate
4. **Release** → Deploy to production and verify
5. **Close & Retrospective** → Capture learnings and next steps

## Getting Started

**New to OctoAcme?** Start with [Project Management Overview](./octoacme-project-management-overview.md).

**Starting a new project?** Follow the [Initiation Guide](./octoacme-project-initiation.md).

**Managing a project?** Use [Project Planning](./octoacme-project-planning.md) and [Execution & Tracking](./octoacme-execution-and-tracking.md).
