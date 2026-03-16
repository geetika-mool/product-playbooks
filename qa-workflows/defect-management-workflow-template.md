# Defect Management Workflow Template

## 1. Purpose
Define a standardized process for logging, prioritizing, tracking, and resolving defects.  
This workflow ensures transparency, accountability, and consistent quality governance across teams.

---

## 2. Defect Lifecycle
Defects should move through clear, trackable states:

1. **Open** – Logged by QA/SDET/Automation Engineer.  
2. **Triaged** – Severity and priority reviewed, owner identified (developer, hardware engineer, etc.).  
3. **In Progress** – Fix actively being worked on.  
4. **Blocked** – Work cannot proceed due to dependencies, environment issues, or resource constraints.  
5. **Resolved** – Fix implemented and unit tested.  
6. **Verified** – QA validates fix via regression/automation.  
7. **Closed** – Defect officially marked complete. Closure reasons must be specified:  
   - **Fixed** – Issue resolved and verified.  
   - **Will Not Fix** – Accepted as known limitation or low impact.  
   - **Not Reproducible** – Could not be reproduced despite attempts. 
8. **Reopened** – If issue persists after verification.  

---

## 3. Severity & Priority Guidelines
- **Severity (Impact on system):**
  - **Critical:** Blocks release, system crash, data loss.  
  - **Major:** Key functionality broken, workaround exists.  
  - **Minor:** Cosmetic/UI issues, low impact.  

- **Priority (Order of resolution):**
  - **High:** Must be fixed immediately.  
  - **Medium:** Fix required before release.  
  - **Low:** Can be deferred to future sprint.  

---

## 4. Roles & Responsibilities
- **SDET (Software Development Engineer in Test):**
  - Designs testable code and identifies defects early in SDLC.  
  - Logs defects linked to unit/integration tests.  
  - Collaborates with developers on testability improvements.  

- **QA Automation Engineer:**
  - Logs defects found during regression, UI, or performance automation.  
  - Ensures defects are reproducible with automation scripts.  
  - Integrates defect tracking into CI/CD pipelines.  

- **Manual QA Engineer:**
  - Logs defects from exploratory and usability testing.  
  - Provides detailed reproduction steps and environment info.  

- **Developers:**
  - Fix assigned defects and confirm resolution.  
  - Collaborate with SDETs for unit test coverage.  

- **Hardware Engineers (if applicable):**
  - Resolve board-level or firmware defects.  
  - Provide logs from lab equipment or harnesses.  

- **Team Lead / QA Lead:**
  - Reviews severity/priority assignments.  
  - Ensures defect backlog is managed and risks escalated.  

- **Product Owner / Project Manager:**
  - Reviews defect trends and release readiness.  
  - Decides on deferral of low-priority defects.  

---

## 5. Tracking Tools
- **Software Teams:** JIRA, GitHub Issues, GitLab Issues, Bugzilla.  
- **Hardware Teams:** TestRail, Lab dashboards, custom defect trackers.  
- **Integration:** CI/CD pipelines auto-log failures into defect tracking tools.  

---

## 6. Reporting
- **Daily:** Defects logged, grouped by severity.  
- **Weekly:** Defect trends (new, resolved, open).  
- **Dashboards:**  
  - Defects by severity (Critical, Major, Minor).  
  - Average resolution time.  
  - Backlog size and aging defects.  

---

## 7. Risks & Mitigation
- **Risk:** Misclassification of severity → *Mitigation:* QA Lead reviews all Critical/Major defects.  
- **Risk:** Defect backlog grows unmanageable → *Mitigation:* Weekly triage meetings, backlog grooming.  
- **Risk:** Defects reopened frequently → *Mitigation:* Strengthen verification, add regression automation.  
- **Risk:** Poor defect reproduction steps → *Mitigation:* Enforce defect logging standards (steps, environment, logs).  
- **Risk:** Tool fragmentation across teams → *Mitigation:* Standardize defect tracking tools or integrate dashboards.  
- **Risk:** Delayed fixes due to resource constraints → *Mitigation:* Escalation process, prioritization by Product Owner.  

---

## 8. Continuous Improvement
- Conduct defect retrospectives each sprint.  
- Track defect leakage (issues found post-release).  
- Improve automation coverage to reduce defect recurrence and improve reproducibility.  
- Share lessons learned across teams to refine severity/priority definitions. 
