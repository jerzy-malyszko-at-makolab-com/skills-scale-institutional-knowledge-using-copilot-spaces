# OctoAcme — Project Management Process Docs

This folder contains OctoAcme's project management process documentation. It serves as a centralized, versioned knowledge base for all team members — from new joiners onboarding to experienced contributors looking for process guidance.

---

## Overview of OctoAcme's Project Management Processes

OctoAcme follows a structured five-phase project lifecycle: **Initiation, Planning, Execution, Release, and Close & Retrospective**. Initiation begins with a lightweight Project One-pager capturing the problem statement, SMART goals, success metrics, and a stakeholder list — and a formal decision gate ensures alignment before moving forward. During Planning, the team holds a kickoff, builds a prioritized backlog with clear acceptance criteria, defines a Definition of Done (DoD), and produces a release plan and milestone map. Execution is tracked via a project board (e.g., GitHub Projects) with columns from Backlog through Done, with small pull requests (≤400 lines) tied to issues, CI-enforced tests and linting, and at least one required approval before merging.

Three core personas drive delivery at OctoAcme. The **Project Manager (PM)** owns delivery coordination, timelines, risk management, and cross-team communication. The **Product Manager (PdM)** defines the product vision, prioritizes the backlog, and measures outcomes using data and user research. **Developers** implement features and collaborate on design and testability, while a dedicated **QA/Testing** function validates quality and acceptance criteria. Stakeholders provide inputs and approvals throughout the lifecycle. Each role has clearly defined responsibilities and communication expectations to ensure ownership and accountability on every project.

OctoAcme maintains a regular communication cadence with twice-weekly standups, a weekly PM + PdM sync, monthly stakeholder updates, and ad-hoc escalations as needed. Risks are tracked in a structured **Risk Register** (capturing ID, description, impact, likelihood, owner, mitigation, and status) and reviewed during weekly syncs. Escalation follows a tiered path: team-level triage in standups (Level 1), PM escalation to the Product Lead and dependent teams (Level 2), and sponsor-level escalation for business-impacting issues (Level 3). Stakeholder communications use standardized weekly status templates covering progress, next steps, risks/blockers, and decisions needed.

Quality is embedded throughout execution: unit tests, integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance. Releases are categorized as Patch, Minor, or Major and require all acceptance criteria to be met, passing CI and security scans, drafted release notes, and a rollback plan before deployment. After each sprint, release, or milestone, the team runs a **retrospective** (timeboxed at 45–75 minutes) using a "what went well / what could be improved / action items" structure. Improvement actions are added to the backlog with clear owners and timelines, and their impact is measured to foster a culture of iterative, data-informed continuous improvement.

---

## Table of Contents

| Document | Description |
|---|---|
| [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) | High-level introduction to OctoAcme's project approach, roles, and artifacts |
| [octoacme-project-initiation.md](./octoacme-project-initiation.md) | Steps to validate and authorize new work, align stakeholders, and create a lightweight plan |
| [octoacme-project-planning.md](./octoacme-project-planning.md) | Converting an approved initiative into an actionable backlog and release plan |
| [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md) | Day-to-day execution guidance, PR workflow, quality checks, and blocker escalation |
| [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md) | Risk register, stakeholder communication cadence, and communication templates |
| [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md) | Release types, deployment checklist, rollback playbook, and release notes template |
| [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md) | Running retrospectives and tracking continuous improvement actions |
| [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) | Detailed role definitions for Developers, Product Managers, and Project Managers |
