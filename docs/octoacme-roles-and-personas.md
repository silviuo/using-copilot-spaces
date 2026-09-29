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

## Program Manager / Delivery Lead

### Role Summary
Program Managers / Delivery Leads coordinate execution across related projects or workstreams. They provide an integrated view of milestones, dependencies, and delivery risks without taking over individual project or product decisions.

### Primary Responsibilities
- Align cross-project plans, milestones, and dependencies
- Track progress and surface schedule, capacity, and delivery risks
- Coordinate resolution of blockers that span teams or projects
- Provide consolidated status and options to project and product leadership

### Key Interactions
- **Project Managers:** align plans and milestones; Project Managers remain responsible for their project plans and day-to-day coordination.
- **Product Managers:** reconcile cross-project priorities and trade-offs; Product Managers retain product and backlog priority decisions.
- **Developers:** clarify sequencing and dependencies, and route delivery blockers to the right owners without directing implementation.

### Decision-Making and Approval Boundaries
- May coordinate sequencing and recommend adjustments across workstreams.
- Does not independently change product scope, project commitments, or technical direction; obtains decisions from the accountable Product Manager, Project Manager, or Technical Lead.

### Handoffs and Escalation
- Share integrated milestones, dependencies, and risks with Project Managers and Product Managers during planning and delivery reviews.
- Escalate unresolved cross-team blockers or commitment risks to the accountable Project Manager, then Product Manager or sponsor when business trade-offs are needed.

### Goals
- Keep connected workstreams aligned and dependencies visible
- Surface delivery risks early enough for informed action
- Provide a reliable view of progress against shared milestones

### Typical Communication
- Cross-project milestone and dependency reviews
- Consolidated delivery updates, risk summaries, and decision requests

---

## Release Manager

### Role Summary
Release Managers coordinate release readiness, deployment activities, and release communications so teams can ship in a controlled and observable way.

### Primary Responsibilities
- Maintain the release schedule, readiness checklist, and release status
- Coordinate validation of acceptance criteria, CI results, release notes, and rollback plans
- Confirm deployment owners, windows, dependencies, and post-deployment checks
- Coordinate go/no-go communication and stakeholder release announcements

### Key Interactions
- **Project Managers:** align release milestones, dependencies, and status; Project Managers own project schedules and delivery risks.
- **Product Managers:** confirm the intended scope and customer-facing release notes; Product Managers own product priority and scope decisions.
- **Developers:** coordinate deployment steps, technical readiness evidence, and post-deployment verification; Developers own implementation and operational fixes.

### Decision-Making and Approval Boundaries
- Owns release coordination and readiness tracking, and may recommend whether to proceed based on agreed criteria.
- Does not waive required quality, security, or operational controls. Go/no-go approval follows the team's release policy and rests with its designated approvers; unresolved risks are escalated rather than silently accepted.

### Handoffs and Escalation
- Receive readiness evidence, release notes, and rollback or mitigation plans from delivery teams before the release window.
- Hand deployment coordination to the designated deployment operator, then share verification results and release status with Project Managers, Product Managers, and stakeholders.
- Escalate failed checks, missing approvals, or deployment incidents to the designated technical or operational owner and the Project Manager; follow the incident response process for critical failures.

### Goals
- Make release readiness and ownership clear before deployment
- Reduce avoidable deployment risk and confusion
- Ensure stakeholders receive timely, accurate release updates

### Typical Communication
- Release readiness reviews and deployment checklists
- Go/no-go summaries, release announcements, and post-deployment updates

---

## Technical Lead / Architect

### Role Summary
Technical Leads / Architects guide technical design and implementation across a team or project. They help ensure that solutions are secure, maintainable, and consistent with agreed architecture.

### Primary Responsibilities
- Guide technical design and document significant decisions
- Review implementation risks, dependencies, and non-functional requirements
- Support Developers with technical questions, code reviews, and complex problem solving
- Identify technical risks early and recommend mitigations

### Key Interactions
- **Developers:** provide design guidance and review technical work; Developers remain responsible for implementation and tests.
- **Product Managers:** explain technical options, risks, and trade-offs; Product Managers decide product value and priority.
- **Project Managers:** communicate technical estimates, dependencies, and risks that affect plans; Project Managers coordinate schedule and project-level responses.

### Decision-Making and Approval Boundaries
- Leads technical direction within agreed architecture and engineering standards, and identifies when a design decision needs broader review.
- Does not independently approve product scope, alter delivery commitments, or accept business risk on behalf of stakeholders.

