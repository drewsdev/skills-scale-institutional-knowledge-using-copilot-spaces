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

## Stakeholders / QA

### Role Summary
Stakeholders provide business context, inputs, and approvals. QA validates quality and acceptance criteria before release.

### Responsibilities
- Provide requirements, priorities, and business context
- Review and approve deliverables at key milestones
- Validate that implemented features meet acceptance criteria (QA)
- Surface quality issues and regression risks (QA)

### Goals
- Ensure delivered work meets business and customer expectations
- Maintain confidence in product quality
- Provide timely feedback to keep delivery on track

### Typical Communication
- Milestone demos and sign-off meetings
- Bug reports and QA test results
- Stakeholder update emails / status calls

---

## UX Designer

### Role Summary
UX Designers champion user experience, accessibility, and usability across the product. They translate user needs and business goals into intuitive designs that guide development.

### Responsibilities
- Create user flows, wireframes, and prototypes
- Conduct user research and usability testing
- Define and document UI/UX standards and patterns
- Advocate for accessibility and inclusive design
- Collaborate on design reviews with Developers and Product Managers

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce rework by validating designs early with real users
- Ensure visual and interaction consistency across the product

### Typical Communication
- Design review sessions with Developers and Product Managers
- Shared design files and annotated mockups (e.g., Figma)
- Usability test summaries and recommendations

### Works closely with / Interacts with
- **Product Managers** — align on user requirements, feature scope, and acceptance criteria
- **Developers** — collaborate on implementation feasibility, handoff assets, and design Q&A
- **Stakeholders / QA** — gather feedback during usability tests and validate designs meet expectations
- **Project Managers** — flag design dependencies and timeline impacts early

---

## Solution Architect

### Role Summary
Solution Architects define the technical architecture and ensure it aligns with security, scalability, and engineering best practices. They guide high-level design decisions and support teams in navigating technical complexity.

### Responsibilities
- Define and document system architecture and integration patterns
- Review key technical decisions for alignment with best practices and security requirements
- Identify architectural risks and propose mitigations
- Advise technical leads and Developers during design and implementation
- Ensure architectural consistency across teams and releases

### Goals
- Deliver scalable, secure, and maintainable architectures
- Prevent costly technical debt through early design guidance
- Keep teams aligned on architectural standards and constraints

### Typical Communication
- Architecture decision records (ADRs) and design documentation
- Technical review sessions with Developers and Project Managers
- Risk and dependency notes in the risk register

### Works closely with / Interacts with
- **Developers** — guide design decisions, review technical spikes, and ensure implementation aligns with architecture
- **Project Managers** — provide effort estimates and flag architectural dependencies on timelines
- **Product Managers** — validate that technical solutions meet product requirements and constraints
- **Stakeholders / QA** — advise on testability, non-functional requirements, and integration acceptance criteria

---

## Support / Customer Success Lead

### Role Summary
Support / Customer Success Leads champion the end-user perspective during and after delivery. They coordinate handoffs to support teams, gather customer feedback, and drive knowledge transfer to ensure smooth operations post-release.

### Responsibilities
- Represent customer needs and priorities in planning and release discussions
- Coordinate release readiness and handoffs to support teams
- Gather and synthesize customer feedback for the product backlog
- Manage escalations from customers and route issues to the right teams
- Deliver and maintain user-facing training and knowledge base content

### Goals
- Ensure customers can successfully adopt and use delivered features
- Reduce time-to-resolution for post-release issues
- Create a feedback loop that improves future product decisions

### Typical Communication
- Release readiness meetings with Developers and QA
- Customer feedback summaries shared with Product Managers
- Support runbooks and training materials for end users

### Works closely with / Interacts with
- **Developers** — coordinate handover, document known issues, and escalate production incidents
- **Stakeholders / QA** — triage issues, align on severity, and confirm feature acceptance from a customer perspective
- **Product Managers** — share customer feedback and advocate for user-impacting backlog items
- **Project Managers** — flag support readiness risks and ensure handoff activities are tracked in the project plan

---

## Data Analyst

### Role Summary
Data Analysts generate insights from project and product metrics to support evidence-based decision-making. They help teams understand outcomes, track key performance indicators, and identify opportunities for improvement.

### Responsibilities
- Define, collect, and analyze project and product metrics
- Build and maintain dashboards and reports for key stakeholders
- Surface trends, anomalies, and actionable insights from data
- Support post-release reviews with quantitative outcome data
- Collaborate with Product Managers on KPI definition and tracking

### Goals
- Enable data-informed decisions throughout the project lifecycle
- Make project outcomes and impact visible to stakeholders
- Identify performance bottlenecks and improvement opportunities early

### Typical Communication
- Dashboard links and metric summaries in status updates
- Retrospective data reports (velocity, quality, adoption)
- Ad-hoc analysis shared with Product Managers and Stakeholders

### Works closely with / Interacts with
- **Product Managers** — define success metrics and KPIs; report on outcome achievement
- **Project Managers** — provide progress and velocity insights; surface trends that may impact delivery
- **Stakeholders / QA** — communicate results, quality trends, and adoption data in stakeholder updates
- **Developers** — coordinate on instrumentation and data availability for new features

---

## RACI Responsibility Matrix

The table below maps key lifecycle activities to roles. Use this as a quick reference for ownership and accountability.

**Key:** R = Responsible (does the work) · A = Accountable (final authority) · C = Consulted (provides input) · I = Informed (kept up to date)

| Activity | Project Manager | Product Manager | Developers | UX Designer | Solution Architect | Support / CS Lead | Data Analyst | Stakeholders / QA |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Initiation** — problem statement & one-pager | R | A | I | C | C | C | I | C |
| **Planning** — scope, backlog, milestones | A | R | C | C | C | C | I | I |
| **Architecture & design** | I | C | C | R | A | I | I | C |
| **UX design & research** | I | C | C | A | C | C | I | C |
| **Execution** — feature build & testing | C | C | R | C | C | I | I | I |
| **Quality assurance & acceptance** | I | C | R | C | C | C | I | A |
| **Risk identification & escalation** | A | C | C | C | R | C | C | C |
| **Release planning & deployment** | A | C | R | I | C | C | I | C |
| **Release / support handoff** | C | I | R | I | C | A | I | C |
| **Post-release metrics & review** | I | A | C | C | I | C | R | C |
| **Retrospectives & improvement** | A | C | C | C | C | C | C | I |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

