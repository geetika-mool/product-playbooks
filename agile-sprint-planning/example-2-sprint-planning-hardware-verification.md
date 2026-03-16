# Sprint Planning Template (Example 2 – Hardware Verification Team)

## 1. Sprint Overview
- **Sprint Number/Name:** Sprint 3 – “MCU-X100 Verification”
- **Duration:** 2 weeks (Mar 16 – Mar 30, 2026)
- **Sprint Goal:** Verify the new microcontroller board (MCU-X100) meets design specifications and passes environmental stress tests before production.

---

## 2. Team Capacity
- **Team Members & Availability:**
  - Ananya (Hardware Engineer) – Full availability
  - Vikram (Firmware Engineer) – 2 days off
  - Meera (QA/Verification) – Full availability
  - Suresh (Lab Technician) – Full availability
- **Planned Capacity:** 20 Story Points (based on past velocity: 18–21 SP)
- **Buffer for Unplanned Work:** 2 SP (~10%)

---

## 3. Backlog Items
| ID   | Verification Task | Priority | Estimate | Owner | Status |
|------|------------------|----------|----------|-------|--------|
| HW-301 | Power consumption under load | High | 6 SP | Ananya | Ready |
| HW-302 | Signal integrity on SPI/I2C | High | 5 SP | Vikram | Ready |
| HW-303 | Thermal performance test | Medium | 5 SP | Meera | Ready |
| HW-304 | Firmware boot sequence reliability | High | 4 SP | Vikram | Ready |

---

## 4. Risks & Dependencies
- **Dependencies:** Prototype boards availability (only 10 units).  
- **Risks:** Thermal chamber calibration may delay stress testing.  
- **Mitigation:** Prioritize functional tests first; schedule chamber maintenance early.

---

## 5. Sprint Commitments
- Complete power consumption and signal integrity tests.  
- Conduct thermal performance validation.  
- Verify firmware boot sequence reliability.  

### Definition of Done (DoD)
- Test scripts executed and results logged in TestRail.  
- Measurements validated against design specifications.  
- No critical defects open; minor issues documented.  
- Verification report drafted and reviewed by QA lead.  
- Prototype boards returned to inventory with updated status.  
- Stakeholder sign-off obtained from Hardware Lead.  

---

## 6. Notes
### Key Decisions
- Firmware boot sequence tests will run on 5 boards in parallel to save time.  

### Blockers & Concerns
- Limited prototype boards may slow down parallel testing.  

### Action Items
| Action Item | Owner | Due Date | Status |
|-------------|-------|----------|--------|
| Calibrate thermal chamber | Suresh | Mar 17 | Pending |
| Prepare automated test scripts | Meera | Mar 18 | In Progress |

### Communication & Alignment
- Weekly sync with Firmware team scheduled for Mar 20.  

### Retrospective Carry-Over
- Improve defect logging consistency — adopt new severity tagging system.
