### Test Case ID: TC027  
**Target Description**: Password reset request with non-registered email  
**Suite**: Registration and Login  
**Type**: Negative / Validation  
**Priority**: High  
---

#### Pre-conditions:
1. The "Lost your password?" page is opened: https://simply33food.com/en/my-account/lost-password/  
2. A valid user account exists with credentials:<br>
   - Username: "PetroQA"<br>
   - Email: "petroshutiak@gmail.com"  

---

#### Steps to Execute:

| Step | Action | Expected Result | Pass | Fail | Bug Report ID |
|------|--------|------------------|------|------|----------------|
| 1 | Enter invalid data:<br>• **Username or email address**: "nonexistinguser@gmail.com" | The field accepts the input |      |      |                |
| 2 | Click "Reset password" button | Click "Reset password" button | A confirmation message is displayed: "A confirmation email has been sent." |      |      |                |

---

**Executor**: Petro Shutiak  
**Date**: 12.06.2025  
