# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Security Review (if needed), Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)
  - For security-sensitive changes, request Security Champion review
  - For UX changes, attach screenshots and request UX/UI Designer review
  - QA validation completed before marking as Done

## Quality & Testing
- Unit tests for new logic (Developer responsibility)
- Integration tests where applicable (Developer + QA collaboration)
- End-to-end smoke tests for critical flows before release (QA/Tester)
- Security scanning in CI (Security Champion monitors and triages)
- Manual QA for feature acceptance when needed (QA/Tester)
- UX validation against design specifications (UX/UI Designer + QA)
- Accessibility testing for user-facing features (UX/UI Designer + QA)
- Performance testing for critical paths (Technical Lead/Architect guidance)

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests, lint, and security scans
- [ ] QA test plans created and maintained
- [ ] Security review process established for sensitive changes
- [ ] UX design specifications available and accessible
- [ ] Regular demos scheduled (include UX, QA, and stakeholders)
- [ ] Risk register updated weekly
- [ ] Support team informed of upcoming changes

---

*Reference: Execution process updated to include expanded roles per [Issue #4](https://github.com/MaximCalpacci/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4)*
