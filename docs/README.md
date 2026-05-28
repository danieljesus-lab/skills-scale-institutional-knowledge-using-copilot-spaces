# OctoAcme Project Management Docs

Welcome! This README summarizes the core project management processes followed by OctoAcme and provides quick links to detailed process documentation.

## OctoAcme Project Management Overview

OctoAcme follows a structured, lifecycle-based approach to project delivery that emphasizes customer value, iterative execution, and clear ownership. The framework consists of five distinct phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During initiation, teams validate business need and create a lightweight Project One-pager that defines the problem statement, success metrics, and stakeholder alignment—serving as the decision gate to move forward. Once approved, the planning phase transforms the initiative into an actionable backlog broken into shippable increments with defined dependencies, risks, and a release timeline.

Execution and tracking are coordinated through daily standups (15 minutes), weekly delivery syncs, and a GitHub Projects board with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done). Pull requests are kept small (≤400 lines when possible) and require at least one approval before merging, with automated CI testing and linting run before review. Quality assurance is embedded throughout: unit tests cover new logic, integration tests validate cross-component flows, and end-to-end smoke tests verify critical paths before release. Security scanning is integrated into the CI pipeline, and manual QA is performed when needed for feature acceptance.

OctoAcme defines clear roles and accountability to prevent confusion and bottlenecks. **Project Managers** coordinate schedules, manage risks, and facilitate communication; **Product Managers** own prioritization and success metrics; **Developers** implement features and contribute to technical decisions; and **QA/Testing** validates acceptance criteria. Communication cadence is deliberate—weekly syncs between PM and Product Lead, twice-weekly standups for the delivery team, and monthly stakeholder updates—with a documented escalation path (team-level → PM → Product Lead → Sponsor) for risks and blockers.

Finally, OctoAcme embeds continuous improvement into its culture through structured retrospectives held after each sprint, release, or milestone. Teams reflect on what went well, what could improve, and identify 2–3 prioritized action items with clear owners and due dates. This combination of disciplined planning, embedded quality practices, clear roles, transparent communication, and a learning mindset creates a sustainable, scalable delivery model.

## Process Documents Index

- **[Project Management Overview](octoacme-project-management-overview.md)** — Core principles, roles, artifacts, and lifecycle overview
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Validate business need, align stakeholders, and make go/no-go decisions
- **[Project Planning](octoacme-project-planning.md)** — Break work into increments, estimate scope, identify risks and dependencies
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day coordination, team rhythm, quality assurance, and reporting
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Risk registers, escalation paths, and stakeholder communication strategies
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardized release processes, deployment checklists, and rollback procedures
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Post-delivery reviews, action item tracking, and iterative process improvements
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Detailed responsibilities and communication patterns for Developers, Product Managers, and Project Managers

## Quick Start for New Team Members

1. **Understand the landscape:** Start with [Project Management Overview](octoacme-project-management-overview.md) to learn core principles and roles.
2. **Learn your role:** Check [Roles & Personas](octoacme-roles-and-personas.md) to understand responsibilities and communication patterns.
3. **Follow the phase:** Depending on your current project stage, dive into the relevant phase document (Initiation → Planning → Execution → Release → Retrospective).
4. **Reference as needed:** Use the index above to quickly access specific guidance on risk management, communication, or deployment procedures.

## Key Principles

- **Customer-first:** Prioritize customer value and usability
- **Iterative delivery:** Deliver small, testable increments
- **Clear ownership:** Each project has named PM and Product Lead
- **Data-informed:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback and learning
