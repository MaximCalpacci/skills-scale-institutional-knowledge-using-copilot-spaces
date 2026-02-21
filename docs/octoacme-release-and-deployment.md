# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- QA sign-off on test execution and acceptance validation
- Passing CI and security scans (Security Champion review completed)
- UX validation for user-facing changes (UX/UI Designer approval)
- Technical architecture review for significant changes (Technical Lead/Architect)
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared
- Support team briefed on changes and potential customer impact

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] QA final validation completed
- [ ] Security review sign-off obtained
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications (QA + Technical Lead)
- [ ] Announce release to stakeholders and support team
- [ ] Monitor for errors and user feedback (Support/Customer Advocate)

---

*Reference: Release process updated to include expanded roles per [Issue #4](https://github.com/MaximCalpacci/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4)*

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
