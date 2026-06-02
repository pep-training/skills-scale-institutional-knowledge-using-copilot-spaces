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

## QA Lead

### Role Summary
QA Leads oversee the testing strategy and quality assurance processes. They ensure that acceptance criteria are met, coordinate testing efforts across the team, and serve as the bridge between Developers, Product Managers, and Project Managers on quality-related matters.

### Responsibilities
- Define and maintain the testing strategy and quality gates
- Author or review acceptance criteria related to testability and quality
- Coordinate with Developers to identify test coverage gaps and improve test design
- Collaborate with Product Managers to validate feature acceptance
- Track quality metrics and report on test status during execution phase
- Escalate quality risks and blockers to Project Manager

### Goals
- Ensure all features meet acceptance criteria before release
- Maintain high quality standards and reduce post-release defects
- Provide clear, data-driven visibility into product quality
- Accelerate feedback loops between development and validation

### Typical Communication
- Daily standups and sprint planning (focus on test readiness)
- QA status reports and quality dashboards
- Collaboration with Developers during PR reviews (testability feedback)
- Weekly sync with Product Manager on feature acceptance

### Key Interactions
- **With Developers**: Review test design, identify testability improvements, validate test coverage
- **With Product Managers**: Clarify acceptance criteria, validate feature behavior, sign off on readiness
- **With Project Managers**: Report quality blockers, escalate risks, provide burndown on test completion

---

## UX Designer

### Role Summary
UX Designers ensure that proposed solutions are user-centric, accessible, and deliver an exceptional experience. They synthesize customer research, advocate for end-user needs, and collaborate with Product Managers and Developers to translate user insights into design decisions.

### Responsibilities
- Conduct or synthesize user research and usability testing
- Create wireframes, prototypes, and design specifications
- Advocate for accessibility standards and inclusive design
- Review acceptance criteria for usability and user experience alignment
- Participate in design reviews and feedback cycles with the team
- Document design decisions and rationale for future reference

### Goals
- Deliver products that are intuitive, accessible, and delightful to use
- Reduce post-launch usability issues and support burden
- Ensure customer voice is represented in all product decisions
- Build shared understanding of user needs across the team

### Typical Communication
- Design reviews with Product Managers and Developers
- User research findings and insights briefings
- Design specifications and component documentation
- Feedback during sprint planning and backlog refinement

### Key Interactions
- **With Product Managers**: Translate user research into prioritized backlog items, validate feature concepts
- **With Developers**: Provide design specs, review implementation for design fidelity, iterate on feedback
- **With QA Lead**: Contribute to acceptance criteria that include usability and accessibility requirements

---

## Release Manager

### Role Summary
Release Managers own the logistics and execution of deploying software to production. They coordinate final validation, manage the deployment process, and lead incident response if issues arise. They serve as the bridge between QA, Development, Operations, and Stakeholders during release windows.

### Responsibilities
- Plan and coordinate deployment windows and timelines
- Maintain the pre-release checklist and deployment runbook
- Coordinate final smoke tests and production validation
- Manage the rollback plan and execute rollbacks if needed
- Communicate release status to stakeholders during and after deployment
- Trigger and coordinate incident response if critical issues are discovered
- Document post-deployment metrics and lessons learned

### Goals
- Execute zero-downtime or low-impact deployments
- Minimize time to resolution if deployment issues occur
- Maintain clear communication and transparency with all stakeholders
- Continuously improve deployment processes and reduce deployment risk

### Typical Communication
- Pre-release readiness meetings with QA, Dev, and Ops
- Release notes and deployment announcements
- Real-time deployment status updates during release window
- Post-incident retrospectives and deployment retrospectives

### Key Interactions
- **With QA Lead**: Verify all test gates are passed, coordinate final smoke tests
- **With Developers**: Confirm code is ready, assist in rollback if needed
- **With Project Manager**: Report release status, escalate blockers, communicate delays
- **With Operations**: Coordinate infrastructure changes, validate post-deploy monitoring

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference these personas when updating other process documents (e.g., planning, execution, retrospectives) to ensure clear ownership and accountability.
