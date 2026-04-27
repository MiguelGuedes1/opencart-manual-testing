# 🛒 OpenCart Manual Testing Project

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Jira](https://img.shields.io/badge/Management-Jira-blue)
![Type](https://img.shields.io/badge/Type-Manual%20Testing-green)
![Pass Rate](https://img.shields.io/badge/Pass%20Rate-90%25-brightgreen)

## 📌 Project Overview

Manual testing project for the **OpenCart** demo e-commerce platform.  
The goal is to validate the core functional flows of the application,  
document defects, and deliver a final quality report.

🔗 **Application under test:** https://demo.opencart.com  
🔗 **Jira Board:** [OCT Board](https://miguelsilvaguedes1.atlassian.net/jira/software/c/projects/OCT/boards/135/backlog?selectedIssue=OCT-31&atlOrigin=eyJpIjoiYWFiZGI5YWI0NjhmNDA1ODlkMGQzZWNiMTVjNjgyMDkiLCJwIjoiaiJ9)

---

## 📊 Test Execution Summary

| Total TCs | Passed | Failed | Blocked |
|---|---|---|---|
| 20 | 18 | 2 | 0 |

**Pass Rate: 90%** | **Defects Found: 2** | **Execution Period:** 26 Apr – 4 Jun 2026

---

## 🧪 Test Scope

| Module | Type | Pass Rate |
|---|---|---|
| User Registration & Login | Functional, Negative, Boundary | 100% |
| Product Search & Navigation | Functional, Negative | 100% |
| Shopping Cart | Functional, Negative | 75% |
| Checkout & Payment | E2E, Functional, Negative | 67% |
| Admin Panel | Functional, Negative | 100% |

---

## 🐛 Defects Found

| Bug ID | Summary | Severity | Status |
|---|---|---|---|
| BUG-001 | Cart subtotal displays incorrect amount after quantity update | Major | Open |
| BUG-002 | Pre-order product added to cart without stock warning on product page | Minor | Open |

---

## 🗂️ Project Structure
opencart-manual-testing/
├── test-plan/         → Test Plan document
├── test-cases/        → Test cases summary
├── bug-reports/       → Defect reports
├── test-execution/    → Execution results and final report
└── screenshots/       → Evidence and bug screenshots

---

## 🛠️ Tools & Technologies

- **Test Management:** Jira (Scrum) + Xray
- **Documentation:** GitHub + Markdown
- **Browser:** Chrome + DevTools
- **Screenshots:** Snipping Tool
- **Version Control:** Git + GitHub

---

## 📁 Sprints

| Sprint | Goal | TCs | Pass Rate | Period |
|---|---|---|---|---|
| Sprint 1 | Authentication flows + Test Plan | 8 | 100% | 26 Apr – 7 May |
| Sprint 2 | Cart, Search & Checkout flows | 10 | 80% | 8 May – 21 May |
| Sprint 3 | Admin Panel + Retesting + Final Report | 2 | 100% | 22 May – 4 Jun |

---

## 👤 Author

**Miguel Guedes**  
QA Tester  
[LinkedIn](https://www.linkedin.com/in/miguel-guedes1/) · [GitHub](https://github.com/MiguelGuedes1)