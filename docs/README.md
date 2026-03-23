# OctoAcme Project Management Docs

> This README provides immediate orientation for contributors and consumers of OctoAcme's project management documentation. Its goal is to make institutional knowledge **accessible, centralized, and searchable** — reducing onboarding friction for new team members and ensuring every process has a clear, discoverable home.
>
> _Tracked in [issue #2](https://github.com/kavyaganji/skills-scale-institutional-knowledge-using-copilot-spaces/issues/2)._

---

## Summary: Project Management at OctoAcme

OctoAcme follows a structured, five-phase project lifecycle designed to maximize customer value while maintaining transparency and adaptability. The approach begins with **Initiation**, where new ideas are validated against business needs and measurable outcomes through a lightweight Project One-pager. Once approved by stakeholders and sponsors, projects move into **Planning**, where work is broken into shippable increments with clear acceptance criteria, estimated scope, and a documented Definition of Done. The team then executes delivery through iterative sprints, manages risks and communications throughout, releases features to production using standardized checklists and rollback procedures, and concludes with retrospectives to capture learnings and drive continuous improvement.

Three primary roles anchor OctoAcme projects: **Project Managers** coordinate schedules, risks, and cross-team dependencies while maintaining transparency through project boards and status reports; **Product Managers** define what to build, prioritize the backlog, and measure success through data-driven metrics; and **Developers** implement features collaboratively, write tests, and help identify technical risks. The communication cadence includes daily standups focused on progress and blockers, weekly syncs between PM and Product Lead, twice-weekly delivery team standups, and monthly stakeholder updates. Risk escalation follows a three-level path: team-level triage → PM escalation to Product Lead → sponsor-level escalation for business-impacting issues. This multi-layered communication ensures alignment across engineering, product, and leadership while maintaining psychological safety and encouraging feedback.

OctoAcme enforces rigorous quality practices to ensure reliable delivery. Development workflows emphasize small, reviewable pull requests (≤400 lines when possible), automated CI testing and linting, and at least one required approval before merging. Quality assurance includes unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, security scanning in the CI pipeline, and manual QA for feature acceptance. The project board uses a standardized workflow with columns for Backlog, Ready, In Progress, In Review, QA, and Done. Pre-release activities include drafting release notes, documenting rollback plans, and running smoke tests on staging before production deployment. Velocity and burndown metrics are tracked continuously, while success metrics from the Project One-pager are monitored through dashboards measuring errors, latency, and usage — enabling data-informed decisions throughout execution and release cycles.

---

## Docs Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Concise introduction to OctoAcme's project management approach, roles, and key artifacts. The best starting point for new team members. |
| [Project Initiation Guide](octoacme-project-initiation.md) | Steps and deliverables for validating and authorizing new work, aligning stakeholders, and producing a lightweight Project One-pager. |
| [Project Planning](octoacme-project-planning.md) | How to turn an approved initiative into an actionable backlog — covering scope estimation, sprint planning, acceptance criteria, and the Definition of Done. |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day guidance for managing sprint execution, tracking progress on the project board, handling blockers, and escalating issues. |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | How to identify, log, prioritize, and communicate risks and dependencies, including escalation paths and stakeholder update templates. |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Standardized process for releasing features to production, including pre-release checklists, rollback procedures, and post-release monitoring. |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Framework for running sprint and project retrospectives, capturing learnings, and converting them into tracked improvement actions. |
| [Roles & Personas](octoacme-roles-and-personas.md) | Definitions of key roles in OctoAcme projects — Project Manager, Product Manager, Developer, QA, and Stakeholder — with responsibilities and expectations. |
