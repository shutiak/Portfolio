# Pairwise Testing Checklist – Registration, Login & Password Reset (Desktop & Mobile)

This checklist covers core authentication and account recovery flows across key device/browser combinations using pairwise testing.

## Test Scope:
- Validate that all forms (registration, login, password reset) work correctly on multiple platforms.
- Focus: layout, form visibility, field accessibility, validation messages, successful account actions, confirmation screens.

---

## Test Combinations

| # | Device    | Browser | Scenario                                                                 | Status | Bug Report ID | Notes |
|---|-----------|---------|--------------------------------------------------------------------------|--------|----------------|-------|
| 1 | Laptop    | Chrome  | Register new user → Successful login → Logout → Request password reset  |        |                |       |
| 2 | Laptop    | Edge    | Register with invalid email → Login with valid credentials               |        |                |       |
| 3 | iPad 10.2 | Chrome  | Landscape view → Register valid user → Password reset success            |        |                |       |
| 4 | iPhone 14 | Edge    | Mobile view → Login with invalid password → Attempt password reset       |        |                |       |

---

## Notes:

- Use the following sample data for consistency:

### Registration data:
- Username: PetroQA
- Email: petroshutiak@gmail.com
- Password: StrongPass123!

### Password Reset:
- Registered email: petroshutiak@gmail.com

- Validation messages must be checked for:
  - Invalid email format
  - Existing email during registration
  - Empty fields
  - Incorrect credentials during login
  - Password reset with unregistered email

- Ensure responsive layout and proper behavior across devices.

---

**Created by**: Petro Shutiak  
**Date**: 12 June 2025
