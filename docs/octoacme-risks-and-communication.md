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
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support, security, UX)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status
- Include Support/Customer Advocate in release communications
- Notify Security Champion of any security-related changes or incidents

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

Security Incident Communication
- Severity and impact assessment (Security Champion leads)
- Affected systems and user impact
- Immediate containment actions taken
- Investigation status and timeline
- Communication to affected users (coordinated with Support/Customer Advocate)
- Post-incident security review and remediation plan

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security Champion and Security on-call immediately
- For user-impacting issues, coordinate with Support/Customer Advocate for customer communication
- For technical architecture decisions requiring escalation, involve Technical Lead/Architect

---

*Reference: Risk and communication processes updated to include expanded roles per [Issue #4](https://github.com/MaximCalpacci/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4)*
