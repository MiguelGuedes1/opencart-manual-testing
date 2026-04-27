# Test Cases Summary — OpenCart Manual Testing

| TC ID | Summary | Epic | Type | Priority | Status |
|---|---|---|---|---|---|
| TC-001 | Register with valid data | User Registration & Login | Positive | High | PASSED |
| TC-002 | Register with existing email | User Registration & Login | Negative | High | PASSED |
| TC-003 | Register with invalid email format | User Registration & Login | Negative | Medium | PASSED |
| TC-004 | Register with empty required fields | User Registration & Login | Negative | Medium | 
| TC-005 | Login with valid credentials | User Registration & Login | Positive | High | PASSED |
| TC-006 | Login with invalid password | User Registration & Login | Negative | High | PASSED |
| TC-007 | Login with unregistered email | User Registration & Login | Negative | Medium | PASSED |
| TC-008 | Logout successfully | User Registration & Login | Positive | Medium | PASSED |
| TC-009 | Add product to cart | Shopping Cart | Positive | High | PASSED |
| TC-010 | Remove product from cart | Shopping Cart | Positive | High | PASSED |
| TC-011 | Update product quantity in cart | Shopping Cart | Positive | Medium | FAILED |
| TC-012 | Cart persists after login | Shopping Cart | Positive | Medium | PASSED |
| TC-013 | Search existing product | Product Search & Navigation | Positive | High | PASSED |
| TC-014 | Search non-existing product | Product Search & Navigation | Negative | Medium | PASSED |
| TC-015 | Search with empty field | Product Search & Navigation | Negative | Medium | PASSED |
| TC-016 | Complete checkout with valid data | Checkout & Payment | Positive | Highest | FAILED |
| TC-017 | Checkout without being logged in | Checkout & Payment | Negative | High | PASSED |
| TC-018 | Checkout with empty address fields | Checkout & Payment | Negative | High | PASSED |
| TC-019 | Admin login with valid credentials | Admin Panel | Positive | High | PASSED |
| TC-020 | Admin login with invalid credentials | Admin Panel | Negative | Medium | PASSED |

---

## Summary Metrics

| Total | Passed | Failed | Blocked |
|---|---|---|---|
| 20 | 18 | 2 | 0 |

**Pass Rate: 90%**

## Defects Found

| Bug ID | Summary | Severity | Status |
|---|---|---|---|
| BUG-001 | Cart subtotal displays incorrect amount after quantity update | Major | Open |
| BUG-002 | Pre-order product added to cart without stock warning on product page | Minor | Open |