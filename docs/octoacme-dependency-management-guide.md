# OctoAcme Dependency Management Guide

## Purpose
This guide provides processes and templates for identifying, tracking, and managing cross-team dependencies and integration points to ensure projects stay on schedule and reduce blocking issues.

---

## Dependency Types

### External Dependencies
- **Definition:** Dependencies on teams, vendors, or systems outside the project
- **Examples:** Another team's API release, vendor deliverable, infrastructure change
- **Owner:** Project Manager
- **Risk Level:** Typically higher (less control)

### Internal Dependencies
- **Definition:** Dependencies within the project or between project phases
- **Examples:** Backend completion before frontend integration, data migration before feature launch
- **Owner:** Project Manager + Development Lead
- **Risk Level:** Moderate (more control)

### Technical Dependencies
- **Definition:** Code or system dependencies
- **Examples:** Library upgrades, database migrations, API contract changes
- **Owner:** Development Lead with QA input
- **Risk Level:** Varies

### Resource Dependencies
- **Definition:** Dependencies on specific people or skill availability
- **Examples:** Key developer availability, contractor start date
- **Owner:** Project Manager + Resource/Capacity Planner
- **Risk Level:** High

---

## Dependency Identification

### When to Identify Dependencies
- **Project Initiation:** Identify major external and timeline dependencies
- **Project Planning:** Detail all dependencies and integration points
- **Sprint Planning:** Review dependencies each iteration
- **Ongoing:** Add new dependencies as discovered

### Dependency Identification Checklist

**Internal Dependencies:**
- [ ] Are there work items that must be completed sequentially?
- [ ] Are there integration points between components?
- [ ] Are there data dependencies or migrations?
- [ ] Are there resource constraints?

**External Dependencies:**
- [ ] Do we need deliverables from other teams?
- [ ] Do we depend on vendor products/services?
- [ ] Do we need infrastructure changes?
- [ ] Do we need approvals from external stakeholders?

**Technical Dependencies:**
- [ ] Do we need library/framework upgrades?
- [ ] Are there API contract dependencies?
- [ ] Do we depend on platform features or capabilities?
- [ ] Are there database schema changes needed?

---

## Dependency Register Template

**Project:** [Project name]

**Last Updated:** [Date]

**Owner:** [Project Manager name]

### Dependency Register

| ID | Dependency | Type | Depends On (Team/Component) | Owner | Target Date | Status | Risk Level | Mitigation |
|----|-----------|------|---------------------------|-------|-------------|--------|------------|------------|
| D1 | API integration with Payment Team | External | Payment Services | Alice (PM) | 2024-08-15 | On Track | Medium | Weekly sync with Payment Team PM |
| D2 | Database schema migration | Technical | DevOps team | Bob (Dev Lead) | 2024-08-01 | At Risk | High | Started planning, need DBA approval |
| D3 | John's availability for authentication | Resource | John (Senior Dev) | Alice (PM) | 2024-08-05 | On Track | Low | Backup dev identified, John committed |
| D4 | Customer research completion | External | Marketing/Customer team | Carol (PM) | 2024-07-30 | On Track | Medium | Research firm delivering results on time |
| D5 | Mobile app framework upgrade | Technical | Dev team | Bob (Dev Lead) | 2024-08-10 | At Risk | High | POC in progress, impacts 4 sprints |

---

## Dependency Tracking & Management

### Weekly Dependency Review

**Frequency:** Weekly during project execution

**Attendees:** Project Manager, Development Lead, QA Lead, other relevant owners

**Agenda:**
1. Review status of all dependencies
2. Identify newly at-risk dependencies
3. Escalate blockers
4. Adjust mitigation strategies
5. Plan contingency if needed

**Status Definitions:**
- **On Track:** Dependency expected to be met on schedule
- **At Risk:** Dependency may not be met; mitigation needed
- **Blocked:** Dependency is blocked; escalation required
- **Completed:** Dependency has been satisfied

### Status Update Template

**Dependency ID:** D2

**Dependency:** Database schema migration

**Current Status:** At Risk → On Track

**Previous Status:** At Risk

**Last Updated:** [Date]

**Status Summary:**
[Brief description of current state and recent progress]

**Blockers:**
- [If any, list blockers]

**Upcoming Milestones:**
- Milestone 1: [Description] - [Date]
- Milestone 2: [Description] - [Date]

**Risk Mitigation Actions Taken:**
- [Action 1 taken]
- [Action 2 taken]

**Next Steps:**
- [Next action 1]
- [Next action 2]

**Owner:** [Name]

---

## Dependency Impact Assessment

### Impact Matrix

| Impact Level | Definition | Examples | Mitigation Approach |
|--------------|-----------|----------|--------------------|
| **Critical** | Project cannot proceed without this dependency | API release, infrastructure change | Weekly tracking, executive escalation if at risk |
| **High** | Significant schedule/scope impact if missed | Major team deliverable, vendor product | Bi-weekly tracking, contingency plan |
| **Medium** | Moderate impact, workaround possible | Minor API change, documentation | Tracked in weekly review, mitigation on standby |
| **Low** | Minimal impact, can be deferred | Nice-to-have integration, optional feature | Quarterly review |

