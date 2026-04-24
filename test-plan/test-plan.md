# Test Plan — OpenCart Manual Testing

## 1. Introduction
This document describes the test plan for the manual testing of the 
OpenCart demo e-commerce platform. It defines the scope, objectives, 
approach, and resources required to execute the testing activities.

**Project:** OpenCart Manual Testing  
**Version:** 1.0  
**Author:** Miguel Guedes  
**Date:** April 2026  

---

## 2. Objectives
- Validate the core functional flows of the OpenCart platform
- Identify and document defects found during test execution
- Ensure the application meets the expected business requirements
- Deliver a final quality report with metrics and findings

---

## 3. Scope

### In Scope
- User Registration & Login
- Product Search & Navigation
- Shopping Cart
- Checkout & Payment
- Admin Panel

### Out of Scope
- Performance testing
- Security testing
- Mobile responsiveness
- Payment gateway integration (real transactions)

---

## 4. Test Approach
- **Type:** Manual Functional Testing
- **Techniques:** Equivalence Partitioning, Boundary Value Analysis, 
Error Guessing
- **Test levels:** System Testing, E2E Testing
- **Test types:** Positive testing, Negative testing

---

## 5. Entry Criteria
- Application is accessible at https://demo.opencart.com
- Test cases are written and reviewed
- Test environment (browser + credentials) is set up

## 6. Exit Criteria
- All planned test cases have been executed
- All critical and high severity bugs have been reported
- Test execution report has been delivered

---

## 7. Test Environment
| Item | Details |
|---|---|
| Application | OpenCart Demo |
| URL | https://demo.opencart.com |
| Browser | Google Chrome (latest) |
| OS | Windows 11 |
| Tools | Jira, GitHub, Chrome DevTools |

---

## 8. Risks & Mitigations
| Risk | Mitigation |
|---|---|
| Demo site may be unstable | Re-test on a different day if unavailable |
| Test data may be reset by site admins | Re-create test data before execution |
| Admin credentials may change | Check OpenCart docs for current credentials |

---

## 9. Test Deliverables
- Test Plan (this document)
- Test Cases (Jira + GitHub)
- Bug Reports (Jira + GitHub)
- Test Execution Report
- Final Quality Metrics

---

## 10. Schedule
| Phase | Activity | Period |
|---|---|---|
| Sprint 1 | Test Plan + Test Cases writing | 24 Apr – 7 May |
| Sprint 2 | Test Execution + Bug Reporting | 8 May – 21 May |
| Sprint 3 | Retesting + Final Report | 22 May – 4 Jun |