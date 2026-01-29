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

## QA/Testing Engineers

### Role Summary
QA/Testing Engineers ensure software meets quality standards and acceptance criteria through manual and automated testing. They identify defects, verify fixes, and help establish quality gates.

### Responsibilities
- Design and execute test plans and test cases
- Identify, document, and track defects
- Collaborate with developers on test automation
- Verify acceptance criteria are met before release
- Contribute to quality metrics and process improvements

### Goals
- Prevent defects from reaching production
- Reduce test execution time through automation
- Ensure comprehensive test coverage

### Typical Communication
- Test results and defect reports
- Participation in sprint planning and refinement
- Sign-off on release readiness

### Interactions
- **Developers**: Collaborate on acceptance criteria, report and verify bug fixes
- **Product Managers**: Clarify requirements and edge cases
- **Project Managers**: Report test status and blockers
- **Release Manager**: Provide go/no-go decision input

---

## Stakeholders

### Role Summary
Stakeholders are individuals or groups with a vested interest in the project outcome. They provide input, constraints, and approvals at key milestones.

### Responsibilities
- Provide business context and requirements
- Review and approve key deliverables
- Participate in demos and milestone reviews
- Communicate organizational constraints or priorities

### Goals
- Ensure project aligns with business objectives
- Manage expectations and resource allocation
- Make informed approval decisions

### Typical Communication
- Monthly status updates and demos
- Milestone reviews and approvals
- Ad-hoc escalation discussions

### Interactions
- **Project Managers**: Receive status updates, provide approvals
- **Product Managers**: Define success criteria and priorities
- **All roles**: Available for clarifications and decision-making

---

## Scrum Master

### Role Summary
Scrum Masters facilitate agile ceremonies, remove impediments, and coach the team on agile practices. They ensure the team follows agreed-upon processes and continuously improves.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Remove blockers and impediments to team progress
- Shield the team from external interruptions
- Coach team members on agile principles and practices
- Track and visualize team metrics (velocity, burndown)

### Goals
- Maximize team productivity and flow
- Foster continuous improvement culture
- Ensure sustainable pace and work-life balance

### Typical Communication
- Daily standups and sprint ceremonies
- One-on-ones with team members
- Metrics dashboards and burndown charts

### Interactions
- **Developers**: Remove impediments, facilitate collaboration
- **Product Managers**: Ensure backlog refinement and priority clarity
- **Project Managers**: Coordinate on cross-team dependencies
- **All team members**: Coach on process and facilitate retrospectives

---

## UX Designer

### Role Summary
UX Designers research user needs, create interaction designs, and validate usability. They ensure products are intuitive, accessible, and delightful to use.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and high-fidelity designs
- Define user flows and interaction patterns
- Establish and maintain design systems
- Validate designs with users and stakeholders

### Goals
- Deliver user-centered, accessible designs
- Reduce user friction and support costs
- Maintain design consistency across products

### Typical Communication
- Design critiques and reviews
- User research findings and personas
- Annotated wireframes and prototypes

### Interactions
- **Product Managers**: Align on user problems and success metrics
- **Developers**: Hand off designs, clarify implementation details
- **QA/Testing**: Validate UI/UX against acceptance criteria
- **Business Analyst**: Understand workflows and user context

---

## Technical Writer

### Role Summary
Technical Writers create and maintain documentation for users, developers, and other audiences. They ensure information is accurate, clear, and accessible.

### Responsibilities
- Write user guides, API docs, and release notes
- Collaborate with developers to document features
- Maintain documentation consistency and style
- Organize and publish documentation on appropriate platforms
- Update docs based on user feedback

### Goals
- Enable users and developers to self-serve
- Reduce support burden through clear documentation
- Ensure documentation stays current with product changes

### Typical Communication
- Documentation reviews and PRs
- Release notes summaries
- Content architecture proposals

### Interactions
- **Developers**: Gather technical details and review accuracy
- **Product Managers**: Understand feature intent and user value
- **UX Designer**: Align on terminology and user flows
- **Release Manager**: Coordinate documentation releases

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business needs and technical solutions. They gather requirements, document processes, and ensure solutions deliver measurable business value.

### Responsibilities
- Gather and document business requirements
- Analyze current workflows and identify improvement opportunities
- Create detailed functional specifications
- Facilitate requirements workshops with stakeholders
- Validate that delivered solutions meet business needs

### Goals
- Ensure clear, complete requirements
- Reduce rework from misunderstood requirements
- Maximize ROI of development efforts

### Typical Communication
- Requirements documents and user stories
- Process flows and data models
- Stakeholder interviews and workshops

### Interactions
- **Product Managers**: Refine product vision into detailed requirements
- **Developers**: Clarify specifications and acceptance criteria
- **QA/Testing**: Define test scenarios based on business rules
- **Stakeholders**: Validate requirements and gather feedback

