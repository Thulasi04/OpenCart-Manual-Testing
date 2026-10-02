# OpenCart Manual Testing Project

## Project Overview

This project demonstrates manual testing of an OpenCart E-Commerce application.

The testing focuses on validating the major customer-facing functionalities of the OpenCart storefront, including user authentication, product search, wishlist, shopping cart, checkout, and order history.

## Application Under Test

**OpenCart E-Commerce Platform**

## Testing Scope

The following modules were covered during testing:

- User Account & Authentication
- Catalog & Product Discovery
- Shopping Cart
- Wishlist
- Checkout
- Order Processing
- My Account
- Order History

The project also includes end-to-end validation from registration and product search through cart, checkout, and order history. :chatgpt-content-reference{index="1"}

## Testing Types

- Functional Testing
- Smoke Testing
- Sanity Testing
- Boundary Testing
- End-to-End Testing
- Regression Testing
- Browser Compatibility Testing

## Test Environment

### Browsers

- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari

### Tools

- Postman – API Validation
- JIRA – Defect Tracking
- Git – Version Control

The test plan documents Chrome, Firefox, Edge, Safari, Postman, Git, and JIRA as part of the testing environment and tools. :chatgpt-content-reference{index="2"}

## Project Documents

| File | Description |
|------|-------------|
| `manual_testing.xlsx` | Test scenarios, test cases, execution results and defect details |
| `test_plan_&_test_report.pdf` | Test plan, test strategy, schedule and final test report |

## Test Execution Summary

| Metric | Count |
|--------|-------|
| Total Test Cases | 20 |
| Executed | 20 |
| Passed | 12 |
| Failed | 8 |

## Defect Summary

| Severity | Count |
|----------|-------|
| Blocker | 2 |
| Critical | 3 |
| Major | 2 |
| Minor | 1 |
| **Total Defects** | **8** |

The test report records 20 executed test cases, with 12 passed and 8 failed. It documents 8 defects across Blocker, Critical, Major, and Minor severity levels. :chatgpt-content-reference{index="3"}

## Defects Identified

The project includes defects related to:

1. User authentication
2. Product search
3. Product detail page
4. Wishlist
5. Shopping cart calculation
6. Checkout / Place Order
7. Order confirmation email
8. Order History

### Defect Examples

| Defect ID | Description | Severity | Status |
|-----------|-------------|----------|--------|
| DEF001 | Login fails with HTTP 500 error | Blocker | Open |
| DEF002 | Search functionality crashes during keyword search | Critical | Open |
| DEF003 | In-Stock badge overlaps product title | Minor | Open |
| DEF004 | Wishlist items are not persisted | Major | Open |
| DEF005 | Cart total does not recalculate after quantity change | Critical | Open |
| DEF006 | Application freezes when Place Order is clicked | Blocker | Open |
| DEF007 | Order confirmation email is not dispatched | Major | Open |
| DEF008 | Order History page returns HTTP 500 error | Critical | Open |

These defects and their statuses are documented in the final test report. :chatgpt-content-reference{index="4"} :chatgpt-content-reference{index="5"}

## Entry Criteria

Testing was planned to begin after:

- Development completion
- Unit testing completion
- Integration testing completion
- QA build deployment
- Test environment setup
- Test data availability
- Test case review and approval

## Exit Criteria

Testing completion criteria included:

- 100% of planned test cases executed
- No open Blocker or Critical defects
- Major defects resolved or formally deferred
- Test Summary Report finalized and accepted :chatgpt-content-reference{index="6"}

## Testing Schedule

The project included activities such as:

- Test Plan Preparation
- Test Scenario & Test Case Preparation
- User Registration & Authentication
- Search & Product Display
- Product Compare & Wishlist
- Shopping Cart Testing
- Checkout Testing
- My Account Testing
- Defect Retesting & Regression
- Final Test Report & GitHub Publication

The documented schedule runs from July 17, 2026 through August 2, 2026. :chatgpt-content-reference{index="7"}

## Risks & Mitigation

Some identified testing risks included:

- Delay in QA build delivery
- Requirement modifications
- Critical functional defects
- QA resource unavailability

Mitigation activities included prioritizing smoke testing, updating affected test cases, performing regression testing, and redistributing testing tasks when required. :chatgpt-content-reference{index="8"}

## Project Deliverables

This project contains:

- Test Plan
- Test Scenarios
- Test Cases
- Test Execution Results
- Defect Report
- Test Summary Report


