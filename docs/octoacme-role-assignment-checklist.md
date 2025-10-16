# OctoAcme — Role Assignment Checklist

## Purpose
Ensure clear role assignments and accountability at project initiation, reducing ambiguity and improving cross-functional collaboration.

## When to Use
- At the start of every new project during initiation
- When team composition changes mid-project
- During project retrospectives to validate role effectiveness

## Role Assignment Process

### Step 1: Identify Required Roles
Based on project scope and complexity, determine which roles are needed:

#### Core Roles (Required for most projects)
- [ ] **Project Manager**: Assigned Name: _____________
- [ ] **Product Manager**: Assigned Name: _____________
- [ ] **Developer(s)**: Assigned Names: _____________

#### Extended Roles (As needed)
- [ ] **Scrum Master**: Assigned Name: _____________
- [ ] **QA Lead**: Assigned Name: _____________
- [ ] **Technical Architect**: Assigned Name: _____________
- [ ] **Release Manager**: Assigned Name: _____________
- [ ] **Business Analyst**: Assigned Name: _____________
- [ ] **Support Lead**: Assigned Name: _____________

#### Governance & Stakeholder Roles
- [ ] **Project Sponsor**: Assigned Name: _____________
- [ ] **Key Stakeholders**: List: _____________

### Step 2: Define RACI Matrix
Create a RACI (Responsible, Accountable, Consulted, Informed) matrix for key project activities:

| Activity | PM | PdM | Scrum Master | Dev | QA Lead | Architect | Release Mgr | BA | Support |
|----------|----|----|--------------|-----|---------|-----------|-------------|----|---------|
| Requirements gathering | C | A | I | C | I | C | I | R | C |
| Sprint planning | R | C | A | R | C | I | I | C | I |
| Architecture decisions | C | I | I | C | C | A | I | I | I |
| Code reviews | I | I | I | R/A | C | C | I | I | I |
| Testing & QA | C | I | C | C | A | I | C | I | C |
| Release coordination | C | C | C | C | C | I | A | I | C |
| Support escalations | I | C | I | C | I | I | I | I | A |

_Customize this matrix based on your project's specific needs._

### Step 3: Communication & Collaboration Setup
- [ ] All team members added to project communication channels (Slack, Teams, etc.)
- [ ] Access granted to project repositories, boards, and documentation
- [ ] Meeting cadence established and calendar invites sent
- [ ] Escalation paths documented and communicated
- [ ] Decision-making authority clarified for each role

### Step 4: Role Onboarding
- [ ] Each role has reviewed their responsibilities in [Roles and Personas](octoacme-roles-and-personas.md)
- [ ] Each role understands success metrics for the project
- [ ] Each role has access to necessary tools and systems
- [ ] Each role knows who to go to for different types of questions or blockers

### Step 5: Role Validation Checkpoints
Schedule regular checkpoints to validate role effectiveness:

- [ ] **Week 1**: Confirm all roles have what they need to start
- [ ] **Mid-project**: Review RACI matrix and adjust if needed
- [ ] **Retrospective**: Discuss role clarity and collaboration effectiveness

## Red Flags to Watch For
- Multiple people believe they are accountable for the same deliverable
- Unclear decision-making authority causing delays
- Key activities with no clearly responsible party
- Role overlap causing confusion or duplication of effort
- Communication gaps between cross-functional roles

## Decision Log Template
Document key role-related decisions:

| Date | Decision | Rationale | Owner | Impact |
|------|----------|-----------|-------|--------|
| | | | | |

## Tips for Success
- **Avoid role overlap**: Each major deliverable should have one accountable person
- **Clarify decision rights**: Document who has final say on requirements, architecture, quality, and releases
- **Enable collaboration**: Ensure roles that depend on each other have regular touchpoints
- **Update as needed**: Projects evolve; revisit role assignments when scope or team changes
- **Document exceptions**: If roles deviate from standard definitions, document why

## Related Documentation
- [Roles and Personas](octoacme-roles-and-personas.md) - Detailed role definitions
- [Project Initiation Guide](octoacme-project-initiation.md) - Initial project setup
- [Team Onboarding Template](octoacme-team-onboarding-template.md) - Onboarding new team members

---

*For questions about role assignments, contact your Project Manager or Product Lead.*
