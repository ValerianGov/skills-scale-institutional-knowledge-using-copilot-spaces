# OctoAcme Project Management Documentation

## Overview

OctoAcme uses a customer-first, iterative project management approach that emphasizes clear ownership, data-informed decisions, and psychological safety. These processes apply to all cross-functional projects delivering product features, services, or integrations.

## Core Principles

- **Customer-first:** Prioritize customer value and usability
- **Iterative delivery:** Deliver small, testable increments
- **Clear ownership:** Each project has a named PM and Product Lead
- **Data-informed:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback and learning

## Project Lifecycle

OctoAcme follows a structured five-phase project lifecycle:

1. **Initiation** – Validate business need, align stakeholders, create lightweight plan
2. **Planning** – Break work into shippable increments, identify dependencies and risks
3. **Execution** – Build, test, review, and iterate with regular team rhythm
4. **Release** – Deploy features to production with standardized processes
5. **Close & Retrospective** – Capture learnings and drive continuous improvement

## Process Overview

### Project Lifecycle and Core Workflow

OctoAcme's five-phase lifecycle ensures structured delivery while maintaining flexibility. During **initiation**, teams validate business needs and create a lightweight Project One-pager capturing the problem statement, success metrics, stakeholders, and resource requirements. Once stakeholders align and the go/no-go decision is made, the project moves into **planning**, where work is broken into shippable increments with clear acceptance criteria, dependencies are identified, and a prioritized backlog is created. Throughout **execution**, teams follow a sprint-based rhythm with daily standups (15 min), weekly delivery syncs, and end-of-sprint demos. The process emphasizes iterative delivery of small, testable increments tracked on a project board with columns for Backlog, Ready, In Progress, In Review, QA, and Done. Pull requests are kept to ≤400 lines, require at least one approval, and must pass automated CI tests before merging.

### Roles, Responsibilities, and Communication Cadence

OctoAcme operates with clearly defined roles: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define outcomes, prioritize the backlog, and measure success; **Developers** implement features and collaborate on design and testability; and **QA/Testing** validates acceptance criteria. This structure ensures clear ownership and psychological safety. Communication follows a regular cadence that includes twice-weekly standups for delivery teams, weekly syncs between PM and Product Lead, monthly stakeholder updates, and ad-hoc escalations as needed. Risk escalation follows a three-level hierarchy: Level 1 team-level triage in standups, Level 2 escalation to the Product Lead and dependent teams, and Level 3 sponsor-level escalation for business-impacting issues.

### Quality Assurance and Risk Management

Quality is embedded throughout OctoAcme's execution model through unit tests, integration tests, and end-to-end smoke tests for critical flows. Security scanning is configured in the CI pipeline, and manual QA is conducted when needed for feature acceptance. Risk management is continuous—teams identify risks during planning and throughout execution, maintaining a Risk Register that tracks impact, likelihood, ownership, and mitigation plans. Risks are reviewed weekly during syncs and updated in real time. For releases, OctoAcme requires all acceptance criteria to be met, CI and security scans to pass, release notes to be drafted, and a rollback plan to be documented before deployment. Release notes follow a standard template and rollback/incident playbooks ensure rapid response if issues arise.

### Continuous Improvement and Knowledge Management

OctoAcme embeds continuous improvement through retrospectives held after each sprint, release, or milestone, structured around what went well, what could improve, and actionable items with clear owners and due dates. Action items are tracked in the project backlog and reviewed in weekly PM syncs to ensure follow-through. The organization prioritizes capturing learnings and converting them into actionable improvements, creating a culture of psychological safety where feedback is encouraged. All process documentation is maintained in the repository's `docs/` folder and can be attached to Copilot Spaces, enabling new teammates to quickly understand workflows, decision gates, and quality standards while centralizing tacit knowledge and reducing single-person dependency risk.

## Documentation

### Start Here

- [Project Management Overview](octoacme-project-management-overview.md) – Core roles, principles, and artifacts
- [Roles & Personas](octoacme-roles-and-personas.md) – Definitions of developers, PMs, and project leads

### By Project Phase

- [Project Initiation](octoacme-project-initiation.md) – Steps to validate and authorize work
- [Project Planning](octoacme-project-planning.md) – Creating actionable plans and backlogs
- [Execution & Tracking](octoacme-execution-and-tracking.md) – Day-to-day delivery and progress tracking
- [Risk Management & Communication](octoacme-risks-and-communication.md) – Managing risks and keeping stakeholders informed
- [Release & Deployment](octoacme-release-and-deployment.md) – Standardized release processes
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) – Capturing learnings and improvements

## Quick Reference: Key Templates & Checklists

### Project One-pager (Initiation)

- Project name
- Problem statement
- Objective / Goal (SMART)
- Success metrics
- Primary stakeholders
- Suggested timeline / milestones
- Quick risks & dependencies
- Proposed team / roles

### Backlog Item (Planning)

- Title
- Description
- Acceptance criteria
- Priority
- Estimate
- Owner
- Related docs/links

### Risk Register (Risk Management)

- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

### Weekly Status Update (Communication)

- Progress this week
- Next steps
- Risks & blockers
- Ask / decisions needed

### Action Item (Retrospectives)

- Title
- Description
- Owner
- Due date
- Success criteria

## How to Use These Docs

1. **For new team members:** Start with the [Project Management Overview](octoacme-project-management-overview.md) and [Roles & Personas](octoacme-roles-and-personas.md) to understand OctoAcme's approach.

2. **For project setup:** Follow the [Project Initiation](octoacme-project-initiation.md) guide to validate and authorize your work.

3. **For ongoing execution:** Reference [Execution & Tracking](octoacme-execution-and-tracking.md), [Risk Management & Communication](octoacme-risks-and-communication.md), and [Project Planning](octoacme-project-planning.md) as needed.

4. **For releasing:** Use the [Release & Deployment](octoacme-release-and-deployment.md) checklist before going to production.

5. **For learning and improvement:** Schedule a retrospective using the [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) guide.

6. **For Copilot Spaces:** Attach these docs to your Copilot Space to ground its knowledge in OctoAcme's processes and enable context-specific project guidance.

## Keep Docs Updated

- Update your project's One-pager and Risk Register weekly
- Record action items from retrospectives in GitHub issues
- Share process improvements across the team by updating these docs
- Add new templates or examples as your team evolves
