# OctoAcme Project Management Docs — README

Welcome! This README serves as the entry point and overview for all OctoAcme project management process documents in this repository.

## How OctoAcme Manages Projects (Summary)

OctoAcme follows a structured five-phase project lifecycle: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. The approach emphasizes customer-first delivery through iterative increments, clear ownership structures, and data-informed decision-making. Each project operates under a lightweight governance model anchored by a Project One-pager that captures the business problem, goals, success metrics, stakeholders, and initial risks. Projects move through decision gates at each phase—most critically at initiation, where success metrics clarity, stakeholder alignment, and team availability must be confirmed before advancing to planning.

OctoAcme operates with clearly defined personas: **Project Managers** coordinate delivery, manage risks and schedules, and ensure stakeholder alignment; **Product Managers** define what should be built, prioritize the backlog, and measure outcomes; **Developers** implement features, collaborate on design, and identify technical risks; and **QA/Testing** validate quality and acceptance criteria. Communication is structured and frequent—weekly syncs between PM and Product Manager, twice-weekly standups for delivery teams, monthly stakeholder updates, and ad-hoc escalations for blockers. The escalation path is clearly defined: team-level triage → PM → Product Lead → Sponsor, with security incidents following a dedicated runbook.

Execution relies on a standardized pull request workflow (small PRs ≤400 lines), GitHub Projects board (Backlog → Ready → In Progress → In Review → QA → Done), and automated CI/CD with testing and security scanning. Quality assurance combines unit tests, integration tests, end-to-end smoke tests, security scans, and manual QA for feature acceptance. Risk management is integrated throughout the project lifecycle via a Risk Register maintained and reviewed weekly. The delivery approach emphasizes daily standups for progress tracking, sprint-based planning with clear Definition of Done, and regular demos. Post-release, retrospectives capture learnings and convert them into actionable improvements tracked through the project backlog, ensuring continuous organizational learning and process refinement.

### Key Principles

- **Customer-first and iterative delivery** — deliver small, testable increments
- **Defined ownership** — each project has a named Project Manager and Product Lead
- **Data-informed decisions** — measure impact and iterate based on evidence
- **Psychological safety** — encourage feedback and learning
- **Standard artifacts** — charter, roadmap, risk register, retrospective notes

## Process Documents

Navigate to each document below for detailed guidance on specific project management activities:

- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to roles, key artifacts, and lifecycle phases
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Validate and authorize work, align stakeholders, create a lightweight plan
- **[Project Planning](octoacme-project-planning.md)** — Break work into shippable increments, identify dependencies, align timelines
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day delivery, team rhythm, PR workflows, quality practices
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks and dependencies
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardize releases, deployment checklists, rollback procedures
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings, convert to actionable improvements
- **[Roles and Personas](octoacme-roles-and-personas.md)** — Detailed definitions of Developers, Product Managers, and Project Managers

## How to Use These Docs

- **New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md)
- **Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md)
- **In active delivery?** Reference the [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risk Management & Communication](octoacme-risks-and-communication.md) docs
- **Preparing to release?** Use the [Release & Deployment Guide](octoacme-release-and-deployment.md)
- **Improving the process?** Review the [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) doc

Keep the Project Charter updated in your project repo, and add process-specific docs to `.copilot/` if you want Copilot Spaces to use them as context.
