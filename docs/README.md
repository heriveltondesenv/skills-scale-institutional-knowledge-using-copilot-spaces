# OctoAcme Project Management Processes

This repository centralizes OctoAcme's project management processes and templates to help teams run projects consistently and reduce single-person dependencies. The docs in this folder outline the lifecycle from initiation through planning, execution, release, and continuous improvement.

## Summary of Key Workflows and Practices

OctoAcme follows a lightweight, lifecycle-driven approach. Projects move through Initiation (one-pager, stakeholder alignment, initial risk list), Planning (kickoff, prioritized backlog, estimates, Definition of Done, and release planning), Execution (iterative delivery using a project board and a disciplined Pull Request workflow), Release (pre-release checks, smoke tests, and rollback plans), and Close & Retrospective (capture learnings and track action items).

Work is managed on a project board with columns Backlog → Ready → In Progress → In Review → QA → Done. Pull Requests are kept small when possible, must link to an issue and include acceptance criteria, and should pass automated CI checks (tests, linting, and security scans) before requesting reviews. At least one approval is required before merges per team policy.

## Roles & Personas

- Product Manager (PdM): defines outcomes, success metrics, and prioritization.
- Project Manager (PM): coordinates delivery, schedules, risks, and stakeholder communication.
- Developers: implement features, write tests, and participate in reviews.
- QA/Testing: validate acceptance criteria and perform manual or exploratory testing as needed.
- Stakeholders: provide inputs and approvals.

## Communication & Cadence

- Daily standups (15 minutes) for progress and blockers.
- Weekly delivery syncs to review progress and risks.
- Weekly PM+PdM sync and monthly stakeholder updates.
- Use a single source of truth (project README or release doc) and standard templates for status and incident communication.

## Quality Assurance

Quality is built in via unit and integration tests, CI-enforced checks, security scans, and end-to-end smoke tests for critical flows. Manual QA is used when feature acceptance requires human validation. Releases require passing CI, release notes, rollback plans, and post-deploy verifications.

## Where to Find More

See the other docs in this folder for initiation, planning, execution, release, risk management, retrospectives, and persona details.
