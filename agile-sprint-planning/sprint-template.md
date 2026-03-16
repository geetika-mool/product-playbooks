# Sprint Planning Template

## 1. Sprint Overview
- **Sprint Number/Name:** 
(e.g., Sprint 12 – “Performance Improvements”)
- **Duration:** 
Usually 2 weeks; adjust based on team cadence.
- **Sprint Goal:** 
Write a clear, measurable outcome.  
*Tip: Goals should be outcome-focused, not activity-focused. 
Example: “Reduce login latency by 30%” instead of “Work on login module.”*

---

## 2. Team Capacity
- **Team Members & Availability:** 
List names, note vacations/holidays.  
- **Planned Capacity (Story Points/Hours):** 
Estimate based on past velocity.  
- **Buffer for Unplanned Work:** 
Reserve ~10–15% capacity for urgent issues.  
*Tip: Always validate capacity against historical velocity, not optimistic estimates.*

---

## 3. Backlog Items
| ID   | User Story | Priority | Estimate | Owner | Status |
|------|------------|----------|----------|-------|--------|
| CS-101 | As a user, I want faster login | High | 5 SP | Alice | Ready |
| CS-102 | As an admin, I want audit logs | Medium | 8 SP | Bob | In Review |

*Tip: Ensure backlog items are refined with acceptance criteria and no blockers before committing.*

---

## 4. Risks & Dependencies
- **Dependencies:** APIs from other teams, vendor deliverables.  
- **Risks:** New tool adoption, unclear requirements.  
- **Mitigation:** Spike stories, early alignment meetings.  
  *Tip: Document risks openly — it builds trust and helps track mitigation.*

---

## 5. Sprint Commitments
- (List finalized backlog items agreed by team)

### Definition of Done (DoD)
A backlog item is considered **Done** only if ALL of the following criteria are met:

1. **Code Quality**
   - Code is written, peer-reviewed, and merged into the main branch.
   - Follows coding standards and style guidelines.
   - No critical linting or static analysis issues remain.

2. **Testing**
   - Unit tests written and passed (≥80% coverage for new code).
   - Integration tests executed successfully.
   - Regression tests confirm no breakage of existing functionality.
   - QA has validated acceptance criteria.

3. **Documentation**
   - User-facing documentation updated (if applicable).
   - Technical documentation updated (API specs, architecture notes).
   - Release notes prepared for stakeholders.

4. **Deployment**
   - Feature deployed to staging environment.
   - Smoke tests passed in staging.
   - Rollback plan documented in case of failure.

5. **Acceptance Criteria**
   - All acceptance criteria defined in the user story are met.
   - No open critical or high-severity defects linked to the story.

6. **Sign-Off**
   - Product Owner has reviewed and accepted the story.
   - QA has signed off test results.
  
*Tip: Keep this DoD consistent across sprints. Review it periodically to ensure it reflects team maturity and product needs.*

---

## 6. Notes

### 6.1 Key Decisions
- Record important choices made during sprint planning.
- Example 1: “We will prioritize feature 1 over feature 2 .”
- Example 2: “We will prioritize P1 defects over new feature tests.”

### 6.2 Blockers & Concerns
- Capture unresolved issues or potential blockers.
- Example: “Dependency on vendor API delivery by Mar 20.”

### 6.3 Action Items
| Action Item | Owner | Due Date | Status |
|-------------|-------|----------|--------|
| Prepare performance test scripts | Carol | Mar 18 | In Progress |
| Align with Security Team on audit logs | Bob | Mar 19 | Pending |

### 6.4 Communication & Alignment
- Note any cross‑team syncs or stakeholder updates required.
- Example: “Schedule mid‑sprint check‑in with Infra team.”

### 6.5 Retrospective Carry‑Over
- Document items carried forward from the last retrospective.
- Example: “Improve backlog refinement cadence — add mid‑sprint session.”
