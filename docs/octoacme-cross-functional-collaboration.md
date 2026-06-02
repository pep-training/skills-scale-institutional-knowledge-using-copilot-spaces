# OctoAcme — Cross-Functional Collaboration Guide

## Purpose
Provide guidance on how different roles collaborate effectively throughout the project lifecycle, reducing handoff gaps and improving accountability.

## Role Interactions by Project Phase

### Initiation Phase
- **Product Manager** defines the problem and success metrics
- **Project Manager** creates the initial timeline and identifies stakeholder needs
- **UX Designer** (if applicable) participates in problem validation and early research
- **Key Deliverable**: Project One-pager approved by all stakeholders

### Planning Phase
- **Product Manager** prioritizes and refines the backlog with acceptance criteria
- **UX Designer** contributes usability and accessibility requirements
- **QA Lead** defines testing strategy and quality gates
- **Developers** estimate effort and identify technical dependencies
- **Project Manager** creates the release plan and risk register
- **Key Deliverable**: Backlog with clear acceptance criteria, Definition of Done, and test plan

### Execution Phase
- **Developers** implement features with focus on testability
- **QA Lead** validates acceptance criteria and coordinates testing
- **UX Designer** reviews implementation for design fidelity
- **Product Manager** validates features meet intended outcomes
- **Project Manager** tracks progress, identifies blockers, escalates risks
- **Key Deliverable**: Completed, tested, and validated features ready for release

### Release Phase
- **Release Manager** owns the deployment process and timeline
- **QA Lead** performs final smoke tests and sign-off
- **Developers** support deployment and troubleshooting if needed
- **Project Manager** manages stakeholder communication
- **Operations** coordinates infrastructure and monitoring
- **Key Deliverable**: Deployed release with post-deployment validation

### Retrospective Phase
- **Project Manager** facilitates the retrospective meeting
- **All roles** contribute feedback on what worked and what could improve
- **Product Manager** captures learning for future prioritization
- **Key Deliverable**: Action items with owners and due dates

## Communication Cadence

### Daily
- **Standup (15 min)**: All team members. Focus: progress, blockers, dependencies
- **Async Updates**: Status in project board and Slack/email as needed

### Weekly
- **PM Sync (30 min)**: Product Manager + Project Manager. Focus: backlog health, blockers, metrics
- **Dev Sync (30 min)**: Developers + QA Lead + Tech Lead. Focus: technical progress, design reviews, quality gates
- **QA Sync (30 min)**: QA Lead + Product Manager + Project Manager. Focus: test status, blockers, release readiness

### Bi-weekly or Milestone-based
- **Stakeholder Update (30 min)**: Project Manager + Product Manager + Key Stakeholders. Focus: progress, risks, decisions needed
- **Design Review (60 min, if applicable)**: UX Designer + Developers + Product Manager. Focus: design decisions, implementation fidelity

### Pre-Release
- **Release Planning (60 min)**: Release Manager + QA Lead + Developers + Project Manager. Focus: deployment checklist, rollback plan, communication strategy
- **Release Readiness (30 min, day before)**: Release Manager + QA Lead + Dev Lead. Final confirmation all gates are passed

### Post-Release
- **Deployment Retrospective (30 min, within 1 week)**: Release Manager + QA Lead + Dev Lead + Project Manager. Focus: what went well, improvements, action items
- **Sprint/Milestone Retrospective (60 min)**: All team members. Focus: team performance, process improvements, celebration of wins

## Collaboration Best Practices

### Clear Ownership
- Each work item should have a clear owner
- Owners are accountable for progress and escalation
- Secondary owners or collaborators should be noted to avoid confusion

### Transparent Handoffs
- Use acceptance criteria to define the boundary between roles (e.g., Dev to QA, QA to Release)
- Document assumptions and dependencies in the backlog item or PR
- Use status checks (GitHub Reviews, project board columns) to indicate handoff readiness

### Feedback Loops
- PR reviews should include feedback from QA (testability) and UX (design fidelity)
- Acceptance criteria validation should involve Product Manager and UX Designer
- Testing discoveries should feed back into design or acceptance criteria refinement

### Escalation Protocol
- **Level 1 (Team-level)**: Standup discussion, resolve within the team
- **Level 2 (Leadership)**: PM escalates to Product Lead, add to risk register
- **Level 3 (Executive)**: Product Lead escalates to Sponsor for business decisions
- **Security/Compliance**: Bypass normal escalation, notify Security Lead immediately

### Documentation
- Decisions made during collaborations should be documented in:
  - Issue descriptions (acceptance criteria changes)
  - PR comments (design or quality rationale)
  - Confluence or shared wiki (architectural or process decisions)
  - Risk register (identified risks or mitigations)

## Common Pain Points & Mitigations

### Pain Point: Unclear Acceptance Criteria
**Mitigation**: Product Manager + UX Designer + QA Lead collaborate to define acceptance criteria that are specific, measurable, and testable before work begins.

### Pain Point: Late Design Changes
**Mitigation**: UX Designer participates in planning and backlog refinement. Design reviews happen early, and design-heavy items are estimated with buffer.

### Pain Point: Quality Surprises at Release
**Mitigation**: QA Lead is involved from planning phase. Testing strategy is defined early. Developers focus on testability. Smoke tests are defined pre-release.

### Pain Point: Deployment Delays
**Mitigation**: Release Manager is involved in planning. Deployment checklist is created early. Release candidates are validated in staging environment 1+ days before production release.

### Pain Point: Stakeholder Misalignment
**Mitigation**: Project Manager facilitates stakeholder communication weekly. Decisions are documented. Risks are raised early and addressed transparently.
