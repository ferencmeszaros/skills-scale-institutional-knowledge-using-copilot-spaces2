# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Specialized Roles

### Quality Assurance Lead

#### Role Summary
The Quality Assurance Lead defines and enforces quality standards across the project lifecycle. They oversee testing strategies, conduct release readiness assessments, and ensure quality gates are met before deployment.

#### Responsibilities
- Define quality standards and acceptance criteria for testing
- Oversee testing strategies and test coverage planning
- Conduct release readiness assessments
- Manage quality metrics and reporting
- Identify and track quality risks
- Approve quality gates and sign-off on releases

#### Decision Authority
- Approves quality gates for go/no-go decisions
- Determines testing scope and coverage requirements
- Authorizes release readiness based on quality metrics
- Recommends blocking issues or delays based on quality concerns

#### Key Interactions
- **Works with:** Developers on test planning and quality reviews
- **Reports to:** Project Manager on quality metrics and release readiness
- **Collaborates with:** Risk Management Specialist on quality-related risks
- **Advises:** Stakeholder Communications Manager on quality concerns

#### Goals
- Reduce defects in production
- Increase customer confidence in product quality
- Enable faster, safer releases
- Establish quality as a shared team responsibility

---

### Stakeholder Communications Manager

#### Role Summary
The Stakeholder Communications Manager ensures clear, timely communication with all project stakeholders. They manage communication plans, coordinate status updates, and handle escalations to keep stakeholders informed and aligned.

#### Responsibilities
- Develop and maintain project communication plans
- Manage stakeholder update schedules and channels
- Coordinate and approve status reports and communications
- Handle stakeholder escalations and concerns
- Track communication effectiveness and stakeholder feedback
- Ensure alignment between Project Manager and leadership communications

#### Decision Authority
- Determines communication frequency and channels
- Approves status reports and stakeholder communications
- Decides on escalation timing and format
- Recommends communication strategy changes based on stakeholder feedback

#### Key Interactions
- **Works with:** Project Manager on status and project updates
- **Coordinates with:** Risk Management Specialist on issue and risk communication
- **Collaborates with:** Quality Assurance Lead on quality-related communications
- **Advises:** Product Manager on stakeholder sentiment and feedback

#### Goals
- Maintain stakeholder confidence and alignment
- Reduce misunderstandings and surprises
- Enable early identification of stakeholder concerns
- Support transparent, data-driven decision-making

---

### Risk Management Specialist

#### Role Summary
The Risk Management Specialist proactively identifies, assesses, and manages project risks. They develop mitigation strategies, monitor the risk register, and ensure the team is prepared for potential issues.

#### Responsibilities
- Identify and assess potential project risks
- Develop and maintain the risk register
- Create mitigation strategies for identified risks
- Monitor risk indicators and trigger conditions
- Escalate critical risks to leadership
- Recommend contingency actions and response plans
- Track mitigation effectiveness

#### Decision Authority
- Escalates critical risks based on impact and probability assessment
- Recommends contingency action triggers
- Approves risk mitigation strategy changes
- Determines risk communication priority and timing

#### Key Interactions
- **Partners with:** Project Manager on risk planning and response
- **Coordinates with:** Technical Architecture Owner on technical risks
- **Works with:** Quality Assurance Lead on quality-related risks
- **Reports to:** Leadership on critical risks
- **Advises:** Stakeholder Communications Manager on risk communication

#### Goals
- Minimize project surprises and disruptions
- Enable proactive risk response
- Increase project predictability
- Build organizational risk management capability

---

### Technical Architecture Owner

#### Role Summary
The Technical Architecture Owner ensures technical decisions align with long-term architectural vision and organizational standards. They guide technical direction, review design decisions, and identify technical dependencies and risks.

#### Responsibilities
- Define and communicate technical architecture vision
- Review and approve technical design decisions
- Ensure architectural alignment across components
- Identify technical dependencies and constraints
- Assess technical risks and feasibility
- Guide technology choices and standards
- Support scaling of technical solutions

#### Decision Authority
- Approves technical approach for major components
- Identifies and escalates architectural blockers
- Determines technical dependency priorities
- Recommends technical risk mitigation strategies
- Advises on technology choices and trade-offs

#### Key Interactions
- **Advises:** Developers on technical decisions and design
- **Works with:** Project Manager on technical risk and timeline impacts
- **Coordinates with:** Risk Management Specialist on technical risks
- **Collaborates with:** Quality Assurance Lead on technical quality concerns
- **Reports to:** Project Manager on architectural risks and dependencies

#### Goals
- Enable scalable, maintainable technical solutions
- Reduce technical debt and rework
- Improve architecture consistency and quality
- Support long-term technical sustainability

---

## Role Interaction Matrix

| Role | Interacts With | Type | Key Touchpoints |
|------|----------------|------|------------------|
| Developers | Project Manager | Report/Guidance | Sprint planning, status, blockers |
| Developers | Quality Assurance Lead | Collaborative | Test planning, code review, quality gates |
| Developers | Technical Architecture Owner | Advisory | Design reviews, technical decisions |
| Project Manager | All Roles | Coordination | Planning, status, risk, communication |
| Product Manager | Project Manager | Alignment | Priorities, roadmap, scope |
| Quality Assurance Lead | Developers | Collaborative | Testing, quality standards |
| Quality Assurance Lead | Project Manager | Report/Escalation | Quality metrics, release readiness |
| Stakeholder Communications Manager | Project Manager | Collaborative | Status, communications |
| Risk Management Specialist | Project Manager | Advisory | Risk planning, escalation |
| Technical Architecture Owner | Developers | Advisory | Design, technical decisions |
| Technical Architecture Owner | Project Manager | Report/Escalation | Technical risks, dependencies |

---

## How These Personas Are Used

1. **For Project Teams:** Use these persona definitions to clarify roles, responsibilities, and decision authority within your team
2. **For Copilot Spaces:** Each persona can be used as a persona prompt to shape role-specific guidance and recommendations
3. **For Onboarding:** Reference these definitions when onboarding new team members to help them understand their role and how to interact with other roles
4. **For Exercises:** Frame scenarios and sample interactions using these persona definitions

---

## Key Principles for Role Success

- **Clear Decision Authority:** Each role has defined decision-making authority to enable autonomy and speed
- **Collaborative Interactions:** Roles work together, not in silos, to achieve shared goals
- **Complementary Expertise:** Different roles bring specialized expertise that strengthens project outcomes
- **Scalability:** Role definitions grow with the organization without losing clarity
- **Accountability:** Clear roles enable clear accountability for outcomes
