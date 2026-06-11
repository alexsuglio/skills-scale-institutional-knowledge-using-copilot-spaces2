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

## UX Designer

### Role Summary
UX Designers ensure product experiences are usable, accessible, and consistent with customer needs. They convert product goals into interaction and interface guidance the delivery team can implement.

### Responsibilities
- Run discovery inputs (user interviews, journey mapping, usability feedback)
- Produce and iterate wireframes, prototypes, and interaction guidance
- Define UX acceptance considerations with Product Managers and QA
- Support design reviews during implementation to protect experience quality

### Goals
- Improve task success and user satisfaction
- Reduce rework caused by unclear interaction requirements
- Ensure accessibility and consistency across released experiences

### Typical Communication
- Collaborative design reviews with Developers and Product Managers
- Async design notes linked to backlog items and acceptance criteria
- Usability findings and recommendations shared with Stakeholders

### Interaction with Existing Roles
- **Developers:** Partner on feasibility, edge cases, and implementation details; clarify behavior for states, errors, and responsive layouts.
- **Product Managers:** Align UX decisions to customer outcomes, priorities, and success metrics.
- **Project Managers:** Coordinate design milestones, dependencies, and scope trade-offs in delivery plans.
- **QA/Testing:** Translate design intent into testable UX acceptance criteria (flows, accessibility, copy, and interaction behavior).
- **Stakeholders:** Present design rationale and trade-offs to support timely decisions and approvals.

---

## QA Lead

### Role Summary
QA Leads define and coordinate the quality strategy across planning, execution, and release. They ensure quality risks are visible early and validated before shipment.

### Responsibilities
- Define test strategy, scope, and quality gates for each milestone
- Coordinate manual and automated testing coverage with Developers
- Lead defect triage and prioritize remediation with PM/PdM input
- Track quality metrics (defect trends, escaped defects, test pass rates)

### Goals
- Prevent critical defects from reaching production
- Build repeatable quality practices across teams
- Shorten feedback loops between build and validation

### Typical Communication
- Test plan walkthroughs during planning and pre-release checkpoints
- Daily defect/status updates in delivery channels
- Quality risk summaries in stakeholder status reports

### Interaction with Existing Roles
- **Developers:** Align on testability, test data, and fix validation; provide rapid feedback on regressions.
- **Product Managers:** Confirm acceptance criteria are measurable and complete for validation.
- **Project Managers:** Report quality risks, testing progress, and release readiness impacts.
- **QA/Testing:** Coach contributors on standards, coverage expectations, and execution sequencing.
- **Stakeholders:** Communicate quality posture, known risks, and mitigation plans before go/no-go decisions.

---

## Release Manager

### Role Summary
Release Managers coordinate the operational path to production. They ensure releases are planned, verified, communicated, and recoverable.

### Responsibilities
- Own release calendar, cutover plans, and rollout sequencing
- Verify release readiness checklists, approvals, and rollback plans
- Coordinate cross-team dependencies during deployment windows
- Lead release communications before, during, and after deployment

### Goals
- Deliver predictable, low-risk releases
- Improve release transparency and decision readiness
- Reduce deployment incidents and recovery time

### Typical Communication
- Release readiness reviews with PM, QA Lead, and engineering owners
- Deployment window updates in shared channels
- Post-release summaries with status, incidents, and follow-up actions

### Interaction with Existing Roles
- **Developers:** Confirm deployment prerequisites, runbooks, and on-call expectations.
- **Product Managers:** Align release timing with customer commitments and launch messaging.
- **Project Managers:** Integrate release milestones, risks, and approvals into project plans.
- **QA/Testing:** Gate release progression based on completed validation and documented risk acceptance.
- **Stakeholders:** Provide go-live readiness, decision checkpoints, and post-release outcome updates.

---

## Business Analyst

### Role Summary
Business Analysts translate business needs into clear, testable requirements. They reduce ambiguity between stakeholder intent and team execution.

### Responsibilities
- Elicit requirements, constraints, and process dependencies
- Document functional and non-functional requirements
- Maintain traceability from requirements to backlog items and outcomes
- Support impact analysis for change requests and scope decisions

### Goals
- Improve requirement quality and reduce delivery ambiguity
- Accelerate decision-making with clear analysis
- Increase alignment between business goals and implementation scope

### Typical Communication
- Requirement workshops with Stakeholders, Product Managers, and PMs
- Clarification notes attached to backlog items and planning artifacts
- Change-impact summaries for decision forums

### Interaction with Existing Roles
- **Developers:** Clarify business rules, edge cases, and acceptance boundaries.
- **Product Managers:** Refine requirements into prioritized, outcome-oriented backlog items.
- **Project Managers:** Surface requirement dependencies and scope implications for schedule planning.
- **QA/Testing:** Help convert requirements into test scenarios and traceable acceptance criteria.
- **Stakeholders:** Gather intent, validate assumptions, and confirm requirement sign-off decisions.

---

## Scrum Master

### Role Summary
Scrum Masters facilitate team flow and continuous improvement in Agile delivery. They remove impediments and keep ceremonies outcome-focused.

### Responsibilities
- Facilitate planning, daily standups, reviews, and retrospectives
- Remove delivery impediments and escalate blockers when needed
- Coach teams on Agile practices, estimation, and work-in-progress limits
- Partner with PM/PdM on predictable cadence and healthy backlog flow

### Goals
- Improve team predictability and throughput
- Reduce blocked work and context-switching
- Strengthen continuous improvement habits

### Typical Communication
- Ceremony facilitation and follow-up action tracking
- Blocker escalation updates to PM/PdM and dependent teams
- Team health and process improvement insights in retrospectives

### Interaction with Existing Roles
- **Developers:** Protect focus time, improve sprint commitment quality, and resolve process blockers quickly.
- **Product Managers:** Keep backlog refinement and planning aligned to delivery capacity and priorities.
- **Project Managers:** Coordinate schedule risks, dependency management, and escalation timing.
- **QA/Testing:** Ensure testing work is integrated into sprint planning and Definition of Done execution.
- **Stakeholders:** Set expectations on delivery cadence, inspect/adapt outcomes, and transparent progress signals.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
