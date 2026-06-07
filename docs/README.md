# OctoAcme — Project Management Processes

This repository stores living program/process documents used to run OctoAcme projects. The docs below summarize core processes and link to more detailed guidance in this repo's docs/ directory.

## Overview (brief)
OctoAcme runs cross-functional projects with a focus on customer value, iterative delivery, and clear ownership. Work is organized through lightweight artifacts (Project One-pagers, roadmaps, backlog items), a predictable team rhythm (standups, weekly syncs, demos), and a visible tracking board (Backlog → Ready → In Progress → In Review → QA → Done).

## Key Phases & How We Work
- Initiation
  - Produce a Project One-pager with problem, goals, success metrics, stakeholders, and a high-level timeline.
  - Use decision gates to approve moving into planning.
- Planning
  - Kickoff with stakeholders and delivery team.
  - Create prioritized backlog with acceptance criteria and estimates.
  - Define Definition of Done and release milestones.
- Execution & Tracking
  - Daily standups for blockers and progress; weekly delivery syncs for risks and dependencies.
  - Small PRs, CI checks, and at least one approval before merge.
  - Track velocity, burndown, and key success metrics on dashboards.
- Release & Deployment
  - Pre-release checks (CI/security/acceptance), smoke tests, and rollback plans.
  - Automated deploy pipelines preferred; post-deploy verification and stakeholder announcement.
- Retrospective & Continuous Improvement
  - Run retros after sprints, releases, or incidents; capture 2–3 action items and track them in the backlog.
- Risk Management & Communication
  - Maintain a simple Risk Register (ID, impact, likelihood, owner, mitigation).
  - Use weekly status templates for stakeholder updates and defined escalation paths.

## Roles & Responsibilities (short)
- Product Manager: defines outcomes, success metrics, and prioritization.
- Project Manager: coordinates schedules, risks, and cross-team communication.
- Developers: implement features, write tests, and participate in reviews.
- QA: validate acceptance criteria and run manual/automated tests.
- Stakeholders: provide inputs, approvals, and alignment.

## Where to find full process docs
See docs/ for the complete process documents:
- docs/octoacme-project-initiation.md
- docs/octoacme-project-planning.md
- docs/octoacme-execution-and-tracking.md
- docs/octoacme-release-and-deployment.md
- docs/octoacme-retrospective-and-continuous-improvement.md
- docs/octoacme-risks-and-communication.md
- docs/octoacme-roles-and-personas.md

## How to propose updates
Use the repository issue template "Add Content to Project Management Process Docs" in .github/ISSUE_TEMPLATE/ to request additions or edits.
