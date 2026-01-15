# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
  - **DevOps Engineer:** Verifies CI/CD pipeline health and build status
  - **Security Officer:** Reviews and approves security scan results
- Release notes drafted
  - **Product Manager:** Provides feature descriptions and customer impact
  - **Support Lead:** Reviews release notes for support readiness
- Rollback / mitigation plan documented
  - **DevOps Engineer:** Prepares rollback procedures
- Smoke tests prepared
  - **QA Engineers:** Prepare and validate smoke test suite

**Reference:** Release process clarifications per [sai-sharvan/skills-scale-institutional-knowledge-using-copilot-spaces#4](https://github.com/sai-sharvan/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
  - **DevOps Engineer:** Executes deployment and monitors pipeline
- [ ] Run post-deploy verifications
  - **QA Engineers:** Execute smoke tests in production
  - **DevOps Engineer:** Verify system health metrics
- [ ] Announce release to stakeholders and support
  - **Support Lead:** Notified and prepared for customer inquiries
  - **Product Manager:** Communicates release to stakeholders

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
    - **DevOps Engineer:** Executes rollback procedures
    - **Support Lead:** Monitors customer impact and escalations
    - **Security Officer:** Involved if security incident is suspected
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items
    - **Scrum Master:** Facilitates post-incident retrospective

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:

## Related Templates
- [Cross-Role Handoff Checklist](./octoacme-handoff-checklist.md) - Execution-to-release and release-to-post-release handoffs
- [RACI Matrix Template](./octoacme-raci-matrix-template.md) - Release phase responsibilities