### Risk Assessment for At-Risk Dependencies

When a dependency is marked "At Risk," complete this assessment:

**Dependency:** [Name]

**Why At Risk:**
[Explain what changed or what is causing the risk]

**Potential Impact if Missed:**
- **Schedule Impact:** [Days/weeks delay]
- **Scope Impact:** [Features affected]
- **Budget Impact:** [Estimated cost]
- **Quality Impact:** [Risks to quality]

**Probability of Missing Target Date:**
- [ ] High (>70%)
- [ ] Medium (30-70%)
- [ ] Low (<30%)

**Mitigation Options:**
1. **Option A:** [Describe approach and effort]
2. **Option B:** [Describe approach and effort]
3. **Option C:** [Describe approach and effort]

**Recommended Mitigation:**
[Select recommended option and explain why]

**Escalation Needed?**
- [ ] Yes → [To whom and when]
- [ ] No

---

## Cross-Team Coordination

### Dependency Communication

**For External Dependencies:**
- **Sync Frequency:** Bi-weekly or as agreed
- **Communication Channel:** Email, Slack, or video call
- **Attendees:** Project Managers and relevant team leads from both sides
- **Status:** Always include dependency status update
- **Escalation Path:** PM → Sponsor → Executive escalation if needed

**For Internal Dependencies:**
- **Sync Frequency:** Weekly in project standup
- **Format:** Status update in project board or dashboard
- **Owner Update:** Development Lead or Project Manager

### Coordination Template

**Coordination Meeting Notes**

**Date:** [Date]

**Attendees:** [Names and teams]

**Dependencies Discussed:**
1. [Dependency 1 name]
   - Status: [On Track/At Risk/Completed]
   - Latest update: [Brief summary]
   - Issues: [Any blockers or concerns]
   - Next milestone: [Date and description]

2. [Dependency 2 name]
   - ...

**Agreements & Commitments:**
- [Commitment 1 from Team A]
- [Commitment 2 from Team B]

**Issues & Escalations:**
- [Issue 1: escalation needed?]
- [Issue 2: escalation needed?]

**Next Sync:** [Date and time]

---

## Contingency Planning

### When to Create a Contingency Plan

Create contingency plans for:
- **Critical dependencies:** Always
- **High-risk dependencies:** If probability of missing deadline is >30%
- **External dependencies:** When there's less control over timeline
- **Resource dependencies:** When alternatives exist

### Contingency Plan Template

**Primary Plan:** [Original approach]

**If dependency is not met by [date]:**

**Option 1: Delay Project**
- Start alternate work instead
- Delay project by [X days/weeks]
- Impact: [Cascading effects]
- Cost: [Estimated cost]
- Approval required: [Who]

**Option 2: Scope Reduction**
- Remove dependent features/work
- Proceed with reduced scope
- Plan to add later in Phase 2
- Impact: [Business impact]
- Cost: [Estimated cost]
- Approval required: [Who]

**Option 3: Workaround/Alternative Approach**
- Implement temporary solution
- Example: [Description]
- Timeline to implement: [X days]
- Cost: [Estimated cost]
- Approval required: [Who]

**Option 4: Escalation/Additional Resources**
- Escalate to executive sponsor
- Request priority treatment from dependent team
- Provide additional resources if possible
- Timeline: [X days]
- Cost: [Estimated cost]
- Approval required: [Who]

**Recommended Contingency Plan:** [Select option and explain]

**Trigger for Activation:** [Specific condition that would trigger this plan]

**Owner:** [Name responsible for executing if needed]

---

## Dependency Dashboard

### Project-Level Dependency Summary

**Project:** [Name]

**Last Updated:** [Date]

**Total Dependencies:** [Number]

**Status Breakdown:**
- ✓ On Track: [Number]
- ⚠ At Risk: [Number]
- 🔴 Blocked: [Number]
- ✓ Completed: [Number]

**High-Risk Dependencies Requiring Attention:**

| Dependency | Owner | Target Date | Current Status | Risk Level | Next Action |
|-----------|-------|-------------|----------------|------------|-------------|
| [Dep 1] | [Name] | [Date] | At Risk | Critical | [Action] |
| [Dep 2] | [Name] | [Date] | Blocked | High | [Action] |

**Overall Project Risk Due to Dependencies:** [Low/Medium/High]

**Recommended Actions:**
1. [Action 1]
2. [Action 2]

---

## Lessons Learned

### Post-Project Dependency Review

**Questions to Address:**
- Which dependencies caused the most risk or delay?
- Which dependencies did we misjudge in terms of impact or difficulty?
- What early warning signs did we miss?
- What coordination processes worked well?
- What dependency management improvements should we implement?
- How should we adjust our dependency identification process?

**Improvements for Future Projects:**
- [Improvement 1]
- [Improvement 2]
- [Improvement 3]
