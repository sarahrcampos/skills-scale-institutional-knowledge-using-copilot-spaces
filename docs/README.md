# OctoAcme Project Management Docs README

Welcome to OctoAcme's centralized project management process documentation. This README is intended as the single entry point for teammates to understand how we run projects, find the core process artifacts, and follow established workflows for consistent delivery.

OctoAcme follows an iterative, outcome-driven lifecycle: Initiation → Planning → Execution → Release → Retrospective. Initiation uses a lightweight Project One-pager to capture the problem, goals, success metrics, stakeholders, and a high-level timeline; a decision gate determines whether work moves into planning. Planning focuses on a kickoff, a prioritized backlog with acceptance criteria, estimates, a Definition of Done, and a release plan that captures risks and cross-team dependencies.

Day-to-day execution is managed via a project board (Backlog → Ready → In Progress → In Review → QA → Done) and a pull-request-driven workflow that emphasizes small PRs, linked issues and acceptance criteria, CI gating, and required approvals. Releases are classified (patch, minor, major) and have explicit pre-release requirements (passing CI and security scans, release notes, rollback plan), a deployment checklist, and post-deploy verifications. Blockers follow a three-level escalation path from team triage to sponsor-level intervention for business-impacting issues.

Roles and communication are defined to support clarity and alignment: Product Managers (PdM) own outcomes and prioritization, Project Managers (PM) coordinate delivery, Developers build and test, and QA validates acceptance criteria. Cadence includes daily standups, weekly delivery syncs, PM+PdM alignment, demos at the end of sprints/milestones, and monthly stakeholder updates. Communication templates and a single source of truth in project docs keep reporting consistent; escalation and incident playbooks define clear paths for urgent issues.

Quality assurance is embedded throughout: unit and integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA when needed. Acceptance criteria and the Definition of Done gate progress, dashboards track velocity and product signals, and retrospectives convert learnings into tracked action items.

## Docs directory
- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

## Acceptance Criteria
- [x] Content aligns with existing process docs in docs/
- [x] README improves discoverability and centralizes links
- [ ] Proposed content reviewed with stakeholders (if needed)

## Notes for reviewers
- This README is intentionally concise and links to the authoritative process documents already present in docs/. Please suggest wording changes or additional links that would improve discoverability.