### Handoffs and Escalation
- Hand approved designs, technical constraints, and decision records to Developers before implementation.
- Share implementation risks and readiness evidence with Project Managers and Release Managers as work approaches delivery.
- Escalate security, reliability, or architecture concerns through the relevant technical or security review path; raise product trade-offs with the Product Manager and schedule impacts with the Project Manager.

### Goals
- Enable sound and consistent technical decisions
- Reduce avoidable technical risk and rework
- Help the team deliver maintainable, secure solutions

### Typical Communication
- Design reviews, architecture decision records, and code reviews
- Technical risk and dependency updates during planning and delivery

---

## QA / Test Lead

### Role Summary
QA / Test Leads define and coordinate validation so the team can demonstrate that a change meets its acceptance criteria and agreed quality standards.

### Primary Responsibilities
- Define test strategy, coverage, environments, and validation ownership
- Ensure acceptance criteria and important risk scenarios are testable
- Coordinate automated and manual testing, defect triage, and test reporting
- Report quality risks and readiness evidence before release

### Key Interactions
- **Developers:** agree testability and coverage, coordinate defect fixes, and review test results; Developers own code quality and fixes.
- **Product Managers:** clarify acceptance criteria and expected user outcomes; Product Managers own product acceptance and priority decisions.
- **Project Managers:** report test progress, dependencies, and quality risks that affect milestones; Project Managers coordinate plan changes and escalations.

### Decision-Making and Approval Boundaries
- Owns the test approach and reports whether evidence meets the agreed quality criteria.
- Does not redefine product acceptance criteria or waive release controls. Product acceptance remains with the Product Manager or delegated Product Owner; release approval follows the team's release policy.

### Handoffs and Escalation
- Receive prioritized work and acceptance criteria from Product Managers and Project Managers during planning.
- Share test results, unresolved defects, and explicit quality risks with Developers, Project Managers, Product Managers, and Release Managers before release.
- Escalate critical defects or unmet quality gates to the Project Manager and Release Manager; seek a documented decision from the designated approver rather than treating a risk as accepted.

### Goals
- Provide trustworthy evidence of product quality
- Find important defects and risks early
- Make release-impacting quality gaps visible to decision-makers

### Typical Communication
- Test plans, automated test results, defect triage, and readiness reports
- Quality risk updates during sprint reviews and release readiness checks

---

## Stakeholder / Product Owner

### Role Summary
Stakeholders provide business context, constraints, and feedback. A Product Owner is a designated stakeholder who represents users or the business in day-to-day backlog clarification and product acceptance within delegated authority. This complements, rather than replaces, the Product Manager's ownership of product vision and overall prioritization.

### Primary Responsibilities
- Explain business goals, user needs, and relevant constraints
- Clarify backlog items and acceptance criteria with the Product Manager
- Provide timely feedback on delivered work and make delegated product-acceptance decisions
- Communicate business impact and raise emerging needs or concerns

### Key Interactions
- **Product Managers:** align on outcomes and priorities; the Product Manager retains overall roadmap and backlog priority ownership.
- **Project Managers:** provide timely decisions, dependencies, and stakeholder feedback needed for planning; Project Managers coordinate plans, risks, and status.
- **Developers:** answer questions about user or business needs and review demonstrations against agreed criteria; Developers own technical implementation and estimates.

### Decision-Making and Approval Boundaries
- A Product Owner may clarify requirements and accept work against agreed criteria only within explicitly delegated authority.
- Other stakeholders advise and provide feedback; they do not directly reprioritize committed work. Changes to scope or priority go through the Product Manager and are coordinated with the Project Manager. Technical and release approvals remain with their designated owners.

### Handoffs and Escalation
- Provide validated business needs and acceptance criteria to the Product Manager for backlog refinement and to the delivery team before work begins.
- Return timely acceptance feedback and unresolved business questions to the Product Manager; communicate decisions that affect scope or milestones to the Project Manager.
- Escalate conflicting stakeholder needs or material scope trade-offs to the Product Manager; escalate business-impacting unresolved decisions to the sponsor through the agreed project path.

### Goals
- Keep delivery focused on user and business outcomes
- Make requirements and acceptance decisions timely and actionable
- Ensure stakeholder feedback reaches the people who can act on it

### Typical Communication
- Backlog refinement, demonstrations, and acceptance reviews
- Business context, priority clarification, and milestone or outcome feedback

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
