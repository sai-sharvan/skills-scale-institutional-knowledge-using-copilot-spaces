# OctoAcme RACI Matrix Template

## Purpose
Define clear accountability and collaboration patterns across project roles using the RACI framework (Responsible, Accountable, Consulted, Informed).

**Reference:** This template addresses role accountability gaps identified in [sai-sharvan/skills-scale-institutional-knowledge-using-copilot-spaces#4](https://github.com/sai-sharvan/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4)

## RACI Key
- **R** (Responsible): Does the work to complete the task
- **A** (Accountable): Ultimately answerable for the task's completion and has authority to approve
- **C** (Consulted): Provides input and expertise (two-way communication)
- **I** (Informed): Kept up-to-date on progress (one-way communication)

## Project Lifecycle RACI Matrix

| Activity | PM | PdM | Dev | QA | Scrum Master | UX Designer | DevOps | BA | Support Lead | Security Officer |
|----------|----|----|-----|----|--------------|--------------|---------|----|--------------|---------------------|
| **Initiation Phase** |
| Define project charter | R | A | I | I | C | I | I | C | I | I |
| Business requirements analysis | C | C | I | I | I | I | I | R/A | I | I |
| Initial security review | C | C | I | I | I | I | I | I | I | R/A |
| User research | I | C | I | I | I | R/A | I | C | I | I |
| **Planning Phase** |
| Backlog prioritization | C | A | C | C | C | C | I | C | I | I |
| Sprint planning | C | C | R | C | A | I | I | I | I | I |
| Design specifications | I | C | C | I | C | R/A | I | C | I | I |
| Test plan creation | C | I | C | R/A | I | I | I | I | I | C |
| Infrastructure planning | C | I | C | I | I | I | R/A | I | I | I |
| Security requirements | C | C | C | I | I | I | C | I | I | R/A |
| **Execution Phase** |
| Daily standup facilitation | C | I | R | R | A | I | R | I | I | I |
| Feature development | I | C | R/A | I | C | C | C | I | I | I |
| Code review | I | I | R/A | C | I | C | C | I | I | C |
| Design implementation review | I | I | R | I | I | A | I | I | I | I |
| QA testing | I | I | C | R/A | I | C | I | I | I | I |
| Security scanning | I | I | C | C | I | I | C | I | I | R/A |
| CI/CD pipeline maintenance | I | I | C | C | I | I | R/A | I | I | I |
| **Release Phase** |
| Release planning | R/A | C | C | C | C | I | C | I | C | C |
| Deployment execution | C | I | C | C | I | I | R/A | I | I | I |
| Smoke testing | I | I | C | R | I | I | C | I | I | I |
| Release notes | C | R | C | I | I | I | I | I | A | I |
| Support preparation | C | I | I | C | I | I | I | I | R/A | I |
| **Post-Release** |
| Production monitoring | C | I | C | C | I | I | R/A | I | C | C |
| Customer feedback collection | I | C | I | I | I | I | I | I | R/A | I |
| Incident response | C | I | R | C | C | I | R | I | C | A* |
| Retrospective facilitation | C | C | R | R | A | R | R | R | R | R |

*Security Officer is Accountable for security incidents specifically

## How to Use This Template
1. Copy this matrix at the start of each major project
2. Customize based on actual team composition and project needs
3. Review and confirm RACI assignments during project kickoff
4. Reference during handoffs to clarify who should be involved
5. Update if roles or responsibilities change during the project

## Best Practices
- Each activity should have exactly one "A" (Accountable) person
- Avoid too many "C" (Consulted) roles per activity — causes decision bottlenecks
- Use "I" (Informed) for stakeholders who need visibility but not active participation
- Review RACI matrix during retrospectives to identify responsibility gaps
