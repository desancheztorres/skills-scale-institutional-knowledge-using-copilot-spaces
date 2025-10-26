# OctoAcme Role Collaboration Matrix

## Purpose
This matrix clarifies accountability and collaboration patterns across OctoAcme roles throughout the project lifecycle. Use this as a reference to understand who is Responsible, Accountable, Consulted, or Informed (RACI) for key activities.

## How to Use This Matrix
- **R (Responsible)**: Does the work to complete the task
- **A (Accountable)**: Ultimately answerable for completion and has decision authority (only one A per activity)
- **C (Consulted)**: Provides input and expertise; two-way communication
- **I (Informed)**: Kept updated on progress; one-way communication

---

## Project Initiation Phase

| Activity | PM | PdM | PO | Dev | QA Lead | DevOps | Release Mgr | Stakeholder | Change Champion |
|----------|----|----|----|----|---------|--------|-------------|-------------|-----------------|
| Define problem statement | C | A | C | I | I | I | I | C | I |
| Create project charter | R | C | C | I | I | I | I | C | I |
| Identify stakeholders | R | C | A | I | I | I | I | C | I |
| Secure initial approvals | R | C | I | I | I | I | I | A | I |
| Setup project repository | R | I | I | R | I | R | I | I | I |

---

## Planning Phase

| Activity | PM | PdM | PO | Dev | QA Lead | DevOps | Release Mgr | Stakeholder | Change Champion |
|----------|----|----|----|----|---------|--------|-------------|-------------|-----------------|
| Define roadmap | C | A | R | C | I | I | I | C | I |
| Write user stories | C | C | A/R | C | C | I | I | I | I |
| Estimate effort | C | I | C | A/R | R | C | I | I | I |
| Define acceptance criteria | C | C | R | C | A | I | I | I | I |
| Plan test strategy | C | I | C | C | A/R | C | I | I | I |
| Plan release timeline | R | C | C | I | C | C | A | C | I |
| Identify dependencies | R | C | C | C | C | C | C | C | I |

---

## Execution Phase

| Activity | PM | PdM | PO | Dev | QA Lead | DevOps | Release Mgr | Stakeholder | Change Champion |
|----------|----|----|----|----|---------|--------|-------------|-------------|-----------------|
| Implement features | I | I | C | A/R | C | C | I | I | I |
| Write/run tests | I | I | C | R | A | C | I | I | I |
| Code reviews | I | I | C | A/R | C | C | I | I | I |
| Track progress | A/R | C | C | I | I | I | I | I | I |
| Update project board | R | I | R | R | I | I | I | I | I |
| Manage risks | A/R | C | C | C | C | C | C | C | I |
| Run standups | A/R | C | C | R | R | R | C | I | I |
| Sprint demos | R | C | A | R | R | I | I | C | I |

---

## Quality Assurance Activities

| Activity | PM | PdM | PO | Dev | QA Lead | DevOps | Release Mgr | Stakeholder | Change Champion |
|----------|----|----|----|----|---------|--------|-------------|-------------|-----------------|
| Define quality gates | C | I | C | C | A/R | C | C | I | I |
| Execute test plans | I | I | C | R | A/R | C | I | I | I |
| Bug triage | C | C | C | R | A/R | I | I | I | I |
| Security scanning | I | I | I | C | C | A/R | C | I | I |
| Performance testing | C | C | I | C | C | A/R | C | I | I |
| Acceptance testing | I | C | A | R | R | I | C | C | I |

---

## Release and Deployment

| Activity | PM | PdM | PO | Dev | QA Lead | DevOps | Release Mgr | Stakeholder | Change Champion |
|----------|----|----|----|----|---------|--------|-------------|-------------|-----------------|
| Release planning | C | C | C | I | C | C | A/R | C | I |
| Prepare release notes | C | C | C | R | C | I | A/R | I | I |
| Configure CI/CD pipeline | I | I | I | C | I | A/R | C | I | I |
| Deploy to staging | I | I | I | C | C | A/R | R | I | I |
| Run smoke tests | I | I | I | C | R | C | A | I | I |
| Go/no-go decision | C | C | I | C | C | C | A/R | C | I |
| Deploy to production | I | I | I | C | C | A/R | R | I | I |
| Post-deployment verification | C | I | I | R | R | A/R | R | I | I |
| Release announcement | C | C | I | I | I | I | R | I | A |

---

## Retrospective and Continuous Improvement

| Activity | PM | PdM | PO | Dev | QA Lead | DevOps | Release Mgr | Stakeholder | Change Champion |
|----------|----|----|----|----|---------|--------|-------------|-------------|-----------------|
| Facilitate retrospective | A/R | R | R | R | R | R | R | C | C |
| Capture learnings | R | R | R | R | R | R | R | C | C |
| Identify improvements | C | C | C | C | C | C | C | C | A/R |
| Create action items | R | C | C | C | C | C | C | I | C |
| Track improvement progress | A/R | I | I | I | I | I | I | I | C |
| Implement process changes | C | C | C | C | C | C | C | I | A/R |

---

## Communication and Stakeholder Management

| Activity | PM | PdM | PO | Dev | QA Lead | DevOps | Release Mgr | Stakeholder | Change Champion |
|----------|----|----|----|----|---------|--------|-------------|-------------|-----------------|
| Weekly status updates | A/R | C | C | C | C | C | C | I | I |
| Monthly stakeholder updates | R | R | C | I | I | I | I | A | I |
| Escalation management | A/R | C | C | C | C | C | C | C | I |
| Stakeholder demos | C | C | A/R | R | R | C | I | C | I |
| Change communications | C | C | I | I | I | I | I | C | A/R |

---

## Tips for Using This Matrix

1. **Identify Gaps**: If an activity lacks an Accountable (A) role, clarify ownership before proceeding.
2. **Reduce Bottlenecks**: If one person is Accountable for too many activities, consider redistributing responsibilities.
3. **Improve Communication**: Ensure all Consulted (C) and Informed (I) parties are included in appropriate communication channels.
4. **Adapt to Context**: This matrix represents typical patterns. Adjust based on team size, project complexity, and organizational structure.
5. **Review Regularly**: Revisit the matrix during retrospectives to identify collaboration improvements.

---

*This collaboration matrix was created to address role clarity and accountability gaps identified in [Issue #6](https://github.com/desancheztorres/skills-scale-institutional-knowledge-using-copilot-spaces/issues/6).*
