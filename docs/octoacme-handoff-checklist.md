# OctoAcme — Release & Support Handoff Checklist

## Purpose
Provide a lightweight, reusable checklist to ensure every release is handed off cleanly to support and operations teams, reducing post-release confusion and customer impact.

## When to use
Complete this checklist before each release (patch, minor, or major) as a complement to the [Release & Deployment Guide](octoacme-release-and-deployment.md). Ownership sits with the **Support / Customer Success Lead**, coordinated by the **Project Manager**.

---

## 1. Release Readiness (Pre-handoff)

- [ ] Release notes drafted and reviewed by Product Manager
- [ ] All known issues and limitations documented
- [ ] Customer-facing changelog / announcement prepared (if applicable)
- [ ] Training materials or knowledge-base articles updated to reflect new functionality
- [ ] Internal runbook updated with new operational steps or configuration changes

## 2. Support Team Enablement

- [ ] Support / Customer Success Lead has attended or reviewed the release demo
- [ ] New features walkthrough delivered to support team
- [ ] FAQ or troubleshooting guide created for top anticipated issues
- [ ] Escalation path documented: who to contact for each type of issue (bug, data, infra)
- [ ] On-call rotation or support owner confirmed for the release window

## 3. Technical Handoff

- [ ] Developers have documented known issues, workarounds, and edge cases
- [ ] Environment-specific configuration changes are captured in the runbook
- [ ] Rollback procedure reviewed and confirmed with Developers and Project Manager
- [ ] Monitoring dashboards and alerting thresholds reviewed (Data Analyst / Developers)
- [ ] Access and permissions verified for the support team

## 4. Stakeholder & Customer Communication

- [ ] Stakeholder communication drafted and scheduled (email, release notes post, etc.)
- [ ] Customer-facing communication approved by Product Manager and/or Stakeholders
- [ ] Communication sent / published at agreed time relative to deployment

## 5. Post-release Follow-up

- [ ] Support ticket volume monitored for the first 24–48 hours post-release
- [ ] Critical issues triaged and escalated immediately per the escalation path
- [ ] Feedback from support team shared with Product Manager within one sprint
- [ ] Data Analyst confirms key metrics are being captured and dashboards are live
- [ ] Handoff retrospective item added if process gaps were identified

---

## Roles & Responsibilities (Handoff)

| Step | Owner | Supports |
|------|-------|---------|
| Release notes & changelog | Product Manager | Project Manager |
| Training & knowledge-base updates | Support / CS Lead | Developers |
| Technical runbook & known issues | Developers | Solution Architect |
| Stakeholder communication | Product Manager | Project Manager |
| Monitoring & alerting review | Data Analyst | Developers |
| Post-release feedback loop | Support / CS Lead | Product Manager |

---

## Related Documents
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
