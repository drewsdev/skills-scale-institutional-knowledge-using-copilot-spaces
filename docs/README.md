# OctoAcme Project Management Docs

Welcome! This README provides a concise overview of OctoAcme's project management processes and quick links to our detailed process documentation.

## Overview

OctoAcme follows a lightweight, repeatable project lifecycle guided by five core principles: **customer-first**, **iterative delivery**, **clear ownership**, **data-informed decisions**, and **psychological safety**.

### Key Workflows

Projects move through five stages:

1. **Initiation** – Validate the idea with a Project One-pager, align stakeholders, confirm metrics and team availability before committing to work.
2. **Planning** – Translate the approved initiative into an actionable backlog using a consistent backlog item template (title, description, acceptance criteria, priority, estimate, owner, related links), define a Definition of Done, and map milestones and dependencies.
3. **Execution** – Manage delivery through a shared project board (Backlog → Ready → In Progress → In Review → QA → Done), daily standups, and small pull requests linked to issues and acceptance criteria with CI checks (tests, lint, security scanning) required before merge.
4. **Release** – Follow a release checklist covering readiness verification, release notes, rollback planning, staging validation, and post-deploy checks.
5. **Close & Retrospective** – Capture learnings, convert them into owned, time-bound action items, and archive project artifacts.

### Personas & Roles

| Role | Responsibility |
|------|---------------|
| **Project Manager (PM)** | Coordinates delivery logistics: plans, schedules, risks, and communications. |
| **Product Manager (PdM)** | Owns outcomes and prioritization: problem definition, success metrics, roadmap/backlog trade-offs. |
| **Developers** | Design and implement features with testability and maintainability in mind; participate in design and code reviews. |
| **QA / Testing** | Validates acceptance criteria and overall quality. |
| **Stakeholders** | Provide inputs and approvals; receive regular status updates. |
| **UX Designer** | Champions user experience and accessibility; produces wireframes, prototypes, and design handoffs. |
| **Solution Architect** | Defines technical architecture, guides design decisions, and ensures alignment with security and best practices. |
| **Support / Customer Success Lead** | Coordinates release handoffs to support, gathers customer feedback, and drives adoption. |
| **Data Analyst** | Tracks project and product metrics, builds dashboards, and surfaces data-driven insights. |

### Communication Strategies

- **Daily standups** – Delivery team surfaces progress and blockers.
- **Weekly delivery sync** – PM + PdM review risks, dependencies, and priorities.
- **Monthly stakeholder updates** – Consistent status communicated via agreed templates.
- **Single source of truth** – Project README or release documentation serves as the authoritative reference.
- **Escalation path** – Issues are triaged at team level → PM → Product Lead → Sponsor.

### Quality Assurance Practices

- **PR workflow** – Small, focused pull requests linked to issues; CI must pass (unit tests, lint, security scanning) before review and merge.
- **Test coverage** – Unit and integration tests where appropriate; end-to-end smoke tests for critical flows.
- **Release checklist** – Covers staging validation, release notes, rollback planning, and post-deploy verification.
- **Security scanning** – Automated scanning runs as part of every CI pipeline.

---

## Process Documentation

| Document | Description |
|----------|-------------|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, roles, artifacts, and the full project lifecycle at a glance. |
| [Project Initiation](octoacme-project-initiation.md) | One-pager template, decision gate criteria, and stakeholder alignment steps. |
| [Project Planning](octoacme-project-planning.md) | Backlog item template, estimation guidance, milestones, and Definition of Done. |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Board workflow, standup format, PR process, and progress reporting. |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register format, escalation paths, and communication templates. |
| [Release & Deployment](octoacme-release-and-deployment.md) | Release checklist, deployment steps, rollback plan, and post-deploy verification. |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retro format, action item tracking, and improvement cadence. |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed responsibilities, goals, typical communication patterns, and RACI matrix for all roles. |
| [Release & Support Handoff Checklist](octoacme-handoff-checklist.md) | Reusable checklist for release readiness, support enablement, and post-release follow-up. |
