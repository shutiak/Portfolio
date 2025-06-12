### Test Case ID: TC028  
**Target Description**: Successful password update after reset  
**Suite**: Registration and Login  
**Type**: Functional  
**Priority**: High  
---

#### Pre-conditions:
1. The user has requested a password reset via https://simply33food.com/en/my-account/lost-password/  
2. The password reset email with valid reset link was received.  
3. The password reset page is opened via the valid link from email.  

---

#### Steps to Execute:

| Step | Action | Expected Result | Pass | Fail | Bug Report ID |
|------|--------|------------------|------|------|----------------|
| 1 | Enter new password:<br>• **New password**: "NewStrongPass123!"<br>• **Confirm new password**: "NewStrongPass123!" | Both fields accept the input and passwords match |      |      |                |
| 2 | Click "Save" or "Reset Password" button | Password is successfully updated; confirmation message is displayed (e.g. "Your password has been reset.") |      |      |                |
| 3 | Attempt to login using the new password | Login is successful with updated credentials |      |      |
