# OctoAcme Project Management Docs

This README provides an entry point and overview for the OctoAcme project management documentation. Below you'll find a summary of our key project management processes, along with quick links to all available process documents.

## Project Management Process Overview

OctoAcme follows a structured five-phase project lifecycle designed to deliver customer value iteratively while maintaining clear ownership, measurable outcomes, and continuous improvement. Our approach emphasizes psychological safety, data-informed decisions, and transparent communication across all stakeholders.

### Key Lifecycle Phases

**Initiation & Planning**: Projects begin with a lightweight validation phase where we confirm business needs through a Project One-pager, identify stakeholders, and establish measurable success metrics. Once approved, we break work into prioritized, estimated backlog items with clear acceptance criteria and a documented Definition of Done.

**Execution & Tracking**: Delivery is managed through daily standups (15 minutes), weekly delivery syncs, and sprint-based iterations using project boards. Pull requests are kept intentionally small (≤400 lines) and require at least one approval before merging. Quality is embedded through unit tests, integration tests, and end-to-end smoke tests for critical flows.

**Risk Management & Communication**: We proactively maintain a Risk Register documenting each issue's impact, likelihood, owner, and mitigation strategy, reviewed weekly during syncs. Communication follows a consistent rhythm: weekly PM/Product Manager alignment, twice-weekly standups, monthly stakeholder updates, and structured escalation paths (team-level → PM → Product Lead → Sponsor).

**Release & Deployment**: Pre-release requirements include passing CI/security scans, drafted release notes, and documented rollback plans. Deployments follow a standardized checklist with post-deploy verification and stakeholder announcements. If issues occur, incident response is triggered with root-cause triage and blameless retrospectives.

**Retrospective & Continuous Improvement**: After each sprint, release, or milestone, we conduct retrospectives (45–75 minutes) to capture learnings and assign 2–3 prioritized action items with clear owners and due dates. This cycle of structured reflection and incremental change reduces cycle time and builds a culture of continuous learning.

### Core Roles & Responsibilities

- **Project Managers**: Coordinate delivery, manage schedules, risks, and communications
- **Product Managers**: Define outcomes, prioritize the backlog, and measure success
- **Developers**: Implement features, collaborate on design, and identify technical risks
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs, approvals, and business context

## Process Documentation

Quick links to all OctoAcme project management process documents:

- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, roles, principles, and key artifacts
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Steps to validate business need, align stakeholders, and create a lightweight plan
- **[Project Planning](./octoacme-project-planning.md)** — How to turn an approved initiative into an actionable plan and prioritized backlog
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Day-to-day execution guidance, team rhythm, workflows, quality standards, and blocker escalation
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Risk identification, lifecycle, stakeholder communication, and escalation paths
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardized release process, pre-release requirements, deployment checklist, and rollback playbook
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — How to conduct retrospectives and convert learnings into actionable improvements
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Detailed definitions of typical roles and responsibilities used across OctoAcme projects

## Getting Started

1. **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) for a concise introduction.
2. **Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md), then move to [Project Planning](./octoacme-project-planning.md).
3. **In active delivery?** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Risk Management & Communication](./octoacme-risks-and-communication.md).
4. **Preparing for release?** Use the [Release & Deployment Guide](./octoacme-release-and-deployment.md).
5. **Wrapping up?** Conduct a retrospective using [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md).

## Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named roles with clear responsibilities
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning from all team members
