# OrangeHRM QA Sprint Planning Document

## Overview
- SDLC Duration: 1 Month (4 Weeks)
- Sprint Duration: Weekly (4 Sprints)
- Testing Velocity: 1 Feature per Day (5 Features per Sprint)
- Total Features: 20

---

## Sprint Planning Table

| Epic | User Story ID | Feature | User Story (As a..., I want to..., So that...) | Story Points | Sprint # |
|------|--------------|---------|-----------------------------------------------|--------------|----------|
| Authentication | US-001 | Login Functionality | As a user, I want to log in with valid credentials so that I can access the system dashboard | 3 | Sprint 1 |
| Authentication | US-002 | Invalid Login Handling | As a user, I want to see an error for invalid credentials so that I understand login failures | 2 | Sprint 1 |
| Authentication | US-003 | Forgot Password | As a user, I want to reset my password so that I can regain access if I forget it | 3 | Sprint 1 |
| Authentication | US-004 | Session Management | As a user, I want my session to timeout after inactivity so that my account remains secure | 5 | Sprint 1 |
| Navigation | US-005 | Dashboard Access | As a user, I want to view the dashboard after login so that I can see system summaries | 3 | Sprint 1 |

| Navigation | US-006 | Menu Navigation | As a user, I want to navigate between modules so that I can access different features | 3 | Sprint 2 |
| Navigation | US-007 | Role-Based Access | As an admin, I want role-based access control so that users see only authorized modules | 5 | Sprint 2 |
| PIM | US-008 | Add Employee | As an HR admin, I want to add employee details so that records are maintained | 5 | Sprint 2 |
| PIM | US-009 | Edit Employee | As an HR admin, I want to edit employee information so that records stay updated | 3 | Sprint 2 |
| PIM | US-010 | Delete Employee | As an HR admin, I want to delete employee records so that outdated data is removed | 2 | Sprint 2 |

| Leave | US-011 | Apply Leave | As an employee, I want to apply for leave so that I can request time off | 3 | Sprint 3 |
| Leave | US-012 | Approve Leave | As a manager, I want to approve leave requests so that I can manage team availability | 5 | Sprint 3 |
| Leave | US-013 | Leave Balance View | As a user, I want to view my leave balance so that I can plan time off | 2 | Sprint 3 |
| Time | US-014 | Timesheet Entry | As an employee, I want to log work hours so that my time is tracked | 3 | Sprint 3 |
| Time | US-015 | Timesheet Approval | As a manager, I want to approve timesheets so that payroll processing is accurate | 5 | Sprint 3 |

| Recruitment | US-016 | Add Candidate | As a recruiter, I want to add candidate details so that I can track applicants | 3 | Sprint 4 |
| Recruitment | US-017 | Schedule Interview | As a recruiter, I want to schedule interviews so that candidates are evaluated | 3 | Sprint 4 |
| Admin | US-018 | User Management | As an admin, I want to create/manage users so that access is controlled | 5 | Sprint 4 |
| Admin | US-019 | Job Title Management | As an admin, I want to manage job titles so that roles are standardized | 2 | Sprint 4 |
| System | US-020 | Logout Functionality | As a user, I want to log out securely so that my session is terminated safely | 2 | Sprint 4 |

---

## Notes
- Story points follow Fibonacci scale (1, 2, 3, 5, 8)
- Each sprint includes 5 features aligned with 5 working days
- Prioritization ensures critical authentication and navigation flows are tested first
- Coverage includes functional, UI, and end-to-end scenarios

