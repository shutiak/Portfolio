### Test Case ID: TC023  
**Target Description**: Login with empty fields  
**Suite**: Registration and Login  
**Type**: Negative / Validation  
**Priority**: High  
---

#### Pre-conditions:
1. The Log In page is opened: https://simply33food.com/en/my-account/  

---

#### Steps to Execute:

| Step | Action | Expected Result | Pass | Fail | Bug Report ID |
|------|--------|------------------|------|------|----------------|
| 1 | Leave both fields empty:<br>• **Username or email address**: ""<br>• **Password**: "" | The system detects that required fields are empty and displays validation errors |      |      |                |
| 2 | Click "Log In" button | The form is not submitted; user remains on the login page with validation errors displayed for both fields |      |      |                |

---

**Executor**: Petro Shutiak  
**Date**: 12.06.2025  
