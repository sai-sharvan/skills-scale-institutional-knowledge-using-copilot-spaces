# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
  - **Scrum Master:** Facilitates standup and tracks action items
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone
  - **UX Designer:** Validates implementation against design specifications
  - **Business Analyst:** Confirms business requirements are met

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Quality Assurance Roles and Responsibilities
- **QA Engineers:** Execute test plans, validate acceptance criteria, report defects
- **DevOps Engineer:** Maintain automated test infrastructure and CI/CD pipeline quality gates
- **Security Officer:** Review security test results and vulnerability scans
- **UX Designer:** Conduct usability testing and validate user experience
- **Support Lead:** Provide feedback on production issues to inform test scenarios

**Reference:** Quality assurance process improvements per [sai-sharvan/skills-scale-institutional-knowledge-using-copilot-spaces#4](https://github.com/sai-sharvan/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4)

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
  - **Scrum Master:** Facilitates blocker discussion and tracks resolution
- Level 2: PM escalates to Product Lead and dependent teams
  - **DevOps Engineer:** Escalates infrastructure and deployment blockers
  - **Security Officer:** Escalates security and compliance blockers
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly

## Related Templates
- [Cross-Role Handoff Checklist](./octoacme-handoff-checklist.md) - Reference execution-to-release handoffs
- [RACI Matrix Template](./octoacme-raci-matrix-template.md) - Clarify execution phase responsibilities
