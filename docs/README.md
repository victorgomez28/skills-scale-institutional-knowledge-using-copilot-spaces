# OctoAcme Project Management — README

Purpose
This README is the central entry point for OctoAcme's project management processes. It summarizes the core workflows, roles, communication cadence, and quality practices, and links to the detailed process documents located in this folder.

Overview
OctoAcme follows a lightweight, iterative lifecycle: Initiation → Planning → Execution → Release → Retrospective. Work starts with a Project One-pager to capture the problem, measurable goals, stakeholders, and a high-level timeline. Planning breaks approved initiatives into a prioritized backlog with acceptance criteria and estimates, and produces a release plan and Definition of Done so the team can deliver small, testable increments.

Day-to-day delivery is tracked on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and enforced via a pull request workflow that emphasizes small PRs, linked issues with acceptance criteria, automated CI/linting, and review approvals. Team rhythm includes daily standups, weekly delivery syncs, sprint demos, and regular PM+PdM syncs. Risk and stakeholder communication use a simple Risk Register, standardized weekly status templates, and a tiered escalation path for blockers and incidents.

Quality is embedded across the lifecycle: unit and integration tests, end-to-end smoke tests for critical flows, CI security scanning, and manual QA as needed. Releases require passing CI and security checks, drafted release notes, and a rollback plan. Continuous improvement is enforced through timeboxed retrospectives, prioritized action items assigned to owners, and follow-up in weekly PM syncs.

Process documents (in this folder)
- Project Management Overview — docs/octoacme-project-management-overview.md
- Project Initiation Guide — docs/octoacme-project-initiation.md
- Project Planning — docs/octoacme-project-planning.md
- Execution & Tracking — docs/octoacme-execution-and-tracking.md
- Risks & Communication — docs/octoacme-risks-and-communication.md
- Release & Deployment Guide — docs/octoacme-release-and-deployment.md
- Retrospective & Continuous Improvement — docs/octoacme-retrospective-and-continuous-improvement.md
- Roles & Personas — docs/octoacme-roles-and-personas.md

How to use
Keep this README concise and use the linked documents for process-specific guidance. Consider adding a cross-link from the repository root README for greater discoverability.
