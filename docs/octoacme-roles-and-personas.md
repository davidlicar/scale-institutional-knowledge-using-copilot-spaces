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

## Scrum Master

### Role Summary
Scrum Masters facilitate agile ceremonies, remove team impediments, and coach teams in agile principles and continuous improvement. They are critical in iterative delivery organizations and partner closely with Project Managers and Product Managers to optimize team velocity and process health.

### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Identify and help remove team impediments and blockers
- Coach the team on agile principles and practices
- Maintain sprint health and process adherence
- Escalate systemic issues to Project Manager or Product Manager
- Track team metrics (velocity, cycle time, burndown)

### Goals
- Enable consistent, predictable team delivery
- Foster psychological safety and continuous improvement
- Reduce process friction and unplanned work
- Maintain team morale and engagement

### Typical Communication
- Facilitation of all agile ceremonies
- 1-on-1s with team members to discuss impediments
- Weekly sync with PM and PdM on process health
- Retrospective action item tracking and follow-up

### Interaction with Other Roles
- **With Project Manager**: Escalates scheduling and resource risks; provides velocity data for forecasting
- **With Product Manager**: Coordinates backlog refinement; provides capacity planning input
- **With Developers & QA**: Removes blockers; facilitates knowledge sharing and process improvements

---

## UX Designer

### Role Summary
UX Designers advocate for user needs, conduct design research, and create wireframes and prototypes. They collaborate closely with Product Managers and Developers to ensure that UI/UX aligns with product requirements and delivers excellent usability.

### Responsibilities
- Conduct user research, interviews, and usability testing
- Create wireframes, prototypes, and design specifications
- Define user journeys and interaction patterns
- Collaborate with Developers on implementation feasibility and accessibility
- Ensure design consistency across features and releases
- Iterate on designs based on user feedback and metrics

### Goals
- Deliver intuitive, user-centered products
- Reduce user friction and support burden
- Increase feature adoption and customer satisfaction
- Maintain design consistency and brand alignment

### Typical Communication
- Design reviews with Product Manager and Developers
- User research findings and recommendations
- Design specifications and component documentation
- Design system contributions and updates

### Interaction with Other Roles
- **With Product Manager**: Aligns on user personas, success metrics, and design direction
- **With Developers**: Collaborates on feasibility, accessibility, and implementation details
- **With Project Manager**: Provides design timeline estimates for planning
- **With QA/Testing**: Defines acceptance criteria for UI/UX features

---

## Release Manager

### Role Summary
Release Managers coordinate release scheduling, readiness, and communication across all teams. They ensure that pre-release checklists are followed, lead go/no-go decisions, and support post-release incident management and monitoring.

### Responsibilities
- Coordinate release scheduling and timelines
- Ensure pre-release checklists are completed (testing, security scans, documentation)
- Lead go/no-go decision meetings with stakeholders
- Coordinate deployment execution (staging, production, rollback)
- Manage release notes and stakeholder communication
- Coordinate post-release monitoring and incident response
- Facilitate post-release retrospectives and action items

### Goals
- Minimize release risk and production incidents
- Ensure consistent, predictable release cadence
- Maintain transparency and stakeholder confidence
- Enable rapid rollback or remediation if issues arise

### Typical Communication
- Pre-release readiness meetings with Dev, QA, Ops
- Release notes and stakeholder announcements
- Deployment coordination and status updates
- Post-incident war rooms and retrospectives

### Interaction with Other Roles
- **With Project Manager**: Aligns on release timing and milestones
- **With Developers & QA**: Ensures pre-release criteria are met
- **With Product Manager**: Communicates feature readiness and stakeholder expectations
- **With Security**: Coordinates security scanning and incident response

---

## Stakeholders vs. Sponsors

### Stakeholders

#### Role Summary
Stakeholders are individuals or teams who are impacted by, depend on, or will use the project outcome. They provide ongoing input, feedback, and validation throughout the project lifecycle.

#### Responsibilities
- Provide domain expertise and user perspective
- Give feedback on designs, prototypes, and releases
- Validate that solutions meet their needs
- Participate in user acceptance testing (UAT) when applicable
- Raise concerns or dependencies early

#### Typical Communication
- Milestone reviews and demos
- Feedback on prototypes and specifications
- Ad-hoc consultation on domain-specific questions

### Sponsors

#### Role Summary
Sponsors are senior stakeholders who fund, authorize, and provide executive air cover for projects. They make escalation decisions, approve scope changes, and hold accountability for business outcomes.

#### Responsibilities
- Authorize project initiation and resource allocation
- Make go/no-go decisions at key gates
- Escalate organizational or political barriers
- Approve significant scope, timeline, or budget changes
- Hold ultimate accountability for project success and ROI

#### Goals
- Ensure strategic alignment with organizational priorities
- Remove high-level barriers to project success
- Maximize return on investment

#### Typical Communication
- Project initiation and kick-off
- Milestone and gate reviews
- Escalation and exception handling
- Business outcome reviews and lessons learned

#### Distinction from Stakeholders
- **Stakeholders** have ongoing involvement and provide feedback; they use or depend on the outcome
- **Sponsors** have decision authority and budget control; they authorize and escalate
- A person may wear both hats (e.g., a director who funds a project and uses its output), but the responsibilities differ

---

## Security Champion

### Role Summary
Security Champions are advocates who ensure security requirements are surfaced early in planning, coordinate security assessments, and lead threat modeling workshops. They bridge the development and security teams to embed security practices into project delivery.

### Responsibilities
- Identify and surface security requirements during planning and design phases
- Lead threat modeling sessions and security design reviews
- Coordinate security scanning and vulnerability assessments in CI/CD
- Partner with the Security team on compliance and audit requirements
- Communicate security findings and remediation priorities to the team
- Support incident response and post-incident security improvements

### Goals
- Embed security into project delivery from the start
- Reduce security-related rework and production incidents
- Maintain compliance and reduce organizational risk
- Build security awareness and culture across teams

### Typical Communication
- Security requirements workshops and threat modeling sessions
- Security assessment reports and remediation guidance
- Weekly sync with Security team and Project Manager on risk status
- Incident response and post-incident retrospectives

### Interaction with Other Roles
- **With Product Manager & Project Manager**: Surfaces security requirements early; participates in planning
- **With Developers**: Reviews security implementation; provides guidance on secure coding practices
- **With Release Manager**: Ensures security scanning is completed before deployment
- **With Security team**: Acts as the embedded security advocate; escalates critical findings

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Understand the interactions between roles to identify communication and handoff points in your project workflows.
