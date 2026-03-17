# OctoAcme Project Management Docs

Welcome to the central entry point for OctoAcme's project management process documentation. This README provides a high-level overview of how OctoAcme runs projects and links to all detailed process guides in this folder.

## Overview

OctoAcme operates on a structured project lifecycle that emphasizes customer-first delivery, iterative development, and clear ownership. The process flows through five key phases: **Initiation** (validating business need and stakeholder alignment via a Project One-pager), **Planning** (breaking work into shippable increments with prioritized backlogs and defined acceptance criteria), **Execution** (day-to-day delivery with daily standups and weekly syncs), **Release** (standardized deployment with pre-release checklists and rollback plans), and **Close & Retrospective** (capturing learnings and driving continuous improvements). This lifecycle is supported by three core roles with distinct responsibilities: **Project Managers** who coordinate schedules, risks, and communications; **Product Managers (PdM)** who define outcomes, prioritize work, and measure success; and **Developers** who implement features, write tests, and collaborate on design. Each project maintains a central Project Charter and suite of artifacts—including a roadmap, sprint backlog, risk register, and retrospective notes—that serve as the single source of truth for all stakeholders.

Communication and risk management are embedded throughout OctoAcme's approach. Teams maintain a regular cadence including daily standups, weekly PM and PdM syncs, twice-weekly delivery standups, and monthly stakeholder updates. Risk identification and mitigation happen continuously—from planning through execution—with risks captured in a register tracking impact, likelihood, owner, and mitigation status. Escalation follows a clear path from team-level triage through the PM to the Product Lead and ultimately to sponsors for business-impacting issues. Weekly status reports ensure consistent, transparent communication of progress, next steps, blockers, and decisions needed across all stakeholder groups.

Quality and execution rigor are enforced through multiple mechanisms. OctoAcme mandates small pull requests (≤ 400 lines), automated CI testing and linting, security scanning, and at least one approval before merge. The team uses a structured project board with columns (Backlog, Ready, In Progress, In Review, QA, Done) to visualize workflow and dependencies. Every backlog item includes clear acceptance criteria, and a Definition of Done is established during planning. Pre-release requirements include passing CI/security scans, drafted release notes, smoke tests, and documented rollback plans. This multi-layered approach—combining lightweight documentation, regular synchronization, clear escalation paths, and automated quality gates—enables OctoAcme to deliver reliably while maintaining flexibility and team psychological safety.

## Docs Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level introduction to OctoAcme's project management approach, principles, roles, and lifecycle |
| [Project Initiation Guide](octoacme-project-initiation.md) | Steps to validate and authorize work, align stakeholders, and create a lightweight project plan |
| [Project Planning](octoacme-project-planning.md) | How to turn an approved initiative into an actionable plan and backlog for delivery |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Guidance for managing day-to-day execution and tracking progress toward project milestones |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | How to identify, track, and communicate risks and status updates throughout the project lifecycle |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Standards and checklists for preparing and executing a safe, consistent product release |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | How to run effective retrospectives and turn learnings into lasting improvements |
| [Roles and Personas](octoacme-roles-and-personas.md) | Detailed responsibilities and expectations for every role involved in OctoAcme projects |
