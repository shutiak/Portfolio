### Test Case ID: TC024  
**Target Description**: Verify "Remember Me" functionality  
**Suite**: Registration and Login  
**Type**: Functional / Session  
**Priority**: Medium  
---

#### Pre-conditions:
1. The Log In page is opened: https://simply33food.com/en/my-account/  
2. A valid user account exists with credentials:<br>
   - Username: "PetroQA"<br>
   - Email: "petroshutiak@gmail.com"<br>
   - Password: "StrongPass123!"  
3. Browser allows cookies and session storage.  

---

#### Steps to Execute:

| Step | Action | Expected Result | Pass | Fail | Bug Report ID |
|------|--------|------------------|------|------|----------------|
| 1 | Enter valid data:<br>• **Username or email address**: "petroshutiak@gmail.com"<br>• **Password**: "StrongPass123!" | The fields accept the input |      |      |                |
| 2 | Select the checkbox **"Remember me"** | Checkbox is selected successfully |      |      |                |
| 3 | Click "Log In" button | User is successfully logged in and redirected to dashboard |      |      |                |
| 4 | Close and reopen the browser, navigate back to https://simply33food.com/en/my-account/ | User remains logged in  |      |      |                |

---

**Executor**: Petro Shutiak  
**Date**: 12.06.2025  
