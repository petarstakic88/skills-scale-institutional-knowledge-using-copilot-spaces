# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management documentation hub. This README serves as the landing page and navigation guide for all process documents in this folder.

## Overview

OctoAcme runs projects with an iterative, outcome-focused approach that begins with a lightweight initiation (a Project One-pager) and moves through planning, execution, release, and retrospective stages. The lifecycle emphasizes clear ownership (named PM and Product Lead), measurable success criteria, and a set of core artifacts—project charters, roadmaps, acceptance criteria, and a risk register—that serve as the single source of truth. Work only advances from initiation to planning once success metrics, stakeholder alignment, and team availability are confirmed.

Day-to-day delivery is organized around a simple project-board workflow (**Backlog → Ready → In Progress → In Review → QA → Done**) and disciplined sprint planning: prioritize a backlog with acceptance criteria, estimate scope, and use a documented Definition of Done. The pull-request process encourages small PRs, links to issues and acceptance criteria, automated CI checks (tests and linting), and at least one reviewer approval before merging. Planning and execution checklists (kickoff, release timeline, DoD, CI, and branching conventions) reduce ambiguity and speed handoffs.

Roles and responsibilities are explicit: Product Managers own the vision, outcomes, and prioritization; Project Managers coordinate schedules, risks, and communications; Developers build and test features; QA validates acceptance criteria; and stakeholders provide input and approvals. Each persona has clear responsibilities, which reduces single-person dependency and clarifies escalation paths when blockers arise.

Communication and quality assurance are central. The team uses a regular cadence (daily standups, weekly delivery syncs, sprint demos, and monthly stakeholder updates) plus templates for status and incident communications. QA combines automated practices (unit, integration, and security scans in CI; smoke tests) with manual validation where needed, and a deployment checklist and rollback playbook guard releases. Retrospectives after sprints, releases, or incidents capture action items and feed continuous improvement back into the backlog and process docs.

---

## Quick Navigation

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level overview of the OctoAcme project management approach |
| [Project Initiation](octoacme-project-initiation.md) | Project One-pager, success metrics, and stakeholder alignment |
| [Project Planning](octoacme-project-planning.md) | Roadmaps, sprint planning, and Definition of Done |
| [Execution and Tracking](octoacme-execution-and-tracking.md) | Project-board workflow, PR process, and delivery checklists |
| [Risks and Communication](octoacme-risks-and-communication.md) | Risk register, communication cadence, and status templates |
| [Release and Deployment](octoacme-release-and-deployment.md) | Deployment checklist, release timeline, and rollback playbook |
| [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Sprint and release retrospectives, action items, and process updates |
| [Roles and Personas](octoacme-roles-and-personas.md) | Responsibilities for PMs, Project Managers, Developers, QA, and Stakeholders |

---

## How to Use This Documentation

- **New team members** – Start with the [Project Management Overview](octoacme-project-management-overview.md) and [Roles and Personas](octoacme-roles-and-personas.md) to understand the process and your responsibilities.
- **Starting a new project** – Follow the [Project Initiation](octoacme-project-initiation.md) and [Project Planning](octoacme-project-planning.md) guides in order.
- **During delivery** – Refer to [Execution and Tracking](octoacme-execution-and-tracking.md) for the day-to-day workflow and PR process.
- **Preparing a release** – Use the [Release and Deployment](octoacme-release-and-deployment.md) checklist and rollback playbook.
- **After a sprint or release** – Run a retrospective using the [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) guide.
- **Managing risks or communications** – See [Risks and Communication](octoacme-risks-and-communication.md) for templates and escalation paths.

---

## Contributing

Found an error or have a suggestion for improving the process docs? Please use the [issue template](.github/ISSUE_TEMPLATE) to open an issue describing the proposed update. Include the document name, the section to change, and the reason for the update. All process doc changes are reviewed by the Project Management team before merging.
