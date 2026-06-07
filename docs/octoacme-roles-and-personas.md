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

## QA / Testing

(Existing QA guidance retained — no change to summary)

---

## Stakeholders

(Existing stakeholder guidance retained — no change to summary)

---

## Additional Personas (New)

These roles are recommended additions to improve clarity, accountability, and cross-functional handoffs. Each includes a brief summary, key responsibilities, and how the role interacts with existing core roles.

### UX Designer

Role summary:
- Owns user experience, interaction design, and usability validation for features.

Key responsibilities:
- Collaborate with PdM to translate user needs into design solutions.
- Produce wireframes, prototypes, and user flows.
- Run or coordinate usability testing and incorporate findings.
- Provide design assets and documentation for development handoffs.
- Validate acceptance criteria from a usability perspective.

Interactions:
- Works closely with Product Manager (requirements, user research).
- Collaborates with Developers for implementation details and constraints.
- Provides QA and PM with acceptance criteria focused on usability and accessibility.
- Surface risks to PM/Developer when designs are infeasible or introduce UX debt.

### Security / Compliance Lead

Role summary:
- Ensures features satisfy organizational security, privacy, and regulatory requirements.

Key responsibilities:
- Review designs and implementation plans for security and privacy risks.
- Define required security acceptance criteria and required scans.
- Coordinate required compliance checks and evidence collection.
- Advise on data handling, encryption, logging, and access controls.
- Validate releases meet minimal compliance standards before production.

Interactions:
- Engages during planning to identify risks and required mitigations.
- Works with Developers to define secure-by-design approaches and remediation timelines.
- Coordinates with PM for release gating and with QA to include security test cases.
- Escalates unresolved security blockers to PM/Product Lead as needed.

### Customer Success Manager (CSM)

Role summary:
- Represents customer adoption, feedback, and readiness in product decisions and releases.

Key responsibilities:
- Surface customer requests, pain points, and adoption metrics to Product.
- Coordinate pilot programs and early access with customers.
- Prepare support and enablement materials with Technical Writer.
- Monitor post-release adoption and escalate issues impacting customers.

Interactions:
- Partners with PdM to validate use cases and prioritize features.
- Works with PM and Developers to coordinate release timing for customer pilots.
- Liaises with Support and Sales to ensure readiness and consistent messaging.
- Provides feedback loops (metrics, anecdotes) to the team post-release.

### Technical Writer

Role summary:
- Produces product documentation, release notes, and internal runbooks to support users and teams.

Key responsibilities:
- Draft and maintain user-facing documentation and internal guides.
- Create release notes and migration instructions when needed.
- Ensure documentation is included as part of the DoD for features.
- Coordinate with Developers, PdM, and CSM to capture accurate content.

Interactions:
- Receives feature context and acceptance criteria from PdM and Developers.
- Collaborates with CSM on customer-facing materials and rollout communications.
- Works with PM to ensure documentation tasks are tracked on the project board.
- Drives handoff checklist items for release readiness (docs, training materials).

---

## How to use these personas
- Add the relevant persona(s) to the Project One-pager and project board when scoping work.
- Use the "Interactions" sections to define handoff checkpoints in backlog items (e.g., "Design accepted", "Security reviewed", "Docs drafted").
- For small projects these roles may be combined; the key is to document who owns each responsibility.
