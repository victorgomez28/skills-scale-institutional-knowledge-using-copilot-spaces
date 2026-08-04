# OctoAcme Project Management — README

Purpose
This README is the central entry point for OctoAcme's program management processes. It provides a concise overview of how we run projects, the core roles involved, and direct links to the full process documents stored in the docs/ folder. Place this document in docs/ to make process guidance discoverable for new teammates and stakeholders.

Overview
OctoAcme follows a lightweight, iterative lifecycle that moves from Initiation through Planning, Execution, Release, and Retrospective. Projects begin with a Project One‑pager that captures the problem, objectives, success metrics, stakeholders, and a high‑level timeline. Planning turns approved initiatives into a prioritized backlog with acceptance criteria, estimates, and a release plan. Execution uses a project board with clear columns (Backlog → Ready → In Progress → In Review → QA → Done), small pull requests, CI checks, and a defined cadence of standups, weekly syncs, and demos. Releases require passing CI and security scans, smoke testing, release notes, and a rollback plan. Continuous improvement is enforced via timeboxed retrospectives with tracked action items.

Key workflows and roles
- Initiation: Create the one‑pager, align stakeholders, and decide whether to move to planning.
- Planning: Break work into shippable backlog items, estimate, define DoD, and capture dependencies/risks.
- Execution & Tracking: Day‑to‑day delivery with PR conventions, CI requirements, quality checks, and reporting.
- Risks & Communication: Maintain a Risk Register, use template-based status updates, and follow tiered escalation paths.
Primary roles include Project Manager (delivery coordination, risks, communications), Product Manager (outcomes, prioritization, success metrics), Developers (implementation, tests, docs), and QA (validation and acceptance).

Links to process documents (all in docs/)
- Project Management Overview — docs/octoacme-project-management-overview.md
- Project Initiation Guide — docs/octoacme-project-initiation.md
- Project Planning — docs/octoacme-project-planning.md
- Execution & Tracking — docs/octoacme-execution-and-tracking.md
- Risks & Communication — docs/octoacme-risks-and-communication.md
- Release & Deployment Guide — docs/octoacme-release-and-deployment.md
- Retrospective & Continuous Improvement — docs/octoacme-retrospective-and-continuous-improvement.md
- Roles & Personas — docs/octoacme-roles-and-personas.md

Notes
- Keep this README concise and treat it as a table-of-contents for the docs/ folder. Consider adding a cross-link from the project root README for greater discoverability.
- To propose a doc change, use the "Add Content to Project Management Process Docs" issue template located at .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml.
