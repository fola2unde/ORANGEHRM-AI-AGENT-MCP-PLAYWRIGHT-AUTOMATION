# Sprint Planning Document — OrangeHRM QA Automation

**Application:** https://opensource-demo.orangehrmlive.com/web/index.php/auth/login
**QA Focus:** Functional · UI · API · End-to-End
**SDLC Duration:** 1 month (4 weeks) · **Sprint Duration:** 1 week · **Velocity:** 1 feature/day

---

## Summary

| Metric | Value |
|---|---|
| Total Sprints | 4 |
| Total Features | 20 |
| Total Story Points | 71 |
| Avg. Points per Sprint | 17.75 |
| Story Point Scale | Fibonacci (1, 2, 3, 5, 8) |

---

## Sprint 1 — Critical Path & Core Authentication
**Week 1 · 18 Story Points**
> Priority: Login, error handling, session management, and dashboard navigation are the foundation of all subsequent testing.

| Epic | User Story ID | Feature | User Story | Story Points | Sprint # |
|---|---|---|---|---|---|
| Authentication | QA-001 | Login — valid credentials | As a QA engineer, I want to verify that a valid username and password grants access to the dashboard, so that users can successfully authenticate into the system. | 5 | Sprint 1 – Day 1 |
| Authentication | QA-002 | Login — invalid / error handling | As a QA engineer, I want to test login with invalid, blank, and SQL-injection inputs, so that the system properly rejects unauthorized access and displays appropriate error messages. | 5 | Sprint 1 – Day 2 |
| Authentication | QA-003 | Forgot password flow | As a QA engineer, I want to validate the "Forgot Password" reset link generation and delivery, so that users can recover access securely without admin intervention. | 3 | Sprint 1 – Day 3 |
| Dashboard | QA-004 | Dashboard widgets & navigation | As a QA engineer, I want to verify all dashboard widgets load with correct data and all navigation menu items route to the correct modules, so that authenticated users can reach every feature. | 3 | Sprint 1 – Day 4 |
| Authentication | QA-005 | Session management & logout | As a QA engineer, I want to test session timeout, token expiry, and the logout function, so that user sessions are terminated securely and no data leaks between sessions. | 2 | Sprint 1 – Day 5 |

**Sprint 1 Total: 18 story points**

---

## Sprint 2 — Employee & People Information Management (PIM)
**Week 2 · 19 Story Points**
> Priority: Employee record CRUD operations are the core data layer relied upon by Leave, Time, and Recruitment modules.

| Epic | User Story ID | Feature | User Story | Story Points | Sprint # |
|---|---|---|---|---|---|
| PIM | QA-006 | Add new employee | As a QA engineer, I want to test creating a new employee record with all mandatory and optional fields, so that HR can onboard staff correctly in the system. | 5 | Sprint 2 – Day 1 |
| PIM | QA-007 | Employee search & list view | As a QA engineer, I want to validate search by name, ID, department, and employment status, so that managers can quickly retrieve accurate employee records. | 3 | Sprint 2 – Day 2 |
| PIM | QA-008 | Edit & update employee profile | As a QA engineer, I want to verify that editing personal, contact, and job information saves correctly and reflects in the employee list, so that employee data remains accurate and up-to-date. | 5 | Sprint 2 – Day 3 |
| PIM | QA-009 | Upload & view profile photo | As a QA engineer, I want to test uploading valid and invalid image formats and sizes for the employee profile photo, so that the UI enforces correct file constraints and displays images properly. | 3 | Sprint 2 – Day 4 |
| PIM | QA-010 | Delete employee record | As a QA engineer, I want to verify that deleting an employee shows a confirmation prompt and permanently removes the record, so that accidental deletions are prevented and data integrity is maintained. | 3 | Sprint 2 – Day 5 |

**Sprint 2 Total: 19 story points**

---

## Sprint 3 — Leave Management & Time Tracking
**Week 3 · 18 Story Points**
> Priority: Leave and Time modules represent the most-used employee self-service workflows and involve multi-role approval chains.

