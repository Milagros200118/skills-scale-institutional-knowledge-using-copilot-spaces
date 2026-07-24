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
- Collaborate with QA Lead on test coverage and quality gates

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed
- Weekly sync with QA Lead on quality metrics

#### Interactions with Other Roles
- **With QA Lead**: Ensures test coverage, participates in quality reviews
- **With Product Manager**: Clarifies acceptance criteria, proposes technical solutions
- **With Project Manager**: Updates status, escalates blockers
- **With Technical Documentation Specialist**: Provides technical details for documentation

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Work with Stakeholder Communication Manager on messaging

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs
- Monthly review of product metrics and user feedback

#### Interactions with Other Roles
- **With Project Manager**: Aligns on priorities, timelines, and resource constraints
- **With Developers**: Clarifies requirements, validates technical feasibility
- **With QA Lead**: Defines quality expectations and acceptance criteria
- **With Stakeholder Communication Manager**: Coordinates feature announcements and customer updates
- **With Technical Documentation Specialist**: Ensures user-facing documentation aligns with feature launches

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
- Work with Resource/Capacity Planner to optimize team allocation
- Escalate blockers and manage issue resolution

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation
- Daily standup facilitation

#### Interactions with Other Roles
- **With Product Manager**: Reviews priorities, timelines, and resource needs
- **With QA Lead**: Tracks quality status and release readiness
- **With Resource/Capacity Planner**: Plans resource allocation and identifies bottlenecks
- **With Stakeholder Communication Manager**: Coordinates stakeholder updates
- **With All Technical Roles**: Facilitates communication and escalations

---

## Supporting Roles (Expanded)

### Quality Assurance Lead

#### Role Summary
The QA Lead owns quality standards, testing strategy, and acceptance criteria validation for project releases. They ensure that features meet quality gates before deployment and work proactively to prevent defects.

#### Responsibilities
- Define quality standards and testing strategy for each project phase
- Create and maintain test plans aligned with acceptance criteria
- Establish quality metrics and gates for go/no-go release decisions
- Coordinate testing activities across development team
- Report quality risks and blockers to Project Manager
- Collaborate with developers on test automation and coverage
- Validate features against acceptance criteria before release
- Identify and document defects with clear reproduction steps
- Support post-release quality monitoring and incident response

#### Goals
- Ensure features meet or exceed quality standards
- Reduce production defects and regressions
- Enable confident, low-risk releases
- Build quality into the development process (shift-left)

#### Typical Communication
- Weekly quality metrics review with Project Manager
- Daily standup participation (quality status)
- Quality review meetings at end of sprint/milestone
- Release readiness checkpoints before deployment

#### Interactions with Other Roles
- **With Developers**: Collaborates on test coverage, reviews test strategies, participates in code reviews for testability
- **With Product Manager**: Clarifies acceptance criteria, validates feature completeness
- **With Project Manager**: Reports on quality status, escalates quality risks, provides release readiness assessment
- **With Technical Documentation Specialist**: Validates documentation examples against actual behavior

#### Key Competencies
- Test planning and execution (manual and automation)
- Defect lifecycle management
- Acceptance criteria interpretation
- Risk-based testing approach
- Communication with technical and non-technical stakeholders

---

### Technical Documentation Specialist

#### Role Summary
The Technical Documentation Specialist creates and maintains user-facing and technical documentation that aligns with product releases. They ensure documentation is accurate, clear, and accessible to the target audience.

#### Responsibilities
- Create and update user guides, API documentation, and technical references
- Ensure documentation accuracy by collaborating with development teams
- Maintain documentation review and approval workflow
- Coordinate documentation release schedules with product releases
- Monitor documentation usage and gather feedback for improvements
- Create examples and tutorials that demonstrate feature usage
- Organize and structure documentation for discoverability
- Support localization efforts if needed

#### Goals
- Enable users to effectively use and understand features
- Reduce support tickets related to feature usage
- Maintain single source of truth for technical information
- Accelerate user onboarding and adoption

#### Typical Communication
- Weekly sync with development teams on feature changes
- Coordination with Product Manager on messaging and timing
- Documentation review meetings before releases
- Feedback collection from support and user channels

#### Interactions with Other Roles
- **With Developers**: Gathers technical details, validates documentation accuracy, clarifies implementation details
- **With Product Manager**: Aligns on feature messaging, user-facing language, and release timing
- **With QA Lead**: Validates documentation examples and user workflows
- **With Stakeholder Communication Manager**: Coordinates user-facing announcements with documentation releases

