# OctoAcme Project Management Docs README

This README is the central index for the OctoAcme program management documentation. It provides links to each process document and a concise overview of how OctoAcme runs projects from initiation through continuous improvement.

Summary:

OctoAcme runs projects with a lightweight, repeatable lifecycle that moves work from initiation through planning, execution, release, and continuous improvement. Projects begin with a one-pager that captures the problem, objective, success metrics, stakeholders, and a high-level timeline; the Initiation guide and checklists ensure a clear go/no‑go decision before planning. During planning the team holds a kickoff, builds a prioritized backlog with acceptance criteria, estimates work (T‑shirt sizing or story points), and records dependencies and risks in a Risk Register. Key artifacts — Project One‑pager, Definition of Done, release plan, and a Release Notes template — are maintained in docs/ so the project has a single source of truth.

Work is executed using a simple project board workflow (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined Pull Request process: keep PRs small (target <= 400 lines), include the linked issue and acceptance criteria, run CI and linters before requesting review, and require at least one approval per team policy. The planning and execution docs also prescribe sprint/iteration practices (timeboxed planning, respecting team capacity) and explicit backlog item templates so that work is consistently describable and reviewable. There’s also an Issue Template for proposing updates to process docs, which helps keep process material current and governed.

Roles and communication are explicit: Product Managers define outcomes and success metrics; Project Managers coordinate schedules, risks, and stakeholder communication; Developers implement features and tests; QA validates acceptance criteria; and stakeholders provide input and approvals. Regular cadence is emphasized — daily standups for team-level progress and blockers, weekly delivery syncs to show progress and escalate risks, PM/PdM weekly alignment, and monthly stakeholder updates — plus regular demos at milestones. Communication templates (weekly status, incident triage) and an escalation path (team → PM → Product Lead → Sponsor, with a separate security incident flow) standardize how information and risks move up and across the organization.

Quality and release practices prioritize test coverage, automation, and safe deployment. Developers are expected to add unit and integration tests and run end‑to‑end smoke tests for critical flows; CI includes security scanning and automated checks before merge. Releases follow a checklist (staging smoke tests, rollback plan, backups where applicable) and a clear rollback/incident playbook. Retrospectives are timeboxed and focus on 2–3 actionable improvements; resulting action items are tracked in the backlog so continuous improvement is measurable and tied to delivery.

Links to docs:

- [OctoAcme — Project Management Overview](./octoacme-project-management-overview.md)
- [OctoAcme — Project Initiation Guide](./octoacme-project-initiation.md)
- [OctoAcme — Project Planning](./octoacme-project-planning.md)
- [OctoAcme — Execution & Tracking](./octoacme-execution-and-tracking.md)
- [OctoAcme — Risk Management & Communication](./octoacme-risks-and-communication.md)
- [OctoAcme — Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [OctoAcme — Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [OctoAcme Personas](./octoacme-roles-and-personas.md)

Purpose:

These documents are intended to standardize project execution, provide a shared source of truth for the team, and make it easier for new contributors to find and use OctoAcme's process definitions.
