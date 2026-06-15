# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management process documentation. This folder contains comprehensive guides and templates designed to help teams understand and execute OctoAcme's proven project delivery methodology.

## Overview of OctoAcme Project Management Processes

**Lifecycle & Key Workflows**

OctoAcme operates on a customer-first, iteratively-driven project lifecycle spanning five phases: initiation, planning, execution, release, and closing. During initiation, teams validate business need, align stakeholders, and create a lightweight one-pager defining problem statements, SMART goals, and success metrics before moving to the planning phase. The planning phase breaks initiatives into shippable increments with prioritized backlogs, acceptance criteria, and release timelines. Execution is managed through daily standups, twice-weekly delivery syncs, and a structured workflow using project boards (Backlog → Ready → In Progress → In Review → QA → Done). Pull requests are kept small (≤400 lines), paired with CI automation for tests and security scanning, and require at least one approval before merging. This iterative approach emphasizes small, testable increments and regular demos to maintain stakeholder alignment.

**Roles, Personas & Communication**

OctoAcme defines three core delivery personas. Project Managers coordinate schedules, dependencies, and communications while maintaining project documentation and facilitating decision gates. Product Managers define outcomes, prioritize backlogs, and measure success through data-driven metrics and user research. Developers implement features, participate in design reviews, and help identify technical risks. Communication is structured through a weekly sync between PM and Product Manager, twice-weekly team standups, monthly stakeholder updates, and ad-hoc escalation paths (Team → PM → Product Lead → Sponsor). Each project has named owners and champions, ensuring clear accountability and psychological safety for feedback and learning.

**Quality Assurance & Risk Management**

Quality is embedded throughout execution via unit tests, integration tests, end-to-end smoke testing, security scanning in CI, and manual QA for acceptance when needed. Risks are actively managed through a Risk Register maintained during planning and reviewed weekly; risks are identified, assessed for impact and likelihood, assigned owners, and tracked through mitigation and resolution. Blocker escalation is tiered—team-level triage in standups, PM escalation to stakeholders for business impacts, and sponsor-level involvement for critical issues. Release processes include pre-deployment verification (acceptance criteria met, passing CI, release notes drafted, rollback plans documented), staged deployments to staging with smoke tests before production, and post-deploy verification. Incidents trigger defined response playbooks with rollback capability and blameless retrospectives.

**Continuous Improvement & Learning**

OctoAcme embeds learning through retrospectives held after each sprint, release, or milestone. Retrospectives are timeboxed (45–75 minutes), structured around what went well and what could improve, and result in 2–3 prioritized action items with named owners and due dates. Action items feed back into the project backlog, are reviewed weekly in PM syncs, and their impact is measured to drive incremental improvement. This cycle of structured reflection, accountability, and continuous adjustment ensures OctoAcme projects remain aligned with customer value, team capacity, and business outcomes while fostering a culture of transparency, psychological safety, and shared learning.

## Documentation Structure

This folder contains the following detailed process guides:

### Core Processes

- **[octoacme-project-management-overview.md](./octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's principles, core roles, key artifacts, and communication cadence.

- **[octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md)** — Detailed definitions of Developers, Product Managers, and Project Managers with their responsibilities, goals, and typical communication patterns.

### Project Lifecycle Phases

- **[octoacme-project-initiation.md](./octoacme-project-initiation.md)** — Guidance on validating business need, aligning stakeholders, and creating project one-pagers before entering planning.

- **[octoacme-project-planning.md](./octoacme-project-planning.md)** — Process for breaking work into shippable increments, defining acceptance criteria, estimating scope, and creating release plans.

- **[octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md)** — Day-to-day guidance on team rhythm, PR workflows, quality & testing practices, and blocker escalation.

- **[octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md)** — Standardized release procedures, deployment checklists, and rollback/incident playbooks.

- **[octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md)** — How to run effective retrospectives and convert learnings into actionable improvements.

### Cross-Cutting Concerns

- **[octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md)** — Risk register management, stakeholder communication templates, and escalation paths.

## How to Use These Docs

1. **For New Projects:** Start with [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) and [octoacme-project-initiation.md](./octoacme-project-initiation.md) to understand the approach and kickoff process.

2. **For Copilot Spaces:** Copy process-specific docs into `.copilot/` directory to ground Copilot in OctoAcme's methodology for your project context.

3. **For Team Onboarding:** Share [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) to help new team members understand their role and responsibilities.

4. **For Project Execution:** Reference [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md) during sprint planning, standups, and release cycles.

5. **For Continuous Improvement:** Use [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md) to structure learnings and drive iterative improvements.

## Key Principles

- **Customer-first:** Prioritize customer value and usability.
- **Iterative delivery:** Deliver small, testable increments.
- **Clear ownership:** Each project has named Project Manager (PM) and Product Lead.
- **Data-informed decisions:** Measure impact and iterate based on evidence.
- **Psychological safety:** Encourage feedback and learning.

## Getting Started

If you're new to OctoAcme project management, we recommend:

1. Reading this README for context
2. Reviewing the [Project Management Overview](./octoacme-project-management-overview.md)
3. Exploring the [Roles & Personas](./octoacme-roles-and-personas.md) to understand your team
4. Following the lifecycle guides as your project progresses through initiation, planning, execution, release, and retrospective phases

For questions or suggestions about these processes, please open an issue or contact the project leadership team.