#### Key Competencies
- Technical writing and communication
- Ability to learn technical concepts quickly
- Documentation tools and platforms (Markdown, wikis, help systems)
- User empathy and ability to write for different audiences

---

### Stakeholder Communication Manager

#### Role Summary
The Stakeholder Communication Manager coordinates external and internal stakeholder communication, manages status updates, tracks stakeholder feedback, and ensures alignment across project teams and leadership.

#### Responsibilities
- Maintain stakeholder registry and communication preferences
- Prepare and deliver regular status reports to stakeholders
- Track and escalate stakeholder concerns and feedback
- Coordinate release announcements and feature messaging
- Facilitate stakeholder meetings and demos
- Support Project Manager with stakeholder engagement
- Gather and communicate feedback from customer-facing teams (support, sales)
- Document stakeholder decisions and action items

#### Goals
- Maintain stakeholder alignment and confidence
- Identify and surface emerging concerns early
- Ensure consistent messaging across all communications
- Reduce miscommunication and surprises

#### Typical Communication
- Weekly stakeholder status reports
- Bi-weekly stakeholder review meetings
- Ad-hoc communication on critical issues
- Post-release stakeholder updates

#### Interactions with Other Roles
- **With Project Manager**: Reports stakeholder sentiment, escalates concerns, coordinates status communications
- **With Product Manager**: Communicates feature updates, gathers customer feedback, aligns on messaging
- **With Developers and QA Lead**: Gathers technical status for stakeholder reports
- **With Technical Documentation Specialist**: Coordinates documentation availability with release announcements

#### Key Competencies
- Stakeholder management and communication
- Executive presence and communication
- Feedback synthesis and analysis
- Project status and metrics interpretation
- Crisis communication (for incidents/delays)

---

### Resource/Capacity Planner

#### Role Summary
The Resource/Capacity Planner monitors team capacity and resource allocation across projects, identifies staffing gaps and bottlenecks, supports forecasting, and optimizes resource utilization.

#### Responsibilities
- Track team member availability and allocation across projects
- Identify resource bottlenecks and capacity constraints
- Forecast resource needs based on project roadmaps
- Support Project Manager with capacity planning and risk mitigation
- Optimize team utilization and balance workload
- Report on capacity utilization metrics
- Identify cross-training and skill gap opportunities
- Coordinate with hiring/staffing partners on resource requests

#### Goals
- Optimize resource utilization across projects
- Prevent resource bottlenecks and schedule slips
- Enable data-driven capacity forecasting
- Support team growth and skill development

#### Typical Communication
- Weekly capacity reviews with Project Manager
- Monthly capacity planning reports
- Quarterly forecasting discussions with leadership
- Ad-hoc escalations for resource conflicts

#### Interactions with Other Roles
- **With Project Manager**: Provides capacity insights, identifies resource constraints, supports mitigation planning
- **With Development Lead and QA Lead**: Understands team capacity, skill sets, and availability
- **With Executive Stakeholders**: Reports on resource allocation and forecasts

#### Key Competencies
- Resource planning and forecasting
- Capacity analysis and metrics
- Workload balancing
- Spreadsheet and planning tool proficiency
- Communication with technical and business stakeholders

---

## Role Interaction Matrix

| Role | Primary Collaborators | Interaction Frequency | Key Touchpoints |
|------|----------------------|----------------------|------------------|
| **Project Manager** | Product Manager, Developers, QA Lead, Stakeholder Comm Mgr, Resource Planner | Daily | Standups, status updates, escalations, weekly syncs |
| **Product Manager** | Project Manager, Developers, QA Lead, Stakeholder Comm Mgr | 2-3x/week | Planning, prioritization, acceptance criteria, roadmap reviews |
| **Developers** | QA Lead, Product Manager, Project Manager, Tech Doc Specialist | Daily | Code reviews, standups, quality discussions, requirements clarification |
| **QA Lead** | Developers, Product Manager, Project Manager | Daily | Test planning, quality reviews, acceptance criteria validation |
| **Tech Doc Specialist** | Developers, Product Manager, QA Lead, Stakeholder Comm Mgr | 2-3x/week | Feature documentation, release coordination, messaging alignment |
| **Stakeholder Comm Mgr** | Project Manager, Product Manager, Tech Doc Specialist, Executive Sponsors | Weekly | Status reporting, messaging, feedback collection |
| **Resource/Capacity Planner** | Project Manager, Development Leads, QA Lead, Executives | Weekly | Capacity reviews, forecasting, resource allocation |

---

## How These Personas Are Used in the Exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the interaction matrix when designing cross-functional workflows and decision-making processes.
- Use the responsibilities and goals to clarify ownership and accountability in project documentation.
