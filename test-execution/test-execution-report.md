# Test Execution Report — OpenCart Manual Testing

**Project:** OpenCart Manual Testing  
**Version:** 1.0  
**Author:** Miguel Guedes  
**Execution Period:** 26 Apr 2026 – 4 Jun 2026  
**Environment:** Chrome (latest) / Windows 11  
**URL:** https://demo.opencart.com  

---

## Executive Summary

This report presents the results of the manual testing performed 
on the OpenCart demo e-commerce platform. Testing was conducted 
across 3 sprints covering 5 functional modules and 20 test cases.

---

## Test Execution Summary

| Metric | Value |
|---|---|
| Total Test Cases | 20 |
| Passed | 18 |
| Failed | 2 |
| Blocked | 0 |
| Pass Rate | 90% |
| Defects Found | 2 |

---

## Results by Sprint

| Sprint | Period | TCs Executed | Passed | Failed | Pass Rate |
|---|---|---|---|---|---|
| Sprint 1 | 26 Apr – 7 May | 8 | 8 | 0 | 100% |
| Sprint 2 | 8 May – 21 May | 10 | 8 | 2 | 80% |
| Sprint 3 | 22 May – 4 Jun | 2 | 2 | 0 | 100% |

---

## Results by Module

| Module | TCs | Passed | Failed | Pass Rate |
|---|---|---|---|---|
| User Registration & Login | 8 | 8 | 0 | 100% |
| Product Search & Navigation | 3 | 3 | 0 | 100% |
| Shopping Cart | 4 | 3 | 1 | 75% |
| Checkout & Payment | 3 | 2 | 1 | 67% |
| Admin Panel | 2 | 2 | 0 | 100% |

---

## Defects Summary

| Bug ID | Jira | Summary | Severity | Priority | Status |
|---|---|---|---|---|---|
| BUG-001 | OCT-35 | Cart subtotal displays incorrect amount after quantity update | Major | High | Open |
| BUG-002 | OCT-36 | Pre-order product added to cart without stock warning on product page | Minor | High | Open |

---

## Sprint 1 — Authentication
**Goal:** Establish the test foundation by validating all user 
authentication flows.

**Result:** 8/8 PASSED — 100% pass rate. All registration, 
login and logout flows working as expected.

---

## Sprint 2 — Search, Cart & Checkout
**Goal:** Validate the core e-commerce journey across product 
search, shopping cart and checkout flows.

**Result:** 8/10 PASSED — 80% pass rate. 2 defects found:
- BUG-001: Cart subtotal calculation incorrect after quantity update
- BUG-002: Pre-order stock warning missing on product page

---

## Sprint 3 — Admin Panel
**Goal:** Complete test coverage by validating the admin panel.

**Result:** 2/2 PASSED — 100% pass rate. Admin authentication 
working as expected.

---

## Conclusions

The OpenCart platform demonstrates stable functionality across 
the majority of tested flows with a 90% overall pass rate. 
The critical checkout flow (TC-016) failed due to stock 
availability issues in the demo environment, and a calculation 
defect was identified in the shopping cart module.

## Recommendations

- BUG-001 should be prioritised for immediate fix as it affects 
the cart total calculation which is critical for e-commerce.
- BUG-002 should be addressed to improve user experience 
by displaying stock warnings earlier in the purchase flow.