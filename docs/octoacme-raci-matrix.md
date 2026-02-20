# OctoAcme RACI Matrix

## Purpose
Define clear accountability and responsibility for project activities across all roles. The RACI matrix helps teams understand who is Responsible, Accountable, Consulted, and Informed for each project activity.

## RACI Definitions
- **R (Responsible):** Performs the work to complete the task
- **A (Accountable):** Ultimate ownership and approval authority (only one A per activity)
- **C (Consulted):** Provides input and expertise before decisions or actions
- **I (Informed):** Kept up-to-date on progress and decisions

---

## Project Initiation Phase

| Activity | Project Manager | Product Manager | Developer | QA Lead | Release Manager | Risk Owner | Communications Coordinator | Executive Sponsor |
|----------|----------------|-----------------|-----------|---------|----------------|------------|---------------------------|-------------------|
| Define problem statement | C | R/A | C | I | I | I | I | C |
| Identify stakeholders | R/A | C | I | I | I | I | R | C |
| Create project charter | R/A | C | C | I | I | C | C | C |
| Approve project charter | C | C | I | I | I | I | I | A |
| Establish communication plan | R | I | I | I | I | I | C | I |

---

## Planning Phase

| Activity | Project Manager | Product Manager | Developer | QA Lead | Release Manager | Risk Owner | Communications Coordinator | Executive Sponsor |
|----------|----------------|-----------------|-----------|---------|----------------|------------|---------------------------|-------------------|
| Define acceptance criteria | C | R/A | C | C | I | I | I | I |
| Estimate work | C | C | R/A | C | I | I | I | I |
| Create sprint backlog | R | C | C | C | I | I | I | I |
| Identify dependencies | R/A | C | C | C | C | R | I | I |
| Establish test strategy | C | C | C | R/A | C | I | I | I |
| Create release plan | R | C | C | C | R/A | C | I | I |
| Identify initial risks | R | C | C | C | C | R/A | I | C |
| Approve project plan | A | C | I | I | I | I | I | C |

---

## Execution & Tracking Phase

| Activity | Project Manager | Product Manager | Developer | QA Lead | Release Manager | Risk Owner | Communications Coordinator | Executive Sponsor |
|----------|----------------|-----------------|-----------|---------|----------------|------------|---------------------------|-------------------|
| Implement features | C | C | R/A | C | I | I | I | I |
| Write and execute tests | C | I | C | R/A | I | I | I | I |
| Conduct code reviews | I | I | R/A | C | I | I | I | I |
| Track progress | R/A | C | C | C | I | C | I | I |
| Manage risks | R | C | C | C | C | R/A | I | C |
| Bug triage | C | C | C | R/A | I | I | I | I |
| Update stakeholders | R | C | I | I | I | C | R | I |
| Resolve blockers | R/A | C | C | C | C | C | I | C |

---

## Release & Deployment Phase

| Activity | Project Manager | Product Manager | Developer | QA Lead | Release Manager | Risk Owner | Communications Coordinator | Executive Sponsor |
|----------|----------------|-----------------|-----------|---------|----------------|------------|---------------------------|-------------------|
| Prepare release notes | C | C | C | C | R/A | I | C | I |
| Conduct release readiness review | C | C | C | C | R/A | C | I | I |
| Approve deployment | C | C | C | C | A | C | I | C |
| Execute deployment | C | I | C | C | R/A | I | I | I |
| Verify deployment | C | I | R | R | A | I | I | I |
| Announce release | C | C | I | I | C | I | R/A | I |
| Monitor post-deployment | C | I | R | C | R/A | C | I | I |

---

## Retrospective & Continuous Improvement Phase

| Activity | Project Manager | Product Manager | Developer | QA Lead | Release Manager | Risk Owner | Communications Coordinator | Executive Sponsor |
|----------|----------------|-----------------|-----------|---------|----------------|------------|---------------------------|-------------------|
| Facilitate retrospective | R/A | C | C | C | C | C | C | I |
| Document learnings | R | C | C | C | C | C | C | I |
| Create improvement actions | R/A | C | C | C | C | C | I | I |
| Track action items | R/A | I | C | C | C | C | I | I |
| Share lessons learned | C | I | I | I | I | I | R/A | I |

---

## Escalation & Decision-Making

| Activity | Project Manager | Product Manager | Developer | QA Lead | Release Manager | Risk Owner | Communications Coordinator | Executive Sponsor |
|----------|----------------|-----------------|-----------|---------|----------------|------------|---------------------------|-------------------|
| Scope changes | C | R/A | C | C | C | C | I | C |
| Resource allocation | R | C | I | I | I | I | I | A |
| Critical risk decisions | R | C | I | I | C | R/A | I | C |
| Budget decisions | C | C | I | I | I | I | I | A |
| Timeline extensions | R/A | C | I | I | C | C | I | C |
| Deployment rollback | C | C | C | C | R/A | C | I | C |

---

## How to Use This Matrix
1. Reference this matrix during project kickoff to clarify roles
2. Review during planning to ensure all activities have clear ownership
3. Use as a decision-making guide when questions arise about authority
4. Update if your project requires additional activities or roles
5. Include in project documentation for team reference

## Notes
- Some activities may have multiple R's when work is shared, but should only have one A
- Adjust the matrix based on project size and complexity
- For smaller projects, some roles may be combined
