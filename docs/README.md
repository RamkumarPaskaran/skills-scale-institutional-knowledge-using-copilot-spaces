# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management suite. This documentation provides comprehensive guidance for running projects using the OctoAcme framework.

## OctoAcme Approach

OctoAcme is built on five core principles:
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle Overview

OctoAcme projects follow a structured five-phase lifecycle:

1. **Initiation**: Define problem statement, stakeholders, and high-level timeline
2. **Planning**: Break down scope, identify dependencies, and create backlog
3. **Execution**: Build, test, review, and iterate
4. **Release**: Deploy, verify, and announce
5. **Retrospective**: Capture learnings and continuous improvements

## OctoAcme Project Management Processes — Summary

OctoAcme manages projects through a structured five-phase lifecycle with defined deliverables and decision gates. During **Initiation**, the team validates business need, identifies stakeholders, and produces a lightweight Project One-pager that confirms success metrics and resource needs before moving forward. **Planning** converts that approval into an actionable backlog with prioritized items, clear acceptance criteria, and a Definition of Done. **Execution** follows an iterative delivery model with daily standups, weekly delivery syncs, and small pull requests (≤400 lines) that pass automated tests before review. The **Release** phase standardizes deployment through pre-release checklists, smoke testing, and rollback plans to minimize production risk. Finally, **Retrospectives** capture learnings after each sprint or milestone and convert insights into tracked action items for continuous improvement.

OctoAcme emphasizes **clear ownership** across three core roles: **Project Managers** coordinate delivery, manage schedules, risks, and stakeholder communication; **Product Managers** define outcomes, prioritize the backlog, and measure impact through data; and **Developers** implement features, write tests, and collaborate on design and acceptance criteria. QA/Testing roles validate quality and acceptance criteria, while stakeholders provide inputs and approvals. This distributed responsibility model—paired with named Project Managers and Product Leads for each project—reduces ambiguity and ensures accountability throughout execution.

Communication cadence is frequent and structured: daily standups focus on progress and blockers, weekly PM–PdM syncs align delivery and strategy, and twice-weekly team standups keep execution on track. A **Risk Register** captures risks by ID, impact, likelihood, owner, and mitigation plan, reviewed at weekly syncs to prevent surprises. Escalation follows a clear three-level path: Level 1 is team-level triage in standups, Level 2 escalates to the PM and Product Lead, and Level 3 reaches sponsor level for business-impacting issues. Quality is embedded throughout execution with unit tests, integration tests, end-to-end smoke tests, and security scanning in CI. Beyond single releases, OctoAcme uses retrospectives to reflect on improvements and drive continuous learning.

## Core Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risks, communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validates quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

## Documentation Index

### Getting Started
- **[Project Management Overview](octoacme-project-management-overview.md)** — Introduction to OctoAcme, roles, key artifacts, and project lifecycle
- **[Roles and Personas](octoacme-roles-and-personas.md)** — Detailed role definitions and responsibilities

### Project Phases
- **[Project Initiation](octoacme-project-initiation.md)** — Validate business need, align stakeholders, authorize work
- **[Project Planning](octoacme-project-planning.md)** — Create actionable plans, backlog, and release timeline
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day delivery, progress tracking, team rhythm
- **[Release & Deployment](octoacme-release-and-deployment.md)** — Standardized release procedures and rollback plans

### Critical Processes
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, track, and communicate risks and dependencies
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and drive improvements

## Issue Templates

Use the **[Add Content to Project Management Process Docs](https://github.com/RamkumarPaskaran/skills-scale-institutional-knowledge-using-copilot-spaces/issues/new?template=add-update-content-to-process-docs.yml)** template to propose updates or additions to this documentation suite.

## How to Use These Docs

- **New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md) and [Roles and Personas](octoacme-roles-and-personas.md).
- **Starting a new project?** Follow the [Project Initiation](octoacme-project-initiation.md) guide, then move to [Project Planning](octoacme-project-planning.md).
- **Running execution?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risk Management & Communication](octoacme-risks-and-communication.md).
- **Preparing for release?** Review [Release & Deployment](octoacme-release-and-deployment.md).
- **Looking for improvements?** Use [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) to capture and track learnings.
