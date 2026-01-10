# Sprint Planning (Workday Agile Delivery)

## Purpose
Sprint Planning aligns HR, IT, and Workday delivery teams on **what will be delivered**, **why it matters**, and **how it will be executed** within the constraints of the Workday ecosystem.

For Workday teams, sprint planning must balance:
- Business urgency
- Tenant and release constraints
- Integration dependencies
- Compliance and risk

---

## Participants & Roles

| Role | Responsibility |
|----|---------------|
| Product Owner | Prioritizes backlog, clarifies business value |
| Workday HRIS Analysts | Estimate effort, identify configuration impacts |
| Integration Specialist | Assess downstream/upstream dependencies |
| Architect / Tech Lead | Validate design alignment & scalability |
| Scrum Master | Facilitates and removes blockers |

---

## Inputs

- Groomed backlog with acceptance criteria
- Sprint capacity (accounting for support, releases, PTO)
- Workday release calendar & blackout periods
- Known integration dependencies
- Outstanding defects or carryover work

---

## Sprint Planning Flow

1. **Sprint Goal Definition**
   - Define 1–2 clear outcomes tied to business value  
   - Example: *“Enable automated job change feed to downstream payroll”*

2. **Backlog Review**
   - Review prioritized user stories
   - Confirm scope clarity and acceptance criteria
   - Identify cross-functional dependencies

3. **Workday Impact Assessment**
   - Business Process Framework (BPF) changes
   - Security or role impacts
   - Reporting implications
   - Integration triggers or sequencing

4. **Effort Estimation**
   - Use relative estimation (story points or t-shirt sizing)
   - Consider testing, documentation, and deployment effort

5. **Commitment**
   - Finalize sprint backlog
   - Confirm sprint goal and success criteria

---

## Workday-Specific Considerations

- Avoid deploying during Workday weekly service windows
- Account for tenant refresh timing
- Validate if work conflicts with upcoming Workday releases
- Ensure regression testing coverage for impacted business processes

---

## Outputs

- Committed sprint backlog
- Defined sprint goal
- Identified risks and mitigation actions

---

## Signals of a Healthy Sprint Plan

- Sprint goal is clear and achievable
- Stories are small, testable, and well-defined
- Dependencies are identified early
- Team confidence is high

---

## Continuous Improvement

Sprint planning effectiveness is reviewed during retrospectives.  
Common improvement areas:
- Overcommitment
- Unclear acceptance criteria
- Missed integration dependencies