| Epic | User Story ID | Feature | User Story | Story Points | Sprint # |
|---|---|---|---|---|---|
| Leave | QA-011 | Apply for leave | As a QA engineer, I want to test submitting a leave request with valid leave types, date ranges, and comments, so that employees can successfully request time off and the system records it correctly. | 5 | Sprint 3 – Day 1 |
| Leave | QA-012 | Approve / reject leave request | As a QA engineer, I want to verify that a manager can approve or reject a leave request and the status updates correctly for the employee, so that the leave workflow functions end-to-end. | 5 | Sprint 3 – Day 2 |
| Leave | QA-013 | Leave balance & entitlement | As a QA engineer, I want to validate that leave balances deduct correctly after approval and entitlements are displayed accurately, so that leave quota limits are enforced by the system. | 3 | Sprint 3 – Day 3 |
| Time | QA-014 | Add & submit timesheet | As a QA engineer, I want to test adding project hours to a timesheet for a given week and submitting it for approval, so that employee work hours are captured and routed correctly. | 3 | Sprint 3 – Day 4 |
| Time | QA-015 | Attendance punch-in / punch-out | As a QA engineer, I want to verify the punch-in and punch-out functionality records accurate timestamps and prevents duplicate punches within the same session, so that attendance tracking is reliable. | 2 | Sprint 3 – Day 5 |

**Sprint 3 Total: 18 story points**

---

## Sprint 4 — Recruitment, Admin & End-to-End Regression
**Week 4 · 16 Story Points**
> Priority: Recruitment and Admin config finalize module coverage. Sprint is intentionally lighter to allow buffer for defect retesting and release sign-off.

| Epic | User Story ID | Feature | User Story | Story Points | Sprint # |
|---|---|---|---|---|---|
| Recruitment | QA-016 | Post a vacancy | As a QA engineer, I want to test creating and publishing a job vacancy with all required fields, so that recruitment teams can list open positions and begin the hiring pipeline. | 3 | Sprint 4 – Day 1 |
| Recruitment | QA-017 | Candidate application flow | As a QA engineer, I want to verify adding a candidate, attaching a resume, and moving them through interview stages, so that the full recruitment lifecycle can be tracked in the system. | 5 | Sprint 4 – Day 2 |
| Admin | QA-018 | User roles & permissions | As a QA engineer, I want to test creating user accounts with Admin, ESS, and Supervisor roles and confirm module access aligns with role permissions, so that access control is enforced correctly. | 5 | Sprint 4 – Day 3 |
| Admin | QA-019 | Job titles & pay grades config | As a QA engineer, I want to validate CRUD operations on job titles, pay grades, and employment statuses under Admin configuration, so that organizational structure data is managed accurately. | 1 | Sprint 4 – Day 4 |
| Admin | QA-020 | End-to-end regression suite | As a QA engineer, I want to run a full regression pass covering login → employee creation → leave request → recruitment → admin configuration, so that cross-module integrations are verified before the release sign-off. | 2 | Sprint 4 – Day 5 |

**Sprint 4 Total: 16 story points**

---

## Story Point Breakdown by Sprint

| Sprint | Focus Area | Story Points | % of Total |
|---|---|---|---|
| Sprint 1 | Authentication + Dashboard | 18 | 25.4% |
| Sprint 2 | PIM | 19 | 26.8% |
| Sprint 3 | Leave + Time | 18 | 25.4% |
| Sprint 4 | Recruitment + Admin + Regression | 16 | 22.5% |
| **Grand Total** | | **71** | **100%** |

---

## Story Point Distribution by Epic

| Epic | Features | Total Points |
|---|---|---|
| Authentication | QA-001, QA-002, QA-003, QA-005 | 15 |
| Dashboard | QA-004 | 3 |
| PIM | QA-006, QA-007, QA-008, QA-009, QA-010 | 19 |
| Leave | QA-011, QA-012, QA-013 | 13 |
| Time | QA-014, QA-015 | 5 |
| Recruitment | QA-016, QA-017 | 8 |
| Admin | QA-018, QA-019, QA-020 | 8 |

---

## Modules Not Covered (Recommended for Cycle 2)

The following lower-risk, non-critical-path modules are good candidates for a second SDLC cycle:

- **Reports** — Custom report generation and export
- **Performance** — Appraisal cycles and KPI tracking
- **Directory** — Employee directory and org chart
- **Claims** — Expense claim submission and approval
- **Buzz** — Social feed and internal communication

---

## Notes

- **Fibonacci scale used:** 1, 2, 3, 5, 8
- **Sprint 4 is intentionally lighter (16 pts)** to provide buffer for defect retesting, environment instability, and release sign-off prep — standard QA practice.
- **Negative-path testing (QA-002)** carries the same story points as happy-path login (QA-001) due to the volume of boundary and security scenarios (SQL injection, blank fields, brute-force lockout).
- **End-to-end regression (QA-020)** scores low (2 pts) because individual module test cases already exist by Sprint 4; this story focuses on cross-module scripting and integration validation only.
