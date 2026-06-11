# OctoAcme — Role Collaboration & Handoffs

## Purpose
Clarify accountability boundaries and common handoffs between cross-functional roles so work moves from planning to release with fewer gaps.

## Collaboration Principles
- Keep one shared source of truth for requirements, decisions, and status.
- Record explicit owners for each handoff deliverable.
- Escalate blockers through the documented PM/PdM/stakeholder path when cross-team resolution stalls.

## Role Collaboration Matrix (RACI-lite)

| Process area | Primary owner | Key supporting roles | Required collaborators |
| --- | --- | --- | --- |
| Problem framing and outcomes | Product Manager | Business Analyst | Project Manager, Stakeholders |
| Delivery planning and dependencies | Project Manager | Scrum Master | Product Manager, Developers, QA Lead |
| UX definition and validation | UX Designer | Product Manager | Developers, QA Lead, Stakeholders |
| Build and implementation | Developers | Scrum Master | Product Manager, UX Designer, QA Lead |
| Test strategy and quality gates | QA Lead | QA/Testing contributors | Developers, Project Manager, Product Manager |
| Release readiness and deployment | Release Manager | Project Manager | QA Lead, Developers, Product Manager, Stakeholders |
| Retrospective and process improvement | Scrum Master | Project Manager | Product Manager, Developers, QA Lead |

## Standard Handoff Checklist

Use this checklist at each phase boundary (planning to execution, execution to release, release to retrospective):

- [ ] **Scope handoff complete:** Prioritized backlog item(s) include acceptance criteria, owners, dependencies, and target milestone.
- [ ] **Design handoff complete (if applicable):** UX artifacts are linked and include edge states, accessibility expectations, and open questions.
- [ ] **Build handoff complete:** Implementation notes, technical assumptions, and integration impacts are documented for QA and PM visibility.
- [ ] **Quality handoff complete:** Test coverage plan, defect triage path, and unresolved risk log entries are documented.
- [ ] **Release handoff complete:** Checklist status, approvals, communication plan, and rollback readiness are documented.
- [ ] **Stakeholder handoff complete:** Decision points, launch status, and post-release follow-ups are shared with named stakeholders.

## Escalation Ownership
- **Execution blockers:** Scrum Master facilitates first response; Project Manager owns cross-team escalation.
- **Scope/trade-off decisions:** Product Manager owns prioritization with stakeholder input.
- **Quality and release risk acceptance:** QA Lead and Release Manager recommend; Project Manager and Stakeholder sponsor finalize go/no-go.
