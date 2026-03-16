# QA Reporting Workflow (Example – Android App Team)

## 1. Purpose
Track and communicate QA progress for the Android onboarding flow (guided tour, Google login, analytics).

---

## 2. Daily Reporting
Date: Mar 17
Executed: 25 test cases
Passed: 22
Failed: 3
Defects logged: 1 Critical (Login timeout), 2 Minor (UI overlay misalignment)
Blockers: None

---

## 3. Weekly Summary
Week 1 Summary:
Planned: 120 test cases
Executed: 80
Defects: 6 logged (2 Critical, 3 Major, 1 Minor)
Risks: API quota limits, device fragmentation
Mitigation: Prioritized top 3 devices, requested quota increase

---

## 4. Defect Tracking
Defect ID: QA-201
Title: Guided tour overlay not dismissing
Severity: Major
Reporter: Salim
Owner: Priya (Android Developer)
Status: In Progress

---

## 5. Dashboards
- Test coverage: 83% executed.  
- Defects by severity: Critical (2), Major (3), Minor (1).  
- Pass rate: 88%.  
- Trend chart: Defects logged vs resolved over 2 weeks.  

---

## 6. Final Report
Final QA Report – Sprint 12
Scope: Onboarding flow (guided tour, login, analytics)
Executed: 120 test cases (95% coverage)
Defects: 0 Critical, 2 Major, 3 Minor (all resolved)
Risks: API quota issue mitigated
Recommendation: Ready for release

---

## 7. Communication Channels
- Daily logs → TestRail.  
- Weekly summaries → Slack + email.  
- Dashboards → Firebase Test Lab + Graffana.  
- Final report → Product Owner.  

---

## 8. Roles & Responsibilities
- QA Engineer: Logs daily execution.  
- Team Lead: Consolidates weekly summary.  
- Developers: Resolve defects.  
- Product Owner: Reviews final report.  

