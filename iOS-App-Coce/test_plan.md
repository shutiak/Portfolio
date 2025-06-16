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

The purpose of testing is to verify the correct functionality, usability, data handling, and balance calculations of the Simple Budget Tracking App on iPhone 14 (iOS 18.5). 

The application is focused on allowing users to:

- Add income and define mandatory expenses.
- Automatically calculate remaining disposable balance after mandatory expenses.
- Monitor how much of mandatory expenses are still unpaid during the month.
- Store all data locally on the device without requiring user accounts or cloud sync.
- Fully erase all user data on request.

The application is intentionally simple, targeted at solving a very specific budgeting scenario with minimal complexity.

## 6. Features to be Tested

| Feature | Description |
| ------- | ----------- |
| Installation | Verify installation via TestFlight on iOS |
| First Launch | Verify correct behavior on initial startup |
| Income Entry | Adding, editing, deleting income records |
| Mandatory Expenses Entry | Adding, editing, deleting mandatory expenses |
| Balance Calculation | Correct calculation of remaining balance after all expenses |
| Monthly Progress | Display remaining unpaid mandatory expenses for current month |
| Data Deletion | Erase all stored data through user interface |
| Data Persistence | Verify data is stored locally and remains after app restarts |
| Privacy | Verify privacy policy availability and data storage scope |
| UI/UX | Verify clarity, responsiveness, and usability on iPhone 14 |
| Input Validation | Verify handling of invalid input values (negative, non-numeric, empty fields) |

## 7. Features Not to be Tested

- User authentication (not implemented)
- Cloud synchronization (not implemented)
- Multi-device data access (not implemented)
- Any kind of analytics or integrations (not implemented)

## 8. Test Environment

| Device | iOS Version | Installation Source |
| ------ | ----------- | ------------------- |
| iPhone 14 | iOS 18.5 | TestFlight |

Notes:

- All tests will be performed on real device.
- No server or backend involved.
- All data fully local.

## 9. Test Types

- Functional Testing
- UI Testing
- Usability Testing
- Negative Testing
- Installation Testing
- Smoke Testing
- Data Persistence Testing
- Privacy & Data Deletion Testing

## 10. Test Deliverables

- Test Case Suite (separate document)
- Test Execution Logs
- Defect Reports (if any)
- Final Test Summary Report

## 11. Acceptance Criteria

- All critical functional tests pass successfully.
- Balance calculations are always accurate.
- No data loss or corruption occurs during normal app usage.
- App does not crash or freeze.
- User data is fully deleted when requested.
- Privacy policy is accessible.
- Application works smoothly on target iOS device.

## 12. Risks and Assumptions

- No network or cloud dependencies exist.
- TestFlight build is stable and production-like.
- Device storage is sufficient for testing.
- App complexity intentionally limited (minimal feature set).
