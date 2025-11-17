# OctoAcme Project Management Docs

This folder contains OctoAcme's core project management processes and serves as the single entry point for contributors who need to understand how we initiate, plan, deliver, and improve cross-functional projects.

OctoAcme runs lightweight, outcome-driven projects. Work begins with a Project One-pager to capture the problem, measurable goals, and primary stakeholders, then moves into planning where scope is broken into prioritized backlog items with clear acceptance criteria and estimates. Execution uses a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done) and small, reviewable pull requests as the primary delivery unit. Releases are governed by a pre-release checklist (CI/security scans, release notes, rollback plan, smoke tests) and an incident playbook for rollback and remediation when needed.

Roles and responsibilities are explicit to avoid confusion and accelerate decisions: Product Managers (PdM) define outcomes and prioritize the backlog; Project Managers (PM) coordinate timelines, risks, and communications; Developers implement and test; QA validates acceptance; Stakeholders provide approvals. Escalation paths (team → PM → Product Lead → Sponsor) and a security incident runbook are used for high-impact issues.

Communication and quality assurance are structured and repeatable: daily standups and a weekly delivery sync keep teams aligned, PM–PdM weekly alignment maintains prioritization, and monthly stakeholder updates keep sponsors informed. QA combines automated testing (unit, integration, security scans, and smoke tests) with manual validation when needed. Retrospectives capture actionable improvements; action items are added to the backlog with owners and timelines.

Docs in this folder
- Project Management Overview — docs/octoacme-project-management-overview.md
- Project Initiation Guide — docs/octoacme-project-initiation.md
- Project Planning — docs/octoacme-project-planning.md
- Execution & Tracking — docs/octoacme-execution-and-tracking.md
- Risk Management & Communication — docs/octoacme-risks-and-communication.md
- Release & Deployment Guide — docs/octoacme-release-and-deployment.md
- Retrospective & Continuous Improvement — docs/octoacme-retrospective-and-continuous-improvement.md
- Roles & Personas — docs/octoacme-roles-and-personas.md

Acceptance criteria
- [ ] Content aligns with the process docs in this folder
- [ ] README gives new contributors a clear entry point and links to detailed docs
- [ ] README is concise and covers workflows, roles, communication, and QA practices