### Test Case ID: TC018  
**Target Description**: Registration with leading/trailing spaces in input fields  
**Suite**: Registration and Login  
**Type**: Negative / Validation  
**Priority**: Medium  
---

#### Pre-conditions:
1. The Log In / Registration page is opened: https://simply33food.com/en/my-account/  
2. Registration form is available and functional  

---

#### Steps to Execute:

| Step | Action | Expected Result | Pass | Fail | Bug Report ID |
|------|--------|------------------|------|------|----------------|
| 1 | Enter registration data with leading/trailing spaces:<br>• Username: "  PetroQA  "<br>• Email address: "  petroshutiak@gmail.com  "<br>• Password: "  StrongPass123!  " | The system automatically trims leading and trailing spaces or displays validation errors if trimming is not implemented |      |      |                |
| 2 | Click "Register" button | User account is successfully created if spaces are trimmed; otherwise, appropriate validation errors are displayed |      |      |                |

---

**Executor**: Petro Shutiak  
**Date**: 12.06.2025  
