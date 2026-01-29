# Role Handoff Checklist

## Purpose
This checklist helps teams ensure smooth transitions and handoffs between roles during project lifecycles. Use it to verify that all necessary information, artifacts, and agreements are in place before passing work to the next phase or team member.

## How to Use This Checklist
1. **Before a handoff**: Review the relevant section below based on your handoff type
2. **During handoff**: Walk through items with both parties present when possible
3. **Document completion**: Check off items as completed, note any exceptions
4. **Copy as needed**: Copy this checklist into issues, PRs, or project docs as appropriate
5. **Customize**: Add project-specific items as needed while keeping the core structure

---

## General Handoff Checklist Template

### Pre-Handoff
- [ ] **Handoff meeting scheduled** with all necessary participants
- [ ] **Context document** prepared and shared (background, goals, constraints)
- [ ] **Key stakeholders** identified and informed of handoff
- [ ] **Timeline and deadlines** communicated clearly

### Artifacts & Documentation
- [ ] **All required artifacts** are complete and accessible
- [ ] **Documentation** is up-to-date and linked in handoff notes
- [ ] **Known issues or risks** documented with mitigation plans
- [ ] **Dependencies** identified and communicated
- [ ] **Access and permissions** granted to recipient

### Communication & Sign-off
- [ ] **Questions answered** and ambiguities resolved
- [ ] **Success criteria** agreed upon and documented
- [ ] **Follow-up contact** established (who to ask if questions arise)
- [ ] **Handoff acknowledged** by recipient in writing

---

## Specific Handoff Scenarios

### Requirements Handoff (Product Manager → Business Analyst → Developers)

#### Prerequisites
- [ ] Problem statement and user value clearly defined
- [ ] Success metrics identified
- [ ] Stakeholder approvals obtained

#### Artifacts
- [ ] Product brief or PRD (Product Requirements Document)
- [ ] User stories with acceptance criteria
- [ ] Wireframes or mockups (if applicable)
- [ ] Technical constraints or dependencies documented

#### Communication
- [ ] Requirements review meeting held
- [ ] Edge cases and error scenarios discussed
- [ ] Open questions documented in backlog
- [ ] Developers confirm understanding of scope

#### Sign-off
- [ ] Business Analyst confirms requirements completeness
- [ ] Development team accepts work into sprint/backlog
- [ ] Estimation completed and agreed upon

---

### Design Handoff (UX Designer → Developers)

#### Prerequisites
- [ ] Designs validated with users or stakeholders
- [ ] Design review completed with team
- [ ] Accessibility requirements defined

#### Artifacts
- [ ] High-fidelity designs or prototypes
- [ ] Design specs (spacing, colors, typography)
- [ ] Interactive states documented (hover, active, disabled)
- [ ] Responsive behavior defined (mobile, tablet, desktop)
- [ ] Asset files exported and accessible
- [ ] Design system components referenced

#### Communication
- [ ] Design walkthrough session conducted
- [ ] Edge cases and error states clarified
- [ ] Animation or transition specs explained
- [ ] Implementation questions resolved

#### Sign-off
- [ ] Developers confirm design is implementable
- [ ] Review process agreed upon (e.g., design QA)
- [ ] UX Designer available for clarifications during implementation

---

### Development Handoff (Developers → QA/Testing)

#### Prerequisites
- [ ] Code complete and merged to test branch
- [ ] Unit tests passing
- [ ] Build/deployment to test environment successful

#### Artifacts
- [ ] Test environment URL or access instructions
- [ ] Test data or setup scripts
- [ ] Feature documentation or implementation notes
- [ ] Known limitations or incomplete areas flagged

#### Communication
- [ ] Demo of implemented feature conducted
- [ ] Differences from original spec explained and approved
- [ ] Test approach discussed
- [ ] Timeline for test completion agreed

#### Sign-off
- [ ] QA confirms test environment is ready
- [ ] Test plan reviewed and approved
- [ ] Developers commit to fix bugs within agreed SLA

---

### Release Handoff (QA → Release Manager → Production)

#### Prerequisites
- [ ] All test cases executed and passing (or exceptions approved)
- [ ] Critical and high-priority bugs resolved
- [ ] Regression testing completed
- [ ] Performance testing passed (if applicable)

#### Artifacts
- [ ] Test summary report with pass/fail metrics
- [ ] Release notes drafted and reviewed
- [ ] Deployment runbook or checklist
- [ ] Rollback procedure documented and tested
- [ ] Configuration changes documented
- [ ] Database migration scripts (if applicable)

#### Communication
- [ ] Go/no-go decision meeting held
- [ ] Stakeholders informed of release timing
- [ ] On-call team briefed on changes
- [ ] Customer-facing teams notified (support, success, sales)

#### Sign-off
- [ ] QA provides final testing sign-off
- [ ] Release Manager approves deployment
- [ ] Production deployment completed successfully
- [ ] Post-deployment validation passed

---

### Support Handoff (Release Manager → On-call/Support)

#### Prerequisites
- [ ] Release deployed successfully to production
- [ ] Post-deployment smoke tests passed
- [ ] Monitoring and alerts configured

#### Artifacts
- [ ] Release notes with user-facing changes
- [ ] Known issues and workarounds documented
- [ ] Troubleshooting guide or runbook
- [ ] Escalation path defined
- [ ] Relevant logs and monitoring dashboards linked

#### Communication
- [ ] Support team briefed on new features and changes
- [ ] Expected customer impact discussed
- [ ] FAQs or talking points provided
- [ ] On-call rotation updated if needed

#### Sign-off
- [ ] Support team acknowledges readiness
- [ ] First-tier support questions answered
- [ ] Development team committed to fix critical issues

---

## Copyable Checklist Template for Issues/PRs

```markdown
## Handoff Checklist

### Pre-Handoff
- [ ] Handoff meeting scheduled
- [ ] Context document prepared
- [ ] Stakeholders informed
- [ ] Timeline communicated

### Artifacts
- [ ] Required artifacts complete
- [ ] Documentation up-to-date
- [ ] Known issues documented
- [ ] Access granted

### Communication
- [ ] Questions answered
- [ ] Success criteria agreed
- [ ] Follow-up contact established

### Sign-off
- [ ] Handoff acknowledged by recipient
```

---

## Best Practices

- **Be proactive**: Schedule handoffs in advance, don't wait until the last minute
- **Document everything**: Verbal agreements are easily forgotten
- **Include context**: Explain *why* decisions were made, not just *what*
- **Test the handoff**: Can the recipient actually access and understand everything?
- **Make it two-way**: Handoff is complete when recipient confirms understanding
- **Continuous improvement**: Update this checklist based on lessons learned

---

## Related Documentation
- [OctoAcme Roles and Personas](./octoacme-roles-and-personas.md) - Detailed role definitions
- [Roles Quick Reference](./roles-quick-reference.md) - Summary of responsibilities
- [Project Management Overview](./octoacme-project-management-overview.md) - Process overview
