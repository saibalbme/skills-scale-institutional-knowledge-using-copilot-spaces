# OctoAcme RACI Matrix Template

## Purpose
A RACI matrix clarifies roles and responsibilities for key activities and decisions. Use this template to avoid confusion about who owns what and to ensure decisions are made efficiently.

## RACI Definitions

| Acronym | Definition | Responsibility |
|---------|-----------|-----------------|
| **R** | **Responsible** | Does the work; executes the task or activity |
| **A** | **Accountable** | Owner; approves the work and is ultimately answerable |
| **C** | **Consulted** | Provides input; asks for their opinions before decisions |
| **I** | **Informed** | Notified; receives updates after decisions or work is complete |

### Key Principles
- Every activity should have exactly **one Accountable** person
- There may be multiple **Responsible** or **Consulted** parties
- **Accountable** person may also be **Responsible**
- If nobody is Accountable, the activity will stall
- Too many Consulted parties slows decision-making

---

## OctoAcme RACI Template

### Project-Level Activities

| Activity | Product Manager | Project Manager | Technical Lead | Developers | QA/Testing Lead | DevOps/Release Engineer | Business Analyst | Scrum Master | Security/Compliance |
|----------|-----------------|-----------------|----------------|------------|-----------------|-------------------------|------------------|--------------|---------------------|
| **Define project scope & success metrics** | A/R | C | C | I | I | I | C | I | C |
| **Create project plan & timeline** | C | A/R | C | C | I | I | I | C | C |
| **Identify risks & dependencies** | C | A/R | C | I | C | C | C | C | C |
| **Establish Definition of Done** | C | A/R | C | C | C | I | I | C | I |
| **Plan security & compliance review** | I | C | C | I | C | I | I | I | A/R |
| **Kickoff meeting facilitation** | C | A/R | C | C | I | I | I | C | I |

### Requirements & Planning Activities

| Activity | Product Manager | Project Manager | Technical Lead | Developers | QA/Testing Lead | DevOps/Release Engineer | Business Analyst | Scrum Master | Security/Compliance |
|----------|-----------------|-----------------|----------------|------------|-----------------|-------------------------|------------------|--------------|---------------------|
| **Gather & document requirements** | C | I | I | I | C | I | A/R | I | C |
| **Define acceptance criteria** | A/R | C | C | C | C | I | C | I | I |
| **Assess technical feasibility** | C | C | A/R | C | C | I | I | I | C |
| **Assess testability** | C | I | C | C | A/R | I | C | I | I |
| **Prioritize backlog** | A/R | C | C | I | C | I | C | I | C |
| **Sprint planning** | C | C | C | A/R | I | I | I | A/R | I |
| **Estimate scope & effort** | C | C | C | A/R | C | I | I | C | I |

### Design & Architecture Activities

| Activity | Product Manager | Project Manager | Technical Lead | Developers | QA/Testing Lead | DevOps/Release Engineer | Business Analyst | Scrum Master | Security/Compliance |
|----------|-----------------|-----------------|----------------|------------|-----------------|-------------------------|------------------|--------------|---------------------|
| **Create technical design** | I | I | A/R | R | C | C | I | I | C |
| **Conduct design review** | I | C | A/R | R | C | C | I | I | A/C |
| **Assess security implications** | I | I | C | I | I | I | I | I | A/R |
| **Plan deployment architecture** | I | C | A/R | I | I | R | I | I | C |
| **Document technical decisions** | I | I | A/R | I | I | I | I | I | I |

### Execution Activities

| Activity | Product Manager | Project Manager | Technical Lead | Developers | QA/Testing Lead | DevOps/Release Engineer | Business Analyst | Scrum Master | Security/Compliance |
|----------|-----------------|-----------------|----------------|------------|-----------------|-------------------------|------------------|--------------|---------------------|
| **Code implementation** | I | I | C | A/R | I | I | I | I | I |
| **Code review** | I | I | A/R | R | I | I | I | I | C |
| **Unit testing** | I | I | I | A/R | C | I | I | I | I |
| **Security code review** | I | I | C | C | I | I | I | I | A/R |
| **Identify & report blockers** | I | C | I | A/R | I | I | I | A/R | I |
| **Daily standup facilitation** | I | I | I | R | R | I | I | A/R | I |
| **Track sprint progress** | I | A/R | I | R | I | I | I | C | I |

### Testing & Quality Activities

