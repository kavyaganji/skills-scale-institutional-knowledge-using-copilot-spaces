# OctoAcme — Role Onboarding & Handoff Checklist

This document provides practical checklists and templates to support onboarding new team members, clarifying role boundaries, and managing hand-offs across the project lifecycle.

---

## New Team Member Onboarding Checklist

Use this checklist when a new person joins any role on an OctoAcme project.

### All Roles
- [ ] Review [OctoAcme Project Management Overview](octoacme-project-management-overview.md)
- [ ] Read [Roles & Personas](octoacme-roles-and-personas.md) — especially your own role and adjacent roles
- [ ] Get added to the project communication channels (Slack, Teams, etc.)
- [ ] Receive access to the project repository and relevant tooling
- [ ] Schedule 1:1 introductions with the Project Manager and Product Manager
- [ ] Review the current sprint backlog and in-progress work
- [ ] Review the risk register and open blockers

### Developer
- [ ] Set up local development environment (follow repo README)
- [ ] Complete first PR with a minor change or fix to learn the review process
- [ ] Review CI/CD pipeline configuration with DevOps Engineer

### UX Designer
- [ ] Access design tool and shared component library
- [ ] Review existing wireframes, mockups, and design guidelines
- [ ] Meet with Product Manager to align on current user research findings

### DevOps Engineer
- [ ] Review infrastructure-as-code and deployment runbooks
- [ ] Get access to monitoring dashboards and alerting tools
- [ ] Shadow an on-call rotation or incident review

### Business Analyst
- [ ] Review backlog and any existing requirements documents
- [ ] Meet with Product Manager and key stakeholders for context
- [ ] Identify any undocumented requirements or process gaps

### Customer Support Lead
- [ ] Access support ticketing system and review open tickets
- [ ] Review escalation procedures and known issue list
- [ ] Meet with Product Manager to understand recent releases and upcoming changes

---

## Stakeholder Mapping Template

Use this template at project initiation to identify and plan communication for all relevant stakeholders.

| Stakeholder | Role / Group | Interest / Concern | Communication Frequency | Owner |
|---|---|---|---|---|
| _Name_ | _e.g., Engineering Lead_ | _e.g., Technical feasibility_ | _e.g., Weekly sync_ | _PM_ |
| _Name_ | _e.g., Business Sponsor_ | _e.g., Budget and timeline_ | _e.g., Monthly update_ | _PM_ |
| _Name_ | _e.g., Support Team_ | _e.g., Release readiness_ | _e.g., Per release_ | _Customer Support Lead_ |

---

## Role Hand-off Checklist

Use this checklist when transferring work between roles (e.g., design to development, development to QA, QA to release).

### Design → Development Hand-off
- [ ] Annotated mockups or design specs shared in the project repository
- [ ] Design reviewed and accepted by Product Manager
- [ ] Open design questions documented and assigned
- [ ] Accessibility requirements noted
- [ ] Developer walkthrough session scheduled or completed

### Development → QA / Testing Hand-off
- [ ] Feature branch deployed to staging environment
- [ ] Acceptance criteria reviewed with QA
- [ ] Known issues or limitations documented
- [ ] Test data requirements communicated

### QA / Testing → Release Hand-off
- [ ] All acceptance criteria validated and signed off
- [ ] Regression tests passed
- [ ] Release notes drafted and reviewed by Product Manager
- [ ] DevOps Engineer notified of release readiness

### Release → Customer Support Hand-off
- [ ] Release notes shared with Customer Support Lead before deployment
- [ ] Known issues or limitations communicated to Support
- [ ] Rollback plan confirmed with DevOps Engineer
- [ ] Incident communication templates prepared (if high-risk release)

---

## Persona–Responsibilities Matrix

Quick reference for which role is responsible (R), accountable (A), consulted (C), or informed (I) for key project activities.

| Activity | Project Manager | Product Manager | Developer | UX Designer | DevOps Engineer | Business Analyst | Customer Support Lead |
|---|---|---|---|---|---|---|---|
| Define project scope | A | R | C | C | C | C | I |
| Prioritize backlog | C | A/R | C | C | I | C | C |
| Requirements gathering | C | A | I | C | I | R | C |
| UI/UX design | I | C | C | R/A | I | C | I |
| Implementation | C | I | R/A | C | C | I | I |
| CI/CD & deployments | I | I | C | I | R/A | I | I |
| QA & acceptance testing | C | A | R | C | C | C | I |
| Release communication | A | C | I | I | C | I | R |
| Post-release support | C | C | C | I | C | I | R/A |
| Retrospective | A | R | R | R | R | R | R |

**Key:** R = Responsible, A = Accountable, C = Consulted, I = Informed

---

## Related Documents
- [Roles & Personas](octoacme-roles-and-personas.md)
- [Project Management Overview](octoacme-project-management-overview.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