---

## Release Manager

### Role Summary
Release Managers coordinate the release process, ensuring code moves smoothly from development to production. They manage release schedules, communicate changes, and coordinate deployment activities.

### Responsibilities
- Plan and coordinate release schedules
- Manage release branches and version control
- Coordinate deployment activities with operations/SRE
- Communicate release contents and timing to stakeholders
- Ensure rollback procedures are ready and tested

### Goals
- Deliver reliable, predictable releases
- Minimize deployment-related incidents
- Maintain clear release documentation

### Typical Communication
- Release calendars and schedules
- Deployment runbooks and checklists
- Release notes and change logs

### Interactions
- **Project Managers**: Coordinate release timing and scope
- **Developers**: Manage code freeze and release branches
- **QA/Testing**: Verify release readiness
- **Technical Writer**: Coordinate documentation updates
- **On-call/Support**: Brief on changes and known issues

---

## Security Lead

### Role Summary
Security Leads ensure products are designed, built, and deployed securely. They perform threat modeling, security reviews, and help teams adopt secure development practices.

### Responsibilities
- Conduct threat modeling and security design reviews
- Perform or coordinate security testing and code reviews
- Define security requirements and guidelines
- Respond to security incidents and vulnerabilities
- Train teams on secure coding practices

### Goals
- Prevent security vulnerabilities from reaching production
- Ensure compliance with security standards
- Foster a security-aware culture

### Typical Communication
- Security review findings and recommendations
- Threat models and risk assessments
- Security incident reports

### Interactions
- **Developers**: Review code for security issues, provide guidance
- **Product Managers**: Define security requirements early
- **Release Manager**: Approve security-critical releases
- **Business Analyst**: Ensure security requirements are captured

---

## Data Analyst

### Role Summary
Data Analysts help teams make data-informed decisions by analyzing user behavior, measuring outcomes, and creating dashboards. They support product development with insights and metrics.

### Responsibilities
- Design and implement analytics tracking
- Analyze product usage and user behavior
- Create dashboards and reports for stakeholders
- Support A/B testing and experimentation
- Provide insights to inform product decisions

### Goals
- Enable data-driven decision making
- Measure and communicate product impact
- Identify opportunities for improvement

### Typical Communication
- Analytics reports and dashboards
- Experiment results and recommendations
- Data quality and tracking updates

### Interactions
- **Product Managers**: Define success metrics and analytics requirements
- **Developers**: Implement tracking and instrumentation
- **UX Designer**: Provide behavioral insights from user data
- **Stakeholders**: Share performance metrics and trends

---

## Role Handoffs & Interactions

Successful project delivery depends on smooth handoffs between roles. Below are common handoff patterns:

### Requirements Handoff: Product Manager → Business Analyst → Developers
1. **PdM** defines the problem, user value, and success metrics
2. **BA** translates this into detailed requirements, acceptance criteria, and process flows
3. **Developers** implement based on clear specifications and edge cases

**Key artifacts**: Product brief, user stories, functional specs, acceptance criteria

### Design Handoff: UX Designer → Developers
1. **UX Designer** creates validated designs, prototypes, and specifications
2. **Developers** implement UI/UX according to designs and design system
3. **UX Designer** reviews implementation for design fidelity

**Key artifacts**: Design files, prototypes, design specs, asset library

### Release Handoff: Project Manager → Release Manager → On-call/Support
1. **PM** confirms scope, timeline, and stakeholder communication plan
2. **Release Manager** coordinates deployment, monitors rollout
3. **On-call/Support** receives handoff with release notes, known issues, rollback plan

**Key artifacts**: Release notes, deployment checklist, runbook, rollback procedure

### Testing Handoff: Developers → QA/Testing → Release Manager
1. **Developers** complete implementation and unit tests
2. **QA/Testing** executes test plan, reports defects, validates fixes
3. **Release Manager** receives go/no-go decision based on quality gates

**Key artifacts**: Test plan, test results, defect log, quality metrics

---

## RACI Matrix Example: Release to Production

This example shows typical roles for a production release activity using RACI notation:
- **R**esponsible: Does the work
- **A**ccountable: Owns the outcome, final approver
- **C**onsulted: Provides input
- **I**nformed: Kept up to date

| Activity | PM | PdM | Dev | QA/Testing | Release Mgr | Security Lead | Support |
|----------|----|----|-----|------------|-------------|---------------|---------|
| Release planning | A | C | C | C | R | I | I |
| Code freeze decision | I | C | I | C | A | I | I |
| Security review | I | I | C | I | C | A | I |
| Final testing sign-off | C | I | I | A | C | I | I |
| Deployment execution | I | I | I | I | R/A | I | I |
| Release communication | R | C | I | I | C | I | I |
| Production validation | C | I | R | R | A | I | I |
| Support handoff | C | I | I | I | R | I | A |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