| Activity | Product Manager | Project Manager | Technical Lead | Developers | QA/Testing Lead | DevOps/Release Engineer | Business Analyst | Scrum Master | Security/Compliance |
|----------|-----------------|-----------------|----------------|------------|-----------------|-------------------------|------------------|--------------|---------------------|
| **Create test plan** | C | I | I | I | A/R | I | C | I | I |
| **Develop test cases** | I | I | I | C | A/R | I | C | I | I |
| **Execute manual testing** | I | I | I | I | A/R | I | I | I | I |
| **Develop test automation** | I | I | C | R | A/R | I | I | I | I |
| **Bug triage & prioritization** | C | C | I | C | A/R | I | I | I | I |
| **Acceptance testing** | C | C | I | I | A/R | I | C | I | I |
| **Release readiness assessment** | I | A/R | C | C | C | I | I | I | C |

### Release & Deployment Activities

| Activity | Product Manager | Project Manager | Technical Lead | Developers | QA/Testing Lead | DevOps/Release Engineer | Business Analyst | Scrum Master | Security/Compliance |
|----------|-----------------|-----------------|----------------|------------|-----------------|-------------------------|------------------|--------------|---------------------|
| **Create release notes** | A/R | R | C | I | I | R | I | I | I |
| **Plan deployment window** | I | A/R | C | I | C | R | I | I | C |
| **Deploy to staging** | I | I | I | I | I | A/R | I | I | I |
| **Run smoke tests** | I | I | I | I | A/R | R | I | I | I |
| **Security deployment review** | I | I | C | I | I | C | I | I | A/R |
| **Deploy to production** | I | I | I | I | I | A/R | I | I | I |
| **Post-deployment verification** | I | A/R | I | I | A/R | R | I | I | I |
| **Announce release** | A/R | R | I | I | I | I | I | I | I |
| **Monitor production issues** | I | C | C | C | I | A/R | I | I | C |

### Retrospective & Continuous Improvement

| Activity | Product Manager | Project Manager | Technical Lead | Developers | QA/Testing Lead | DevOps/Release Engineer | Business Analyst | Scrum Master | Security/Compliance |
|----------|-----------------|-----------------|----------------|------------|-----------------|-------------------------|------------------|--------------|---------------------|
| **Facilitate retrospective** | I | C | I | R | R | R | I | A/R | I |
| **Capture action items** | I | A/R | I | R | I | I | I | A/R | I |
| **Review metrics & outcomes** | A/R | A/R | I | I | I | I | C | I | I |
| **Update process documentation** | I | C | C | I | I | C | I | I | C |
| **Share learnings** | I | A/R | I | I | I | I | I | A/R | I |

---

## How to Use This Template

1. **Identify your activities**: List all key activities and decisions for your project
2. **Assign roles**: For each activity, assign R, A, C, or I based on involvement
3. **Validate**: Ensure every activity has at least one Accountable person
4. **Communicate**: Share the RACI with the team and confirm alignment
5. **Update regularly**: Revise as scope, team, or priorities change
6. **Reference during execution**: Use to resolve questions about who should be involved

## Tips for Effective RACI Matrices

- **One Accountable, multiple Responsible**: Accountability should be clear; execution can be distributed
- **Minimize Consulted roles**: Too many consultants slow decisions. Keep to key stakeholders
- **Plan for escalation**: If Accountable person can't decide, define escalation path
- **Document exceptions**: Note any unusual arrangements or special cases
- **Review during retrospectives**: Update RACI based on what actually happened vs. what was planned

## Example: Feature Implementation RACI

```
Feature: Add user authentication to dashboard

| Activity | Owner | Executor | Advisor | Status |
|----------|-------|----------|---------|--------|
| Design authentication flow | Technical Lead (A) | Developer (R) | Security (C) | Complete |
| Implement login UI | Developer (A/R) | Developer (R) | Product Manager (C) | In Progress |
| Security review | Security Officer (A) | Technical Lead (C) | DevOps (I) | Pending |
| Test authentication | QA Lead (A) | QA (R) | Developer (C) | Pending |
| Deploy to staging | DevOps (A/R) | DevOps (R) | Tech Lead (C) | Complete |
| Approval to release | Product Manager (A) | Project Manager (C) | - | Pending |
```

---

## Project-Specific RACI Template (Blank)

Use this blank template to create a RACI matrix for your specific project:

| Activity | Role 1 | Role 2 | Role 3 | Role 4 | Role 5 | Role 6 |
|----------|--------|--------|--------|--------|--------|--------|
| [Activity Name] | | | | | | |
| [Activity Name] | | | | | | |
| [Activity Name] | | | | | | |
| [Activity Name] | | | | | | |
| [Activity Name] | | | | | | |

**Instructions**: 
- Replace "Role 1-6" with your actual roles
- For each activity, enter R, A, C, I, or leave blank if not involved
- Ensure every row has at least one "A" (Accountable)
- Share with team and review for alignment
