# Test Plan: Coco Simple Budget Tracking App

## 1. Project Name
Simple Budget Tracking App

## 2. Test Plan Version
v1.0

## 3. Prepared By
Petr Shutiak

## 4. Date
2025-06-16

## 5. Scope of Testing

The purpose of testing is to verify the correct functionality, usability, stability, and correctness of calculations in the Budget Tracking App on iOS platform (iPhone 14, iOS 18.5). The application allows users to:

- Add income and mandatory expenses
- See remaining balance after mandatory expenses
- Track monthly remaining payments
- Erase all data from the device
- Work fully offline with local data storage

## 6. Features to be Tested

| Feature | Description |
| ------- | ----------- |
| Installation | Verify installation via TestFlight |
| First Launch | Verify first launch behavior |
| Income Management | Adding, editing, deleting income |
| Expense Management | Adding, editing, deleting expenses |
| Balance Calculation | Correct balance after all operations |
| Monthly Progress | Remaining mandatory payments tracking |
| Data Deletion | Full data wipe function |
| Privacy | Local data storage & privacy policy compliance |
| UI/UX | Display correctness, responsiveness |
| Negative Scenarios | Input validations & error handling |

## 7. Features Not to be Tested

- Cloud synchronization (not implemented)
- Multi-device data sharing (not implemented)
- User authentication (not implemented)

## 8. Test Environment

| Device | iOS Version | Platform |
| ------ | ----------- | -------- |
| iPhone 14 | iOS 18.5 | iOS |

Other Environment Notes:

- Local data only
- TestFlight installation

## 9. Test Types

- Functional Testing
- UI/UX Testing
- Usability Testing
- Regression Testing
- Negative Testing
- Smoke Testing
- Installation Testing
- Privacy & Data Persistence Testing

## 10. Test Deliverables

- Test Cases (prepared separately)
- Test Execution Results
- Defect Reports
- Test Summary Report

## 11. Acceptance Criteria

- All functional test cases pass.
- No critical or high priority defects remain open.
- Application performs as expected without crashes.
- All calculations of balances are accurate.

## 12. Risks and Assumptions

- No backend/server dependency.
- Sufficient device storage available.
- TestFlight build is stable.
