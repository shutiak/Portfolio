### Test Case ID: TC016  
**Target Description**: Registration with special characters in name fields  
**Suite**: Registration and Login
**Type**: Negative / Validation  
**Priority**: High  
---

#### Pre-conditions:
1. The Log In / Registration page is opened: https://simply33food.com/en/my-account/  
2. Registration form is available and functional  

---

#### Steps to Execute:

| Step | Action | Expected Result | Pass | Fail | Bug Report ID |
|------|--------|------------------|------|------|----------------|
| 1 | Enter registration data:<br>• Username: "@@@Petro123"<br>• Email address: "petroshutiak@gmail.com"<br>• Password: "StrongPass123!" | The username field detects invalid special characters and displays a validation error (if such validation is implemented) |      |      |                |
| 2 | Click "Register" button | The form is not submitted; user remains on the registration page with validation error displayed for the username field |      |      |                |

---

**Executor**: Petro Shutiak  
**Date**: 12.06.2025  
