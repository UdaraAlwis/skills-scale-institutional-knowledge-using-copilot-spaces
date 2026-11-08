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

### Interaction with Other Roles
- Work with Product Managers to clarify scope, value, and acceptance criteria
- Partner with Project Managers on timeline, dependencies, and blockers
- Collaborate with QA on test coverage and defect triage
- Work with UX/Product Designers to ensure implementation matches intended user experience
- Coordinate with Tech Leads on architecture, technical trade-offs, and implementation quality

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

### Interaction with Other Roles
- Align with Project Managers on milestones, dependencies, and stakeholder communication
- Partner with Developers and Tech Leads on feasibility, trade-offs, and sequencing
- Work with UX/Product Designers to refine user needs, flows, and experience priorities
- Coordinate with QA to confirm acceptance criteria and release readiness
- Escalate business or customer-impacting issues with stakeholders and sponsors

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

### Interaction with Other Roles
- Partner with Product Managers on priorities, milestones, and stakeholder alignment
- Coordinate with Developers and Tech Leads on execution risks, dependency tracking, and delivery pace
- Work with QA to monitor quality risks and release readiness
- Collaborate with UX/Product Designers on sequencing and milestone planning
- Escalate material risks to sponsors or leadership when needed

---

## QA / Test Engineer

### Role Summary
QA / Test Engineers define and execute the quality strategy for a project. They validate whether the product meets acceptance criteria, catch regressions early, and inform release readiness.

### Responsibilities
- Define and maintain the test strategy and test plan
- Validate acceptance criteria and user-facing functionality
- Execute manual and automated testing across relevant workflows
- Partner with Developers to reproduce issues and verify fixes
- Identify quality risks, release blockers, and gaps in coverage
- Support release readiness and regression prevention

### Goals
- Improve product confidence before release
- Reduce defect escape rate and production risk
- Ensure quality is testable, measurable, and visible to the team

### Typical Communication
- Test plans, defect reports, and regression summaries
- Quality and readiness discussions with Product Managers and release owners
- Coordination with Developers on defect triage and fix validation
- Status updates in standups, sprint reviews, and release checkpoints

### Interaction with Other Roles
- Works with Developers to validate fixes, identify edge cases, and improve testability
- Aligns with Product Managers on acceptance criteria and quality expectations; reports gaps rather than redefining product scope
- Provides quality risks and readiness evidence to Project Managers for milestone and release coordination
- Collaborates with UX/Product Designers to validate usability and intended flows
- Partners with Security / Privacy Leads on relevant control testing

---

## UX / Product Designer

### Role Summary
UX / Product Designers lead user research and interaction design, translating user needs and product goals into usable, accessible experiences.

### Responsibilities
- Conduct or contribute to user research and usability discovery
- Translate customer and business needs into user flows, journey maps, and prototypes
- Collaborate with Product Managers on problem framing and user outcomes
- Work with Developers and Tech Leads to ensure designs are feasible and testable
- Identify accessibility, usability, and edge-case considerations
- Support validation of the product experience before and after release

### Goals
- Deliver intuitive, useful, and user-centered experiences
- Reduce rework by aligning design with product goals early
- Make the solution easier to learn and use

### Typical Communication
- Design reviews with Product Managers and Developers
- User research summaries and prototype feedback
- Collaboration in sprint planning and backlog refinement
- Validation feedback during QA and release checks

### Interaction with Other Roles
- Works with Product Managers to clarify user needs, outcomes, and product trade-offs; the Product Manager owns product priorities
- Aligns with Developers and Tech Leads on feasibility, implementation constraints, and edge cases
- Coordinates with QA to make designs testable and validate usability
- Shares design dependencies and sequencing needs with Project Managers
- Consults Security / Privacy Leads where design decisions affect sensitive data or privacy

---

## Tech Lead / Engineering Lead

### Role Summary
Tech Leads guide technical design and implementation quality across the engineering team. They advise on technical decisions and help keep delivery aligned with architecture, maintainability, and execution needs.

