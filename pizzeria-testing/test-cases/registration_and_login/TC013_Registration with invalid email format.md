### Test Case ID: TC013  
**Target Description**: Registration with invalid email format  
**Suite**: Registration  
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
| 1 | Enter registration data:<br>• Username: "PetroQA"<br>• Email address: "petroshutiak#gmail.com"<br>• Password: "StrongPass123!" | The email field detects the invalid email format and displays a validation error |      |      |                |
| 2 | Click "Register" button | The form is not submitted; user remains on the registration page with email validation error displayed |      |      |                |

---

**Executor**: Petro Shutiak  
**Date**: 12.06.2025  
