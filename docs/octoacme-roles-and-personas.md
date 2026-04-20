# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Table of Contents

- [Developers](#developers)
- [Product Managers](#product-managers)
- [Project Managers](#project-managers)
- [QA Lead](#qa-lead)
- [Business Analyst](#business-analyst)
- [UX/UI Designer](#uxui-designer)
- [Scrum Master](#scrum-master)
- [Security Champion](#security-champion)
- [Role Interaction & Hand-off Patterns](#role-interaction--hand-off-patterns)
- [Role Onboarding Checklist](#role-onboarding-checklist)
- [How these personas are used in the exercise](#how-these-personas-are-used-in-the-exercise)

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

### Key Interactions
- **← Business Analyst**: Receives refined user stories and acceptance criteria; clarifies edge cases before implementation begins.
- **← UX/UI Designer**: Receives design specs and assets; raises feasibility concerns early.
- **→ QA Lead**: Hands off completed features with test coverage notes; participates in defect triage.
- **↔ Security Champion**: Consults on secure coding patterns; responds to findings from code scans.

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

### Key Interactions
- **→ Business Analyst**: Provides strategic context and high-level requirements for detailed analysis.
- **→ UX/UI Designer**: Commissions user research and design exploration; validates designs against product goals.
- **← Project Manager**: Receives schedule/risk updates; collaborates on scope trade-offs.
- **← QA Lead**: Reviews test outcomes and acceptance sign-off; informed of defect trends.

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

### Key Interactions
- **↔ Scrum Master**: Collaborates on sprint health and ceremony facilitation; aligns on impediment escalation.
- **→ Security Champion**: Ensures security tasks are tracked in the project plan; escalates unresolved security risks.
- **← All roles**: Single point of contact for cross-team dependencies and schedule impact.

---

## QA Lead

### Role Summary
The QA Lead owns the overall quality strategy for a project. They define test plans, coordinate testing activities, advocate for quality gates, and drive continuous improvement of QA processes.

### Responsibilities
- Define and maintain the test plan, test strategy, and quality acceptance criteria
- Coordinate manual and automated testing across functional areas
- Triage and prioritize defects; escalate blocking issues to the Project Manager
- Review and approve the Definition of Done (DoD) from a quality perspective
- Track and report on test coverage, defect rates, and release readiness
- Mentor developers and team members on testing best practices
- Drive automation of regression suites and CI quality checks

### Goals
- Ensure every release meets agreed quality standards before reaching production
- Reduce defect escape rate through proactive testing strategies
- Build shared quality ownership across the entire team

### Typical Communication
- Sprint planning and review: present test coverage and outstanding defects
- Daily standups: flag blocking defects or testing bottlenecks
- Pre-release quality gate report shared with Project Manager and Product Manager
- Defect triage sessions as needed

### Key Interactions
- **← Developers**: Receives features for testing; collaborates on test coverage and defect reproduction steps.
- **→ Product Manager**: Provides release readiness sign-off and quality metrics.
- **→ Project Manager**: Escalates blockers and reports on QA status weekly.
- **↔ Business Analyst**: Validates that acceptance criteria are testable before sprint begins.
- **↔ Security Champion**: Coordinates on security test cases and vulnerability remediation verification.

---

## Business Analyst

### Role Summary
Business Analysts bridge product strategy and technical delivery. They translate business needs into clear, actionable requirements and ensure that built solutions meet stakeholder expectations.

### Responsibilities
- Elicit, document, and maintain business and functional requirements
- Decompose epics into well-formed user stories with clear acceptance criteria
- Facilitate requirements workshops and stakeholder interviews
- Clarify scope ambiguities with Product Manager and development team
- Validate delivered features against documented business requirements
- Maintain traceability between requirements and backlog items

### Goals
- Eliminate ambiguity before work enters the sprint
- Reduce rework caused by misunderstood requirements
- Create a shared understanding of "done" across business and technical stakeholders

### Typical Communication
- Requirements workshops and user story refinement sessions
- Written user stories and acceptance criteria in the project backlog
- Regular check-ins with Product Manager and lead Developer
- Stakeholder demos and validation sessions

### Key Interactions
- **← Product Manager**: Receives high-level vision and priorities; refines them into detailed requirements.
- **→ Developers**: Hands off refined user stories with clear acceptance criteria and context.
- **→ QA Lead**: Ensures acceptance criteria are testable; reviews test cases for coverage completeness.
- **↔ UX/UI Designer**: Collaborates to align requirements with user experience goals; reviews designs for requirement coverage.
- **↔ Project Manager**: Flags scope changes and dependency impacts promptly.

---

## UX/UI Designer

### Role Summary
UX/UI Designers are responsible for the user experience strategy and interface design of product features. They conduct user research, create wireframes and prototypes, and ensure designs are usable, accessible, and aligned with product goals.

### Responsibilities
- Conduct user research (interviews, usability tests, surveys) to inform design decisions
- Create wireframes, prototypes, and high-fidelity mockups
- Define interaction patterns and component guidelines
- Collaborate with Business Analysts and Product Managers to align designs with requirements
- Deliver design specs and assets to Developers; support implementation questions
- Validate shipped features against design intent and usability standards
- Ensure designs meet accessibility standards (e.g., WCAG 2.1 AA)

### Goals
- Deliver intuitive, accessible, and visually consistent user experiences
- Reduce development rework through clear design documentation
- Advocate for user needs throughout the entire project lifecycle

### Typical Communication
- Design reviews and critique sessions with Product Manager and Developers
- Annotated design files (e.g., Figma) shared with the delivery team
- Usability test findings presented to the team during sprint reviews
- Async feedback via design comments; sync sessions for complex interactions

### Key Interactions
- **← Product Manager**: Receives product goals and feature requirements; aligns on design priorities.
- **← Business Analyst**: Uses requirements to scope design work; validates that designs cover all defined user scenarios.
- **→ Developers**: Hands off design specs, assets, and interaction notes; answers implementation questions.
- **↔ QA Lead**: Provides design acceptance criteria for visual and interaction testing.
- **↔ Security Champion**: Reviews designs for data exposure or user trust concerns (e.g., sensitive data display).

---

## Scrum Master

### Role Summary
The Scrum Master is a servant-leader who ensures the team follows agile principles and practices effectively. They facilitate scrum ceremonies, remove impediments, protect the team from distractions, and coach the organization on continuous improvement.

### Responsibilities
- Facilitate sprint planning, daily standups, sprint reviews, and retrospectives
- Identify and remove impediments that block team progress
- Coach team members on agile principles and the Scrum framework
- Shield the team from external interruptions and scope creep mid-sprint
- Track and communicate sprint health (velocity, burn-down, blockers)
- Foster a culture of continuous improvement and psychological safety
- Escalate unresolved impediments to the Project Manager

### Goals
- Enable consistent, predictable delivery by maintaining sprint health
- Build a self-organizing, high-performing team
- Drive incremental process improvements through retrospective learnings

### Typical Communication
- Daily standups: surface and address impediments in real time
- Sprint planning and retrospective facilitation
- Weekly impediment log shared with Project Manager
- Coaching conversations with individual team members

### Key Interactions
- **↔ Project Manager**: Coordinates on schedule impacts of impediments; shares velocity data for forecasting.
- **↔ Developers**: Removes technical and organizational blockers; facilitates planning and estimation.
- **← Product Manager**: Receives backlog priorities and ensures planning reflects them accurately.
- **↔ All roles**: Ensures everyone understands sprint goals and agile ceremonies; facilitates alignment.

---

## Security Champion

### Role Summary
The Security Champion is an embedded advocate for secure engineering practices. They identify security risks early in the delivery lifecycle, promote secure coding standards, coordinate with security teams, and ensure security requirements are addressed in every phase.

### Responsibilities
- Review requirements, designs, and code for potential security concerns
- Conduct or coordinate threat modeling for new features and changes
- Promote and enforce secure coding guidelines and dependency hygiene
- Triage security findings from automated scans (SAST, SCA, secret scanning)
- Coordinate with external security/DevSecOps teams on assessments and remediation
- Ensure security acceptance criteria are defined and verified before release
- Maintain a security risk register and escalate critical findings to the Project Manager

### Goals
- Prevent security vulnerabilities from reaching production
- Build security awareness and shared responsibility across the team
- Reduce remediation cost by surfacing security issues as early as possible

### Typical Communication
- Security review notes added to design docs and PRs
- Security risk register updates shared with Project Manager weekly
- Threat model sessions at the start of major feature work
- Findings and remediation status reported at sprint reviews

### Key Interactions
- **→ Developers**: Provides secure coding guidance; reviews PRs for security issues; triages scan findings.
- **→ QA Lead**: Collaborates on security test cases and validates remediation of vulnerabilities.
- **← Project Manager**: Informs on security risks and timeline; escalates critical unresolved issues.
- **↔ Business Analyst / UX/UI Designer**: Reviews requirements and designs for privacy and data security concerns early.
- **↔ Product Manager**: Raises security trade-offs that may affect scope or timelines.

---

## Role Interaction & Hand-off Patterns

Smooth hand-offs between roles reduce rework and ambiguity. The table below summarizes the most important transitions.

| From | To | Hand-off Artifact / Action |
|---|---|---|
| Product Manager | Business Analyst | Strategic brief, high-level requirements, prioritized epics |
| Business Analyst | Developers | Refined user stories with testable acceptance criteria |
| Business Analyst | QA Lead | Acceptance criteria review; confirmation that criteria are testable |
| Business Analyst | UX/UI Designer | Requirements scope for design exploration |
| UX/UI Designer | Developers | Design specs, assets (e.g., Figma link), interaction annotations |
| UX/UI Designer | QA Lead | Visual and interaction acceptance criteria |
| Developers | QA Lead | Feature branch or build ready for testing; test coverage notes in PR |
| QA Lead | Project Manager | Release readiness report; outstanding defect list |
| QA Lead | Product Manager | Quality sign-off or escalation before release |
| Security Champion | Developers | Security findings, secure coding guidance, PR review comments |
| Security Champion | Project Manager | Security risk register updates; critical escalations |
| Scrum Master | Project Manager | Impediment log; sprint velocity and burn-down data |

### General Hand-off Checklist
Before passing work to the next role, confirm:
- [ ] The deliverable meets agreed acceptance criteria for this stage
- [ ] Open questions or known gaps are documented and communicated
- [ ] The receiving role has been notified (async or sync as appropriate)
- [ ] Any downstream risks or dependencies are flagged

---

## Role Onboarding Checklist

Use this checklist when a new team member joins in any role. Customize the role-specific section as needed.

### All Roles
- [ ] Introduced to the team and key contacts for each role
- [ ] Access to project repository, project board, and communication channels granted
- [ ] Reviewed [Project Management Overview](octoacme-project-management-overview.md)
- [ ] Reviewed this Roles & Personas document
- [ ] Reviewed the [Project Initiation Guide](octoacme-project-initiation.md) and [Project Planning](octoacme-project-planning.md) docs
- [ ] Shadowed at least one of each: standup, sprint planning, sprint review, retrospective
- [ ] Understands escalation paths for blockers (see [Risks & Communication](octoacme-risks-and-communication.md))

### Developers
- [ ] Local development environment set up and PR workflow verified
- [ ] CI/CD pipeline reviewed; knows how to interpret test and lint results
- [ ] Reviewed [Execution & Tracking](octoacme-execution-and-tracking.md) and branching conventions
- [ ] Completed first code review as author and reviewer

### QA Lead
- [ ] Existing test plan and test suite reviewed
- [ ] QA tooling access configured (test management, CI dashboards)
- [ ] Reviewed Definition of Done and release criteria with Project Manager and Product Manager
- [ ] Scheduled recurring defect triage with development team

### Business Analyst
- [ ] Existing requirements backlog reviewed and gaps identified
- [ ] Stakeholder map reviewed; key business contacts introduced
- [ ] Reviewed backlog refinement process and story template (see [Project Planning](octoacme-project-planning.md))
- [ ] First user story workshop facilitated with Product Manager and Developers

### UX/UI Designer
- [ ] Access to design tools and shared component library granted
- [ ] Existing design artifacts and brand guidelines reviewed
- [ ] User research archive reviewed; research cadence understood
- [ ] First design review session held with Product Manager and Developers

### Scrum Master
- [ ] Team working agreements and Definition of Done reviewed
- [ ] Sprint cadence and ceremony schedule confirmed
- [ ] Impediment escalation path agreed with Project Manager
- [ ] Retrospective backlog of action items reviewed

### Security Champion
- [ ] Security tooling access configured (SAST, SCA, secret scanning dashboards)
- [ ] Existing security risk register reviewed
- [ ] Threat modeling process and templates reviewed with team
- [ ] First security review of current codebase or feature backlog completed

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The [Role Interaction & Hand-off Patterns](#role-interaction--hand-off-patterns) section helps simulate realistic cross-role collaboration scenarios.

