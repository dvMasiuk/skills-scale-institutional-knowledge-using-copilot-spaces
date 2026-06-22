# OctoAcme Project Management Processes

OctoAcme follows a customer-first, iterative project management approach with clear ownership, measurable outcomes, and a lightweight set of artifacts to ensure consistent delivery. These docs serve as the single-source reference for initiation, planning, execution, release, risk management, retrospectives, and roles.

## Brief overview

- Initiation: Capture the problem, objective, success metrics, stakeholders, and a high-level timeline in a Project One-pager and pass a decision gate before planning.
- Planning: Break approved work into a prioritized backlog with acceptance criteria, estimate scope, define a Definition of Done, and map releases/milestones.
- Execution & Review: Use the project board (Backlog → Ready → In Progress → In Review → QA → Done) and small PRs that include acceptance criteria; run CI tests and security scans before reviews and require approvals per team policy.
- Release & QA: Follow pre-release checklists (staging smoke tests, automated pipelines, rollback plans), run unit/integration/e2e tests and manual QA as needed, and use an incident playbook for failures.
- Continuous improvement & Risk: Run retrospectives to produce tracked action items, maintain a risk register with owners and mitigations, and follow defined escalation paths for blockers and incidents.

## Docs

- octoacme-project-management-overview.md
- octoacme-project-initiation.md
- octoacme-project-planning.md
- octoacme-execution-and-tracking.md
- octoacme-release-and-deployment.md
- octoacme-retrospective-and-continuous-improvement.md
- octoacme-risks-and-communication.md
- octoacme-roles-and-personas.md

## How to propose changes

To propose updates or add new process documents, open an issue using the "Add Content to Project Management Process Docs" template:
.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml

## Location

This README lives at: docs/README.md
