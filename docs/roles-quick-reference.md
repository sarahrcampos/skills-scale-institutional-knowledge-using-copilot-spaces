# Roles Quick Reference

## Purpose
A one-page summary of key roles, their primary responsibilities, and when to engage them. Use this as a quick reference during onboarding, project planning, or when you need to know who to contact.

---

## Role Summary Table

| Role | Primary Responsibilities | When to Engage | Typical Artifacts |
|------|-------------------------|----------------|-------------------|
| **Project Manager (PM)** | Coordinate delivery, manage schedules, risks, and communications | Project kickoff, status updates, risk escalations, cross-team coordination | Project plans, status reports, risk registers |
| **Product Manager (PdM)** | Define product vision, prioritize backlog, measure outcomes | Feature prioritization, roadmap planning, requirements clarification | Product briefs, roadmaps, acceptance criteria |
| **Developer** | Implement features, write tests, participate in design reviews | Technical design, implementation, code reviews, estimation | Code, tests, technical design docs, PR descriptions |
| **QA/Testing Engineer** | Test features, identify defects, verify acceptance criteria | Test planning, bug verification, release readiness | Test plans, test results, defect reports |
| **Scrum Master** | Facilitate agile ceremonies, remove impediments, coach on processes | Sprint planning, daily standups, retrospectives, process improvements | Sprint goals, velocity metrics, burndown charts |
| **UX Designer** | Research users, create designs, validate usability | User research, design reviews, prototyping, accessibility | Wireframes, prototypes, design specs, user research findings |
| **Technical Writer** | Create and maintain documentation for users and developers | Feature documentation, release notes, API docs, onboarding guides | User guides, API docs, release notes, how-tos |
| **Business Analyst (BA)** | Gather requirements, document processes, validate solutions | Requirements gathering, process analysis, stakeholder workshops | Requirement docs, user stories, process flows |
| **Release Manager** | Coordinate releases, manage deployment schedules, ensure readiness | Release planning, code freeze, deployment coordination | Release calendars, deployment runbooks, release notes |
| **Security Lead** | Ensure security in design and implementation, respond to vulnerabilities | Threat modeling, security reviews, incident response | Threat models, security review findings, incident reports |
| **Data Analyst** | Analyze usage data, create dashboards, support experimentation | Metrics definition, analytics implementation, A/B testing | Analytics dashboards, experiment results, usage reports |
| **Stakeholder** | Provide business context, approve deliverables, communicate priorities | Milestone reviews, approvals, priority discussions | Approval decisions, business requirements, constraints |

---

## Common Collaboration Patterns

### Planning & Discovery Phase
- **Product Manager** defines the problem and value
- **Business Analyst** gathers detailed requirements
- **UX Designer** conducts user research
- **Data Analyst** provides baseline metrics
- **Security Lead** performs threat modeling

### Design & Specification Phase
- **UX Designer** creates designs and prototypes
- **Business Analyst** documents workflows and specifications
- **Developers** provide technical feasibility input
- **QA/Testing** reviews acceptance criteria
- **Technical Writer** plans documentation approach

### Development Phase
- **Developers** implement features and tests
- **Scrum Master** facilitates ceremonies and removes blockers
- **UX Designer** reviews implementation fidelity
- **Security Lead** performs code security reviews
- **Project Manager** tracks progress and manages risks

### Testing & Validation Phase
- **QA/Testing** executes test plans and reports bugs
- **Developers** fix defects and verify fixes
- **Business Analyst** validates business requirements
- **Product Manager** confirms acceptance criteria met
- **Data Analyst** validates analytics tracking

### Release & Deployment Phase
- **Release Manager** coordinates deployment activities
- **QA/Testing** provides go/no-go recommendation
- **Project Manager** communicates with stakeholders
- **Technical Writer** publishes documentation
- **Data Analyst** sets up monitoring dashboards

### Post-Release Phase
- **Product Manager** measures outcomes against goals
- **Data Analyst** analyzes usage and impact
- **Support/On-call** handles user issues
- **Scrum Master** facilitates retrospective
- **All roles** contribute lessons learned

