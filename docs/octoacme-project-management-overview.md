# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles
- **Project Manager (PM):** coordinates delivery, schedules, risk, communications.
- **Product Manager (PdM):** defines outcomes, prioritizes backlog, and measures success.
- **Developers:** implement features, collaborate on design and testability.
- **QA/Testing:** validate quality and acceptance criteria.
- **Stakeholders:** provide inputs and approvals.

## Extended Roles
These roles support specific aspects of the project lifecycle and may not be present on all projects:
- **Scrum Master:** facilitates agile ceremonies, removes blockers, coaches on best practices.
- **UX Designer:** designs and validates user experiences, ensures usability and consistency.
- **DevOps Engineer:** manages CI/CD pipelines, automates deployments, maintains infrastructure.
- **Business Analyst:** analyzes business needs, documents requirements, bridges stakeholder-technical gaps.
- **Support Lead:** represents customer support, channels feedback, coordinates post-release support.
- **Security/Compliance Officer:** enforces security policies, audits compliance, manages security risks.

**Reference:** Extended roles defined in response to [sai-sharvan/skills-scale-institutional-knowledge-using-copilot-spaces#4](https://github.com/sai-sharvan/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4)

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Lifecycle (high-level)
1. Initiation: problem statement, stakeholders, high-level timeline.
2. Planning: scope, resources, milestones, dependencies.
3. Execution: build, test, review, iterate.
4. Release: deploy, verify, announce.
5. Close & Retrospective: capture learnings and next steps.

## Communication Cadence
- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
- Use the [RACI Matrix Template](./octoacme-raci-matrix-template.md) to clarify role accountability
- Reference the [Cross-Role Handoff Checklist](./octoacme-handoff-checklist.md) during phase transitions