### Responsibilities
- Guide technical design and architecture decisions
- Coordinate engineering dependencies and sequencing
- Review implementation quality and technical trade-offs
- Mentor Developers and support technical problem-solving
- Identify delivery risks, technical debt, and integration concerns early
- Advise Product Managers on scope and feasibility

### Goals
- Deliver a technically sound solution that supports the roadmap
- Reduce delivery risk and avoid preventable rework
- Maintain consistent engineering standards and sustainable delivery

### Typical Communication
- Design discussions, technical planning, and architecture reviews
- Delivery risk updates in project syncs and standups
- Dependency tracking with Project Managers and other teams
- Technical trade-off discussions with Product Managers

### Interaction with Other Roles
- Advises Product Managers on feasibility and technical trade-offs; product priority decisions remain with the Product Manager
- Coordinates with Project Managers on engineering dependencies, delivery risks, and milestone forecasts
- Guides Developers on implementation decisions, reviews, and code-quality standards
- Collaborates with QA on testability, automation opportunities, and risk-based validation
- Engages Security / Privacy Leads when architecture, controls, or data handling need review

---

## Security / Privacy Lead

### Role Summary
Security / Privacy Leads advise the team on security and privacy requirements, risks, and controls throughout design, delivery, and release.

### Responsibilities
- Clarify applicable security, privacy, and compliance requirements
- Identify and assess risks across systems, data, and workflows
- Partner with Developers and QA on controls, testing, and remediation
- Recommend mitigations and document residual risks
- Escalate material concerns through the appropriate project and product leadership
- Contribute to secure release readiness and risk communication

### Goals
- Reduce security and privacy risk to an acceptable level
- Embed controls early in design and delivery
- Support safe, compliant, and trustworthy product decisions

### Typical Communication
- Security and privacy reviews and assessments
- Risk summaries, mitigation recommendations, and escalation updates
- Coordination with engineering, QA, and release stakeholders
- Review inputs during planning and pre-release readiness

### Interaction with Other Roles
- Advises Developers and Tech Leads on controls and secure implementation; engineering owners implement agreed changes
- Coordinates with QA on relevant test coverage and remediation verification
- Works with Product Managers to explain user impact and risk trade-offs
- Informs Project Managers of material risks, dependencies, and escalation needs
- Raises material concerns to the appropriate leadership; does not replace formal security incident or risk-acceptance authorities

---

## Customer Support / Operations Representative

### Role Summary
Customer Support / Operations Representatives bring customer-facing and operational needs into planning and release decisions, helping ensure the product is supportable after launch.

### Responsibilities
- Share support trends, user pain points, and operational needs with the team
- Help prepare support processes, customer communications, runbooks, and handoffs
- Participate in release readiness for operational continuity and customer impact
- Feed post-release issues and customer feedback back to the team
- Identify training, documentation, and service-readiness needs

### Goals
- Improve the customer experience before and after launch
- Reduce operational friction and avoidable support escalations
- Ensure readiness for rollout, adoption, and day-to-day operations

### Typical Communication
- Support issue reviews and customer feedback summaries
- Release and operational readiness check-ins
- Coordination with Product and Project Managers on customer impact and follow-up
- Escalation of recurring or high-impact issues

### Interaction with Other Roles
- Shares customer and operational context with Product Managers to inform priorities and outcomes
- Coordinates with Developers and Tech Leads on issue patterns, edge cases, and supportability concerns
- Supports QA with real-world workflow considerations and regression awareness
- Provides Project Managers with operational dependencies and launch-readiness needs
- Works with UX/Product Designers on usability feedback, customer documentation, and training needs

---

## Role Design Notes

- These are candidate roles to validate with relevant stakeholders and tailor to each project's size, risk, and organizational structure.
- Roles do not require separate people: especially on smaller projects, one person may cover multiple responsibilities.
- Use these definitions to clarify accountability and handoffs without adding unnecessary process overhead.

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
