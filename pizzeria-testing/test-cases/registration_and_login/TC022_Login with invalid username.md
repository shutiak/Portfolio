### Test Case ID: TC022  
**Target Description**: Login with invalid username  
**Suite**: Registration and Login  
**Type**: Negative / Validation  
**Priority**: High  
---

#### Pre-conditions:
1. The Log In page is opened: https://simply33food.com/en/my-account/  
2. A valid user account exists with credentials:<br>
   - Username: "PetroQA"<br>
   - Email: "petroshutiak@gmail.com"<br>
   - Password: "StrongPass123!"  

---

#### Steps to Execute:

| Step | Action | Expected Result | Pass | Fail | Bug Report ID |
|------|--------|------------------|------|------|----------------|
| 1 | Enter login data:<br>• **Username or email address**: "WrongUser123"<br>• **Password**: "StrongPass123!" | The system accepts the input format but does not recognize the user account |      |      |                |
| 2 | Click "Log In" button | An error message is displayed indicating that the username or password is incorrect; user is not logged in |      |      |                |

---

**Executor**: Petro Shutiak  
**Date**: 12.06.2025  
