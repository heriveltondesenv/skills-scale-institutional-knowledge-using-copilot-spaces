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

## Additional Proposed Personas (new)

### Technical Lead (TL)
Role Summary:
- The TL provides technical direction for the project, owning architecture decisions and ensuring technical trade-offs are visible and communicated.

Responsibilities:
- Drive technical design and architecture choices for features and integrations
- Mentor developers and promote engineering standards
- Identify technical risks and propose mitigations or spikes
- Lead design reviews for complex or high-risk changes

Interactions:
- Works closely with Developers to unblock implementation and review proposals
- Aligns with Project Manager on delivery trade-offs and timelines
- Consults Product Manager on feasibility and impact of features
- Escalates major technical trade-offs to engineering leadership when needed

---

### UX / Design Lead
Role Summary:
- Owns user experience and design vision for features, ensuring usability and alignment with product outcomes.

Responsibilities:
- Produce and validate designs, prototypes, and accessibility considerations
- Run or coordinate user research and usability testing
- Hand off specs and design assets to Developers and QA
- Define UX acceptance criteria for features

Interactions:
- Partners with Product Manager to align UX with success metrics and user needs
- Reviews acceptance criteria and collaborates during planning
- Works with QA and Accessibility Specialist to ensure acceptance and compliance

---

### Site Reliability Engineer (SRE) / On-call Engineer
Role Summary:
- Ensures reliability, monitoring, and operational readiness for services in production.

Responsibilities:
- Operate and tune monitoring, alerting, and runbooks
- Lead incident response and post-incident retrospectives
- Implement scalable and observable infrastructure patterns
- Maintain SLIs/SLOs and advise on reliability trade-offs

Interactions:
- Coordinates with Developers for deployment, instrumentation, and fixes
- Works with Project Manager and Release Manager on deployment windows and rollback plans
- Escalates security or operational risks to PM and Security Engineer

---

### Security Engineer
Role Summary:
- Advises on secure design, threat modeling, and vulnerability remediation.

Responsibilities:
- Conduct security reviews and vulnerability assessments
- Define security acceptance criteria and secure-by-default guardrails
- Coordinate with Developers and SRE on fixes and mitigations
- Integrate security checks into CI/CD and release gating

Interactions:
- Works with Product Manager and PM to assess security-related scope and timelines
- Provides inputs to CI/CD and release pipelines for security gating and verification
- Participates in post-incident reviews for security events

---

### Release Manager / Release Engineer
Role Summary:
- Owns release orchestration, verification steps, and communication for production deployments.

Responsibilities:
- Coordinate release schedules and pre-release verification
- Maintain release notes, rollback plans, and release checklists
- Ensure CI/CD pipelines and automation support safe, repeatable releases
- Run post-deploy verification and coordinate post-release communication

Interactions:
- Works with SRE, Developers, QA, and PM to schedule and execute releases
- Notifies stakeholders and support teams about release contents and risks
- Coordinates rollback when needed and documents lessons learned

---

### Data Analyst / Data Engineer
Role Summary:
- Ensures measurement, analytics instrumentation, and data availability to validate product success metrics.

Responsibilities:
- Define event schemas and metrics required for success criteria
- Build dashboards and analyses to inform product decisions
- Validate data correctness post-release and alert on instrumentation gaps

Interactions:
- Partners with Product Manager on success metrics and measurement plans
- Works with Developers to implement instrumentation and tracking
- Shares findings with PM, PdM, and stakeholders in regular syncs

---

### Customer Support / Success Liaison
Role Summary:
- Acts as the bridge between customer feedback/support signals and the delivery team.

Responsibilities:
- Surface prioritized customer issues, trends, and feature requests
- Provide reproduction details, impact, and customer context for incidents
- Communicate release impacts, timelines, and workarounds to customers/support

Interactions:
- Feeds early signals and escalations to PM and PdM
- Works with Developers and QA to reproduce and prioritize fixes
- Helps prepare customer-facing release notes or communications when required

---

### Accessibility Specialist
Role Summary:
- Ensures products meet accessibility standards and offer usable experiences for all users.

Responsibilities:
- Conduct accessibility reviews and testing and provide remediation guidance
- Define accessibility acceptance criteria and test cases
- Advocate for inclusive design and ensure documentation of accessibility decisions

Interactions:
- Works with UX/Design Lead on accessible design patterns
- Provides test cases and acceptance criteria for QA and Developers
- Coordinates with Product Manager on accessibility trade-offs and timelines

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance
