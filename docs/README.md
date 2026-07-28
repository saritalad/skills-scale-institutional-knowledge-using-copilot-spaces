# OctoAcme Project Management Docs

This README centralizes OctoAcme's project management process documents and provides quick links and a short summary of each process to help teams discover and use them.

## Project management processes (brief summary)

OctoAcme follows a lightweight, iterative project management approach that emphasizes clear initiation, deliberate planning, frequent execution checkpoints, and continuous improvement. Initiation focuses on a one-pager to validate the business need and define measurable success criteria. Planning breaks approved initiatives into a prioritized backlog, estimates scope, defines a Definition of Done (DoD), and captures risks and dependencies in a Risk Register to prepare a release plan and milestone map.

Execution emphasizes short iterations, small pull requests, and CI gates to keep work shippable and reviewable. Teams track work on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and follow a PR workflow that links to issues, includes acceptance criteria, runs automated tests and linting, and requires approvals before merging. Regular ceremonies—daily standups, weekly delivery syncs, and end-of-sprint or milestone demos—make progress and blockers visible.

Roles and responsibilities are explicitly defined: Product Managers (PdM) set outcomes and success metrics; Project Managers (PM) coordinate delivery, schedules, risks, and communication; Developers implement and test features; QA validates acceptance and quality. Communication cadence includes PM+PdM weekly alignment, twice-weekly or daily standups for the delivery team, monthly stakeholder updates, and ad-hoc escalations for critical issues.

Quality assurance practices include unit and integration testing, end-to-end smoke tests for critical flows, CI-based security scanning, and manual QA when needed. Releases follow pre-release checklists, rollback plans, and post-deploy verifications. Incidents trigger the incident playbook and blameless retrospectives to capture action items and improvements.

## Documents

- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](docs/octoacme-roles-and-personas.md)

## How to use

- Add this README to the `docs/` folder as `README.md`.
- Keep each process doc updated; link back to this README from each doc's top-level header if helpful.
- Use the repository issue template "Add Content to Project Management Process Docs" to propose edits or new documents.
