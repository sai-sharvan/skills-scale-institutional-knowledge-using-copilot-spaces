# OctoAcme Project Management Process Documentation

This directory contains the source-of-truth process documents for how OctoAcme runs projects. These docs define our project lifecycle, roles, artifacts, and workflows—and serve as context for Copilot Spaces to help teams work consistently and efficiently. Whether you're starting a new project or need a quick reference, these guides provide a lightweight, iterative approach to delivery.

## Overview

OctoAcme runs projects with a lightweight, iterative lifecycle: **Initiation** (one-pager to confirm problem, goals, stakeholders, and go/no-go), **Planning** (kickoff, prioritized backlog, estimates, Definition of Done, and release milestones) and **Execution/Release** (work split into shippable increments, tracked through a project board, then released with verification and rollback plans). The approach is grounded in principles such as customer-first delivery, clear ownership (named PM and Product Lead), data-informed decisions, and psychological safety.

Workflows emphasize clear, small, reviewable increments: use a project board with columns (Backlog → Ready → In Progress → In Review → QA → Done), a formal backlog item template (title, acceptance criteria, estimate, owner), timeboxed sprint planning, and a PR workflow that requires small PRs, CI (tests + lint + security scans), an issue link and acceptance criteria in the PR, and at least one approval before merging. Planning artifacts include the One-pager, release plan, and a Risk Register to track cross-team dependencies and mitigation actions.

Communication is structured and regular: short daily standups for progress and blockers, weekly delivery syncs and PM+PdM alignment, demo/review at sprint end, and monthly stakeholder updates. The docs provide templates (e.g., Weekly Status) and a clear escalation path (team → PM → Product Lead → Sponsor), plus a separate security incident path. Stakeholder communication is centralized via a single source of truth (project README or release docs) and action items from retrospectives are tracked back into the backlog.

Quality assurance and release controls are baked into the flow: unit and integration tests for new logic, end-to-end smoke tests for critical flows, CI security scanning, and manual QA when needed. Releases follow a checklist (staging smoke tests, automated pipelines where possible, post-deploy verification) and include rollback/incident playbooks and release notes templates. Continuous improvement is enforced via regular retrospectives that produce prioritized action items tracked into the backlog.

## Key Artifacts and Documents

The following process documents provide detailed guidance for each phase of the project lifecycle:

- **[octoacme-project-management-overview.md](octoacme-project-management-overview.md)** - High-level introduction to OctoAcme's project management approach, principles, roles, and lifecycle
- **[octoacme-roles-and-personas.md](octoacme-roles-and-personas.md)** - Detailed role definitions and responsibilities for all team members
- **[octoacme-project-initiation.md](octoacme-project-initiation.md)** - How to start a project: problem statement, stakeholders, one-pager, and go/no-go decision
- **[octoacme-project-planning.md](octoacme-project-planning.md)** - Planning phase: kickoff, backlog prioritization, estimates, Definition of Done, and release milestones
- **[octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md)** - Execution workflows: project board, backlog item template, sprint planning, and PR workflow
- **[octoacme-release-and-deployment.md](octoacme-release-and-deployment.md)** - Release process: checklists, verification, rollback plans, and release notes
- **[octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md)** - Retrospectives, action items, and continuous improvement practices
- **[octoacme-risks-and-communication.md](octoacme-risks-and-communication.md)** - Risk management, escalation paths, and communication cadence (standups, syncs, stakeholder updates)

## Templates and Tools

The following templates support clear accountability and smooth collaboration across roles:

- **[octoacme-raci-matrix-template.md](octoacme-raci-matrix-template.md)** - RACI (Responsible, Accountable, Consulted, Informed) matrix for defining role accountability across project activities
- **[octoacme-handoff-checklist.md](octoacme-handoff-checklist.md)** - Cross-role handoff checklist to prevent gaps and ensure smooth transitions between project phases

**Reference:** Templates added to address collaboration gaps identified in [sai-sharvan/skills-scale-institutional-knowledge-using-copilot-spaces#4](https://github.com/sai-sharvan/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4)

## How to Propose Changes

If you have suggestions to improve these process documents—whether it's clarifying a workflow, adding a new template, or closing a gap—please [open a new issue](https://github.com/sai-sharvan/skills-scale-institutional-knowledge-using-copilot-spaces/issues/new/choose) and select the "Add Content to Project Management Process Docs" template.

Your feedback helps us continuously improve our project management practices and keep these docs relevant and useful for the entire team.