---

## Decision Rights Quick Reference

| Decision Type | Primary Decision Maker | Must Consult | Inform |
|---------------|------------------------|--------------|--------|
| **What to build** | Product Manager | Business Analyst, Stakeholders, UX Designer | Project Manager, Developers |
| **When to release** | Release Manager | Project Manager, QA/Testing | Product Manager, Stakeholders |
| **Technical approach** | Developers (tech lead) | Security Lead, Architects | Project Manager, Product Manager |
| **Design direction** | UX Designer | Product Manager, Users | Developers, Business Analyst |
| **Process changes** | Scrum Master | Team members | Project Manager, Stakeholders |
| **Security exceptions** | Security Lead | Risk/Compliance, Stakeholders | Project Manager, Developers |
| **Scope changes** | Product Manager + Project Manager | Stakeholders, Scrum Master | Team members |

---

## Escalation Paths

### For blockers or impediments:
1. **Scrum Master** (team-level blockers)
2. **Project Manager** (cross-team or resource issues)
3. **Product Manager** (priority or scope conflicts)
4. **Stakeholders** (executive decisions)

### For technical issues:
1. **Developers** (implementation questions)
2. **Tech Lead/Architect** (design decisions)
3. **Security Lead** (security concerns)
4. **Engineering Management** (resource or staffing)

### For quality concerns:
1. **QA/Testing** (defects or test failures)
2. **Release Manager** (release readiness)
3. **Project Manager** (timeline impacts)
4. **Product Manager** (scope/quality trade-offs)

---

## Contact Templates

### Need to clarify requirements?
> "Hi [Business Analyst / Product Manager], I'm working on [feature] and need clarification on [specific question]. Could we sync on [aspect]?"

### Need design review?
> "Hi [UX Designer], I've implemented [feature] and would like you to review it for design fidelity. Can you check [link/environment]?"

### Need to report a blocker?
> "Hi [Scrum Master], I'm blocked on [task] due to [reason]. Could you help with [specific need]?"

### Need security review?
> "Hi [Security Lead], we're implementing [feature] that involves [sensitive operation]. Can you review our approach in [doc/PR link]?"

### Need to coordinate a release?
> "Hi [Release Manager], [feature] will be ready for release on [date]. Here's the deployment checklist: [link]"

---

## Role-Specific Communication Preferences

| Role | Preferred for Updates | Preferred for Urgent Issues | Preferred for Collaboration |
|------|----------------------|----------------------------|------------------------------|
| Project Manager | Weekly sync, email, project board | Direct message, phone | Meetings, shared docs |
| Product Manager | Slack/Teams, backlog comments | Direct message | Planning sessions, PRD reviews |
| Developers | PR comments, issue tracker | Direct message | Pair programming, design reviews |
| QA/Testing | Test management tool, Slack | Direct message | Bug triage, test planning |
| Scrum Master | Standup, retrospective | Direct message | Ceremonies, one-on-ones |
| UX Designer | Design reviews, Slack | Direct message | Design crits, prototyping sessions |

---

## Tips for Effective Cross-Role Collaboration

1. **Clarify the role you need**: "I need a Product Manager perspective" vs. "I need a Project Manager perspective"
2. **Respect context-switching**: Schedule meetings in advance when possible
3. **Provide context**: Share links, background, and clear questions
4. **Document decisions**: Don't rely solely on verbal agreements
5. **Use the right channel**: Urgent in chat, detailed in docs, collaborative in meetings
6. **Tag clearly**: Use role tags in issues/PRs for visibility
7. **Follow up**: Close the loop when issues are resolved

---

## Related Documentation
- [OctoAcme Roles and Personas](./octoacme-roles-and-personas.md) - Detailed role definitions with goals and interactions
- [Role Handoff Checklist](./role-handoff-checklist.md) - Checklists for smooth role transitions
- [Project Management Overview](./octoacme-project-management-overview.md) - High-level process and principles
