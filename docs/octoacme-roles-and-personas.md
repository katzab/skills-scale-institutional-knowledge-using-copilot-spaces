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

As delivery scales, these cross-functional roles close common accountability gaps in design, operations, analytics, and customer feedback loops.

## UX Designers

### Role Summary
UX Designers translate product goals and user needs into clear, accessible experiences. They reduce rework by validating interaction and usability early.

### Responsibilities
- Lead user flows, wireframes, and interaction design
- Define accessibility and usability requirements with acceptance criteria
- Run lightweight usability research and synthesize findings
- Partner with Developers to ensure design intent is implemented

### Goals
- Improve task success, clarity, and accessibility for users
- Reduce late-stage design changes during implementation

### Typical Communication
- Design walkthroughs during planning and execution
- Annotated mockups and interaction specs in shared docs
- Usability findings shared with PdM, PM, and Developers

### Interactions with Existing Roles
- PM: aligns design milestones and review checkpoints with delivery timelines
- PdM: refines requirements, user outcomes, and priority trade-offs
- Developers: collaborates on feasibility, edge cases, and implementation fidelity

---

## DevOps / Platform Engineers

### Role Summary
DevOps / Platform Engineers own delivery infrastructure and operational reliability so teams can ship safely and repeatedly.

### Responsibilities
- Maintain CI/CD pipelines, deployment automation, and environments
- Define observability standards (logging, metrics, alerting)
- Partner on release, rollback, and incident response readiness
- Improve developer experience through platform tooling and guardrails

### Goals
- Increase deployment reliability and reduce mean time to recovery
- Reduce manual release steps and operational risk

### Typical Communication
- Release readiness and incident updates
- Runbook and environment change documentation
- Reliability and capacity planning checkpoints

### Interactions with Existing Roles
- PM: flags environment or dependency risks and plans mitigation timelines
- PdM: aligns rollout strategy with business impact and release constraints
- Developers: supports build/deploy workflows and production readiness standards

---

## Data Analysts / Analytics

### Role Summary
Data Analysts ensure initiatives are measurable, actionable, and tied to outcomes by defining and validating product and delivery metrics.

### Responsibilities
- Define event tracking requirements and KPI definitions
- Partner with Developers on instrumentation and data quality checks
- Produce insights on adoption, behavior, and outcome performance
- Support experiment design and post-release analysis

### Goals
- Improve decision quality through reliable measurement
- Shorten feedback loops from release to learning

### Typical Communication
- KPI definitions and dashboard reviews
- Weekly or milestone insight summaries
- Follow-up recommendations for PdM and PM

### Interactions with Existing Roles
- PM: provides metric status for milestone tracking and risk detection
- PdM: aligns success criteria, hypotheses, and prioritization decisions
- Developers: validates instrumentation and data correctness in delivered features

---

## Support Leads / Customer Support

### Role Summary
Support Leads represent customer-facing operational reality, ensuring incidents, feedback, and recurring pain points are triaged and fed back into planning.

### Responsibilities
- Own intake and prioritization of customer-impacting issues
- Coordinate incident communication and status updates
- Maintain support readiness artifacts (FAQs, known issues, response playbooks)
- Provide recurring trend analysis to PM, PdM, and Developers

### Goals
- Reduce customer impact duration and repeat issues
- Improve release readiness for customer-facing changes

### Typical Communication
- Incident and escalation updates in real time
- Weekly support trend digests
- Pre-release readiness alignment on known risks and messaging

### Interactions with Existing Roles
- PM: aligns escalation paths, ownership, and communication cadence
- PdM: shares customer pain trends to influence roadmap priorities
- Developers: routes reproducible defects and validates fix outcomes

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
