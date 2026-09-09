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

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality assurance strategy, test automation, and acceptance criteria verification. They collaborate with developers and product managers to ensure features meet quality standards before release.

### Responsibilities
- Develop and maintain test automation strategy and frameworks
- Define and execute unit, integration, and end-to-end test plans
- Validate acceptance criteria and Definition of Done
- Identify and document defects with clear reproduction steps
- Conduct manual QA testing for feature acceptance
- Support security scanning and compliance validation
- Participate in retrospectives to improve quality processes

### Goals
- Ensure high-quality, reliable software releases
- Reduce production defects and customer impact
- Enable fast, confident deployments through comprehensive testing

### Typical Communication
- QA planning and test strategy discussions
- Defect reports and quality metrics
- Release readiness assessments

### Interactions with Existing Roles
- **Developers:** Collaborate on test automation frameworks, review code testability, validate bug fixes
- **Product Managers:** Clarify acceptance criteria, validate feature usability, communicate quality risks
- **Project Managers:** Report on quality metrics, flag release blockers, participate in risk management

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, set strategic priorities, and grant approval for project execution. They are the ultimate decision-makers on go/no-go and scope trade-offs.

### Responsibilities
- Define business needs and success metrics
- Approve project charter and resource allocation
- Provide strategic guidance and business context
- Make decisions on scope trade-offs and priority conflicts
- Review and approve releases and key milestones
- Participate in escalation and risk mitigation decisions

### Goals
- Ensure projects deliver measurable business value
- Maintain alignment between execution and strategic goals
- Enable risk escalation and timely decision-making

### Typical Communication
- Monthly stakeholder updates and briefings
- Milestone reviews and approval gates
- Escalation and decision meetings

### Interactions with Existing Roles
- **Project Managers:** Escalate risks, request approvals, provide strategic direction
- **Product Managers:** Align on business priorities and success metrics
- **Developers:** Understand business context and project importance (via PM/PM briefings)

---

## Technical Lead/Architect

### Role Summary
Technical Leads own the technical strategy, design decisions, and architectural quality for projects. They guide developers, identify technical risks, and ensure scalability and maintainability.

### Responsibilities
- Define technical architecture and design patterns
- Lead design reviews and provide technical guidance
- Identify technical risks and propose mitigation strategies
- Ensure code quality, testing standards, and documentation
- Guide technology stack decisions and integration strategies
- Mentor developers on technical best practices
- Participate in dependency identification and cross-team coordination

### Goals
- Deliver scalable, maintainable, and secure solutions
- Reduce technical debt and minimize rework
- Enable team growth through mentorship and knowledge sharing

### Typical Communication
- Technical design reviews and architecture discussions
- Code reviews and quality standards guidance
- Risk identification and mitigation planning

### Interactions with Existing Roles
- **Developers:** Provide technical direction, review designs, mentor on best practices
- **Product Managers:** Communicate technical trade-offs and feasibility constraints
- **Project Managers:** Identify technical dependencies and risks for planning

---

## Product Lead

### Role Summary
Product Leads oversee multiple product initiatives, mentor individual Product Managers, and ensure cross-project alignment. They set product strategy and resolve prioritization conflicts.

### Responsibilities
- Set product vision and multi-project strategy
- Mentor Product Managers and oversee product decisions
- Ensure alignment across multiple concurrent initiatives
- Resolve prioritization conflicts and trade-offs
- Review and approve project one-pagers and roadmaps
- Participate in stakeholder escalations and strategic decisions
- Track cross-project success metrics and ROI

### Goals
- Maximize product value and customer impact across initiatives
- Ensure strategic alignment and resource optimization
- Develop strong product management culture and capability

### Typical Communication
- Weekly alignment with Product Managers
- Quarterly strategic reviews and roadmap updates
- Cross-project prioritization and conflict resolution

### Interactions with Existing Roles
- **Product Managers:** Mentor, approve roadmaps, resolve prioritization conflicts
- **Project Managers:** Provide product strategy and scope guidance
- **Stakeholders:** Align on strategic direction and success metrics

---

## Security & Compliance Officer

### Role Summary
Security & Compliance Officers ensure that projects meet security requirements, regulatory standards, and risk management protocols. They guide secure development practices and manage incident response.

### Responsibilities
- Define security requirements and compliance standards for projects
- Review and approve security designs and threat models
- Configure security scanning in CI/CD pipelines
- Respond to security vulnerabilities and incidents
- Conduct security reviews and penetration testing as needed
- Maintain security incident runbooks and response protocols
- Provide security guidance and training to development teams

### Goals
- Protect customer data and system integrity
- Maintain compliance with security and regulatory standards
- Enable fast, secure incident response

### Typical Communication
- Security design reviews and threat modeling sessions
- CI/CD security scanning configuration and management
- Security incident response and post-mortems

### Interactions with Existing Roles
- **Developers:** Define security requirements, guide secure coding practices, respond to vulnerabilities
- **Project Managers:** Integrate security into planning, escalate security risks, coordinate incident response
- **QA/Testing Leads:** Collaborate on security testing and scanning validation

---

## Release Manager

### Role Summary
Release Managers coordinate the deployment and release process, manage release documentation, and oversee go-live activities. They work closely with QA, developers, and operations to ensure smooth, low-risk releases.

### Responsibilities
- Plan and schedule release windows
- Coordinate deployment activities and communicate status
- Prepare and publish release notes and migration documentation
- Execute deployment checklists and smoke tests
- Manage rollback procedures and incident response during deployments
- Track release metrics and post-deployment verification
- Maintain release documentation and version control
- Coordinate stakeholder communication and announcements

### Goals
- Execute reliable, low-risk deployments
- Minimize downtime and customer impact during releases
- Maintain clear release documentation and communication

### Typical Communication
- Release planning and pre-deployment coordination
- Deployment day communication and updates
- Post-deployment verification and stakeholder announcements

### Interactions with Existing Roles
- **Developers:** Coordinate code freezes, manage deployment sequences, track deployment status
- **QA/Testing Leads:** Verify smoke tests, validate release readiness
- **Project Managers:** Report release progress, escalate deployment issues
- **Stakeholders:** Communicate release status and announcements

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
