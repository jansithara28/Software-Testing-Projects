# Project Documentation — E-commerce Website Manual Testing

## 1. Project Overview
This is a manual testing practice project for an e-commerce website. The goal is to design structured test scenarios and test cases for key customer journeys, prepare test data, record reproducible defects, and summarize execution results.

## 2. Objective
- Validate key user workflows: login, search, product details, cart, and checkout.
- Practice positive, negative, boundary, UI, calculation, and navigation testing.
- Maintain clear, traceable test documentation suitable for a beginner testing portfolio.

## 3. Scope

### In scope
- Login validation
- Product search and listing
- Product details
- Add, update, and remove cart items
- Cart calculations
- Checkout form validation
- Order review and confirmation

### Out of scope
- Payment gateway transactions using real payment details
- Security penetration testing
- Load and performance testing
- Compatibility across every browser/device
- Real customer data or real purchases

## 4. Test Approach
1. Select a practice e-commerce application or a locally hosted demo.
2. Review the available functionality and adjust assumptions to match the application.
3. Prepare test data using fictional values.
4. Execute test cases manually.
5. Record actual results and mark each case Pass, Fail, Blocked, or Not Run.
6. Log only defects that can be reproduced and supported with evidence.
7. Summarize execution results and known limitations.

## 5. Entry Criteria
- Practice application is accessible.
- Test environment and browser are available.
- Relevant test data is prepared.
- Core application workflows are understood.

## 6. Exit Criteria
- All planned test cases have an execution status.
- Failed cases have corresponding defect records where appropriate.
- Blocked and not-run cases are explained.
- Execution summary is updated.

## 7. Test Environment
Fill in before execution:
- Application URL:
- Application/build version:
- Operating system:
- Browser and version:
- Screen resolution/device:
- Execution date:
- Tester:

## 8. Deliverables
- Test scenarios
- 40 test cases
- Test data
- Bug report log
- Test execution report
- README

## 9. Assumptions and Notes
- Product names, prices, accounts, and addresses in the workbook are fictional examples.
- Example credentials use the reserved `example.test` domain and are not real accounts.
- Adapt field names, expected behavior, and test data to the selected practice application.
- The bug report entries are illustrative examples only. They are marked **Not Verified** and must not be presented as defects actually found.
- The execution report correctly starts with all test cases marked **Not Run**. Update it only after actual testing.

## 10. Risks
- Practice application may change or become unavailable.
- Some checkout features may require account creation or may be disabled.
- Expected behavior can differ by application; update test cases based on observed requirements.
