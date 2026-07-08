# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation. These guides standardize how we run projects, deliver value, and learn from our work.

## Quick Start

**New to OctoAcme?** Start here:
1. Read [Project Management Overview](octoacme-project-management-overview.md) for core principles and roles
2. Browse the [complete process map](#process-map) below to find what you need
3. Check your [role-specific guide](#role-guides) for tailored workflows

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named owners
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## OctoAcme Project Management Overview

OctoAcme operates a structured five-phase project lifecycle: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. The approach is grounded in customer-first principles, iterative delivery, clear ownership, data-informed decisions, and psychological safety. Projects begin with validation through a lightweight One-pager that confirms business need, identifies stakeholders, and establishes success metrics before moving into detailed planning. Once approved, the team breaks work into shippable increments with prioritized backlogs, acceptance criteria, and estimated scopes. This gateway approach ensures that only well-defined initiatives move forward, reducing wasted effort and misalignment.

**Roles, Communication, and Coordination**: Three core delivery roles drive execution: Project Managers (PMs) coordinate schedules, risks, and communications; Product Managers (PdMs) define outcomes and measure success; and Developers implement features with quality and testability. Supporting roles include QA/Testing for validation and stakeholders for inputs and approvals. Communication follows a regular cadence—weekly syncs between PM and PdM, twice-weekly standups for the delivery team, and monthly stakeholder updates—with a clear escalation path (team-level → PM → Product Lead → Sponsor) for blockers and risks. Risk management is embedded throughout, using a simple Risk Register to identify, assess, mitigate, and monitor threats to delivery.

**Execution, Quality, and Continuous Improvement**: During execution, teams use GitHub Projects with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) and maintain small pull requests (≤400 lines) with linked issues and acceptance criteria. Quality is enforced through CI automation (tests, linting, security scans), manual QA for feature acceptance, and a Definition of Done that every team member understands. Releases are standardized with pre-release checklists, smoke tests, and documented rollback plans to minimize production risk. Finally, retrospectives held after sprints, releases, or milestones capture learnings and convert them into actionable improvements tracked in the project backlog, creating a culture of continuous iteration and evidence-based refinement.

## Process Map

| Phase | Document | Purpose |
|-------|----------|---------|
| **Initiation** | [Project Initiation Guide](octoacme-project-initiation.md) | Validate business need, align stakeholders, define success criteria |
| **Planning** | [Project Planning](octoacme-project-planning.md) | Break work into shippable increments, identify dependencies and risks |
| **Execution** | [Execution & Tracking](octoacme-execution-and-tracking.md) | Manage day-to-day delivery, track progress, handle blockers |
| **Release** | [Release & Deployment Guide](octoacme-release-and-deployment.md) | Standardize release process, reduce risk, improve observability |
| **Close & Learn** | [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings, convert insights into improvements |
| **Cross-cutting** | [Risk Management & Communication](octoacme-risks-and-communication.md) | Identify, manage, and communicate risks throughout the project |

## Role Guides

- **[Developers](octoacme-roles-and-personas.md#developers)**: Design, build, test, and deliver software components
- **[Product Managers](octoacme-roles-and-personas.md#product-managers)**: Define what should be built to deliver value
- **[Project Managers](octoacme-roles-and-personas.md#project-managers)**: Coordinate delivery, manage schedules and risks

## Project Lifecycle at a Glance

```
Initiation → Planning → Execution → Release → Retrospective
                                                     ↓
                                         Continuous Improvement
```

## Templates & Artifacts

**Issue Templates**: [View all issue templates](../.github/ISSUE_TEMPLATE/)
- [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)

**Key Artifacts** you'll create:
- Project Charter / One-pager
- Sprint/Iteration Backlog
- Risk Register
- Release Notes
- Retrospective Action Items

## Using These Docs with Copilot Spaces

These documents are optimized for use in GitHub Copilot Spaces. Reference them by name or phase when asking for guidance on specific project management topics.

## Contributing

Have improvements to suggest? Use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.
