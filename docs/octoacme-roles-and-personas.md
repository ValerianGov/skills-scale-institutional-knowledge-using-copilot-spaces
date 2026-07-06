# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Engineering Manager

### Role Summary
Engineering Managers (EMs) are responsible for the health and effectiveness of engineering teams. They combine people leadership, operational oversight, and prioritization to ensure teams can deliver sustainably.

### Responsibilities
- Staff and grow the team (hiring, coaching, career development)
- Balance capacity, priorities, and technical investments
- Remove team-level impediments and unblock delivery
- Advocate for engineering needs in planning and resourcing discussions

### Goals
- Maintain a high-performing, engaged engineering team
- Align team capacity to product priorities
- Reduce delivery risk through coaching and process improvements

### Interactions with existing roles
- Works with PM for capacity planning and milestone commitments
- Partners with Tech Leads and Developers on technical direction and execution
- Coordinates with HR for performance and career development conversations
- Escalates cross-team or resourcing issues to Product or Program leadership when needed

---

## Tech Lead

### Role Summary
Tech Leads provide technical direction and design leadership for a team or feature area, ensuring solutions meet architectural and quality standards.

### Responsibilities
- Drive technical design and architecture decisions
- Establish and uphold code quality standards and best practices
- Mentor engineers and run design/code reviews
- Identify technical debt and plan remediation alongside feature work

### Goals
- Deliver robust, maintainable solutions that scale
- Improve team engineering practices and code quality
- Keep technical debt visible and managed

### Interactions with existing roles
- Works closely with Developers to implement designs and resolve technical challenges
- Collaborates with QA to ensure testability and appropriate test coverage
- Partners with PM/PdM to evaluate trade-offs between technical debt and feature delivery
- Coordinates with SRE for operability concerns and production readiness

---

## UX Researcher

### Role Summary
UX Researchers gather and synthesize user insights to inform product decisions and validate designs, reducing uncertainty and guiding prioritization.

### Responsibilities
- Plan and conduct user interviews, usability tests, and other research studies
- Synthesize findings into actionable recommendations and patterns
- Validate prototypes and measure usability improvements

### Goals
- Ensure product decisions are grounded in observed user behavior
- Reduce rework by validating assumptions early
- Improve user satisfaction and usability metrics

### Interactions with existing roles
- Partners with Product Managers to define research questions and success metrics
- Works with Designers and Developers to iterate on solutions based on research findings
- Shares research outputs with stakeholders to inform prioritization and acceptance criteria

---

## Release Manager

### Role Summary
Release Managers own release planning and execution activities, ensuring deployments are coordinated, safe, and communicated appropriately.

### Responsibilities
- Maintain the release calendar and coordinate release windows
- Validate release readiness (PRs merged, tests passing, release notes drafted)
- Coordinate deployments, rollback plans, and post-release verification
- Communicate release status to stakeholders and support teams

### Goals
- Reduce deployment risk and ensure predictable releases
- Ensure clear communication around release scope and timing
- Maintain documented runbooks and rollback plans

### Interactions with existing roles
- Coordinates with PM, SRE, QA, and Developers to validate readiness and schedule releases
- Triggers stakeholder communications and support handoffs before and after releases
- Works with Project Managers to align release timing with business milestones

---

## Site Reliability Engineer (SRE)

### Role Summary
SREs focus on production reliability, observability, and incident response, ensuring services meet uptime and performance targets.

### Responsibilities
- Design and maintain monitoring, alerts, and runbooks
- Participate in incident response and post-incident reviews
- Work on capacity planning, performance tuning, and reliability improvements
- Implement automation to reduce operational toil

### Goals
- Improve system reliability and mean time to recovery (MTTR)
- Increase observability and reduce alert noise
- Ensure scalable, performant systems

### Interactions with existing roles
- Collaborates with Developers and Tech Leads on operability and observability requirements
- Works with Release Manager to ensure safe deployment practices
- Partners with Support Lead during incidents to provide technical context and remediation steps

---

## Support Lead / Customer Success Liaison

### Role Summary
The Support Lead or Customer Success Liaison is responsible for triaging customer issues, communicating patterns back to the product and engineering teams, and helping prioritize fixes and improvements.

### Responsibilities
- Triage incoming customer issues and categorize by severity and impact
- Surface product-impacting trends and escalate critical issues
- Maintain communication with customers and internal stakeholders during incident handling

### Goals
- Provide timely, empathetic customer communication
- Reduce time-to-resolution for customer-facing issues
- Feed user context into product prioritization

### Interactions with existing roles
- Raises bugs and reproducible issues to Developers and PMs
- Works with SRE during major incidents to manage customer communications and escalations
- Provides PdM with user context and prioritization input for bug fixes and UX improvements

---

## Data Analyst

### Role Summary
Data Analysts provide measurement, analysis, and insights to help Product and PM make data-informed decisions and validate outcomes.

### Responsibilities
- Define and track success metrics and dashboards
- Conduct analysis to inform prioritization and measure impact of releases
- Validate that shipped features achieve intended outcomes

### Goals
- Surface actionable insights that shape product decisions
- Reduce uncertainty through rigorous measurement
- Help quantify the impact of improvements and experiments

### Interactions with existing roles
- Supplies PdM and PM with metrics and analysis for prioritization and reporting
- Works with Developers and SRE to instrument metrics and ensure data quality
- Shares findings with stakeholders to influence roadmap and success criteria
