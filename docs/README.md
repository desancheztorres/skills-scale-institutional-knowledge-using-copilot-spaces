# OctoAcme Project Management Documentation

## Purpose

Welcome to the central documentation hub for OctoAcme's project management practices. This README serves as the primary entry point and table of contents for all project management process documentation. Whether you're a new team member looking to understand how OctoAcme runs projects, or an experienced contributor seeking specific process guidance, you'll find organized links and summaries here to help you navigate our approach to delivering high-quality software.

## Documentation Index

The following documents describe OctoAcme's end-to-end project management lifecycle:

- [Project Management Overview](octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, core principles, roles, and artifacts
- [Project Initiation](octoacme-project-initiation.md) — How to validate and authorize new work, create a project one-pager, and secure stakeholder alignment
- [Project Planning](octoacme-project-planning.md) — Breaking work into actionable backlogs, estimating scope, and defining release plans
- [Execution and Tracking](octoacme-execution-and-tracking.md) — Day-to-day workflows, PR conventions, quality practices, and progress reporting
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Identifying and mitigating risks, maintaining stakeholder communication, and escalation paths
- [Release and Deployment](octoacme-release-and-deployment.md) — Release types, pre-release checklists, deployment procedures, and rollback strategies
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capturing learnings, running retrospectives, and tracking improvement actions
- [Roles and Personas](octoacme-roles-and-personas.md) — Definitions and responsibilities for Developers, Product Managers, and Project Managers

## Project Management Process Summary

OctoAcme's project management approach is designed to deliver customer value iteratively while maintaining clear ownership, quality standards, and psychological safety. The framework emphasizes data-informed decisions, small testable increments, and cross-functional collaboration across all stages of the project lifecycle.

At the core of every project are three key roles working in partnership: the Project Manager (PM) coordinates delivery, schedules, and risk management; the Product Manager (PdM) defines outcomes and prioritizes the backlog; and Developers implement features while maintaining quality and testability. These roles collaborate through a structured lifecycle that begins with project initiation—creating a lightweight one-pager with problem statement, success metrics, and stakeholder alignment—and progresses through detailed planning where work is broken into shippable increments with clear acceptance criteria and Definition of Done.

During execution, teams follow a consistent rhythm of daily standups, weekly delivery syncs, and end-of-sprint demos. Quality is ensured through comprehensive testing practices including unit tests, integration tests, and security scanning in CI, alongside a pull request workflow that requires code reviews and automated checks before merging. Progress is tracked transparently using project boards (such as GitHub Projects) with clearly defined workflow states, while risks are actively managed through a maintained risk register that's reviewed during weekly syncs. Communication follows a regular cadence with twice-weekly team standups, weekly PM-PdM alignment meetings, and monthly stakeholder updates.

The process concludes with structured release procedures—including staged deployments to environments with smoke tests and rollback plans—followed by retrospectives that capture learnings and convert them into actionable improvements. Throughout the entire lifecycle, OctoAcme maintains a customer-first mindset, prioritizing usability and measurable impact. Key artifacts including project charters, roadmaps, sprint backlogs, and retrospective action items are kept in project repositories and can be added to `.copilot/` directories to provide context for Copilot Spaces, ensuring that institutional knowledge is accessible and actionable for all team members.

## How to Use These Docs

These documents are living resources that evolve with our practices. Here's how to work with them:

**For New Team Members:** Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand our principles and approach, then explore the [Roles and Personas](octoacme-roles-and-personas.md) document to understand your responsibilities and how you fit into the team structure.

**For Active Projects:** Reference the relevant lifecycle documents ([Initiation](octoacme-project-initiation.md), [Planning](octoacme-project-planning.md), [Execution](octoacme-execution-and-tracking.md), [Release](octoacme-release-and-deployment.md)) as you progress through each phase. Use the checklists provided in each document to ensure you're following established practices.

**For Process Updates:** Have a suggestion for improving our documentation? Use the [Add/Update Content to Process Docs](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to propose changes or additions. This ensures all updates are reviewed and aligned with our overall approach.

**Context for Copilot Spaces:** These docs can be added to your project's `.copilot/` directory to provide context-aware assistance. This helps Copilot understand OctoAcme's specific workflows, terminology, and best practices.

---

*This README was created in response to [Issue #2](https://github.com/desancheztorres/skills-scale-institutional-knowledge-using-copilot-spaces/issues/2) to provide a central entry point for all OctoAcme project management documentation.*
