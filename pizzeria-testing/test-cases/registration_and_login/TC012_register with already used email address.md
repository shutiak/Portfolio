### Test Case ID: TC012  
**Target Description**: Attempt to register with already used email address  
**Suite**: Registration and Login
**Type**: Negative / Validation  
**Priority**: High  
---

#### Pre-conditions:
1. The Log In / Registration page is opened: https://simply33food.com/en/my-account/  
2. Registration form is available and functional  
3. An account already exists with email address: petroshutiak@gmail.com  

---

#### Steps to Execute:

| Step | Action | Expected Result | Pass | Fail | Bug Report ID |
|------|--------|------------------|------|------|----------------|
| 1 | Enter registration data:<br>• Username: "PetroQA2"<br>• Email address: "petroshutiak@gmail.com"<br>• Password: "StrongPass123!" | The email field is accepted for input |      |      |                |
| 2 | Click "Register" button | An error message is displayed indicating that the email address is already in use; user is not registered |      |      |                |

---

**Executor**: Petro Shutiak  
**Date**: 12.06.2025  
