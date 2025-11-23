# OctoAcme Project Management Docs

Welcome! This README provides a guide and directory for OctoAcme's project management processes and links to the process documents stored in this repository.

OctoAcme follows a structured, iterative approach to delivering cross-functional projects. Work begins with a lightweight initiation (a Project One-pager to capture the problem, goals, stakeholders, and success metrics), proceeds through collaborative planning (kickoffs, prioritized backlogs, and a Definition of Done), and continues with execution in short increments using a team project board and disciplined PR workflow. Releases follow predefined checks, smoke tests, and rollback plans to reduce risk.

Teams operate with clearly defined personas: Project Managers coordinate delivery and communication; Product Managers own outcomes and prioritization; developers implement and test; and QA validates acceptance criteria. Regular cadences (daily standups, weekly delivery syncs, demos, and monthly stakeholder updates) keep teams aligned and provide structured escalation paths for blockers and incidents.

Quality assurance and risk management are integrated across the lifecycle. QA practices include unit and integration tests, CI security scanning, end-to-end smoke testing for critical flows, and manual QA where needed. Risks are tracked in a simple register and reviewed regularly, and releases require passing CI, security scans, release notes, and rollback plans.

## Process Documentation Index

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

## How to use these docs

- Keep the Project Charter / One-pager updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
- To propose changes to these process documents, use the issue template at `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`.

## Acceptance Criteria

- [ ] Content aligns with existing process docs
- [ ] README provides clear navigation for docs/ folder
- [ ] README added to docs/ folder and referenced in issue #4 (Refs #4)
