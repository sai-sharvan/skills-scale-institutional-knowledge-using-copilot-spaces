# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call
  - **Security Officer:** Leads security incident response and coordinates with stakeholders
- For infrastructure or deployment issues:
  - **DevOps Engineer:** Coordinates technical response and provides impact assessment
- For customer-impacting issues:
  - **Support Lead:** Provides customer impact data and coordinates external communication

**Reference:** Enhanced escalation paths per [sai-sharvan/skills-scale-institutional-knowledge-using-copilot-spaces#4](https://github.com/sai-sharvan/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4)
