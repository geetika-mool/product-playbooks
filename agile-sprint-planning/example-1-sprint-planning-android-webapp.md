# Sprint Planning Template (Example 1 – Android Web Application Team)

## 1. Sprint Overview
- **Sprint Number/Name:** Sprint 7 – “User Onboarding Flow”
- **Duration:** 2 weeks (Mar 16 – Mar 30, 2026)
- **Sprint Goal:** Deliver a seamless onboarding experience for new Android app users, including guided tour and faster login.

---

## 2. Team Capacity
- **Team Members & Availability:**
  - Priya (Frontend – Android) – Full availability
  - Arjun (Backend – APIs) – 1 day off
  - Kavya (QA) – Full availability
  - Rahul (UX Designer) – Half sprint (shared across projects)
- **Planned Capacity:** 25 Story Points (based on past velocity: 24–26 SP)
- **Buffer for Unplanned Work:** 3 SP (~12%)

---

## 3. Backlog Items
| ID   | User Story | Priority | Estimate | Owner | Status |
|------|------------|----------|----------|-------|--------|
| AND-201 | As a new user, I want a guided tour | High | 8 SP | Priya | Ready |
| AND-202 | As a user, I want Google login | High | 5 SP | Arjun | Ready |
| AND-203 | As a user, I want onboarding analytics tracked | Medium | 7 SP | Rahul | Ready |
| AND-204 | QA regression suite update for onboarding | High | 5 SP | Kavya | Ready |

---

## 4. Risks & Dependencies
- **Dependencies:** Google OAuth API integration.  
- **Risks:** Analytics SDK may conflict with existing crash reporting tool.  
- **Mitigation:** Schedule spike story to test SDK compatibility before full integration.

---

## 5. Sprint Commitments
- Deliver guided tour (AND-201).  
- Implement Google login (AND-202).  
- Add onboarding analytics (AND-203).  
- Update QA regression suite (AND-204).  

### Definition of Done (DoD)
- Code peer-reviewed and merged into main branch.  
- Unit and integration tests passed (≥80% coverage).  
- QA validated acceptance criteria.  
- Documentation updated (user guide + API specs).  
- Feature deployed to staging environment.  
- Smoke tests passed in staging.  
- Product Owner sign-off completed.  

---

## 6. Notes
### Key Decisions
- Guided tour will be implemented as a 3-step overlay, not a full tutorial.  

### Blockers & Concerns
- OAuth API quota limits need confirmation.  

### Action Items
| Action Item | Owner | Due Date | Status |
|-------------|-------|----------|--------|
| Test analytics SDK compatibility | Rahul | Mar 18 | Pending |
| Confirm OAuth quota with Google | Arjun | Mar 19 | In Progress |

### Communication & Alignment
- Mid-sprint sync with UX team scheduled for Mar 22.  

### Retrospective Carry-Over
- Improve backlog refinement cadence — add mid-sprint refinement session.
