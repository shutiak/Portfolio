**Test Case ID**: TC002  
**Title**: Input valid amount as monthly income during first launch  
**Type**: Functional  
**Priority**: High  

---

#### Pre-conditions:

1. The user has successfully navigated from the "Get Started" screen to the monthly income input screen.  
2. The screen displays an explanatory text and an input field for the amount.  

---

#### Steps to Execute:

| Step | Action | Expected Result | Pass | Fail | Bug Report ID |
|------|--------|------------------|------|------|----------------|
| 1 | Enter `40000` into the "Income" field | 1. The entered value `40000` is displayed in the "Income" field. <br> 2. The "Next" button at the bottom of the screen remains inactive. |      |      |                |
| 2 | Tap the "Select" button | A modal window appears with a search field and a list of currencies. |      |      |                |
| 3 | Select the currency "Czech Koruna" | 1. The modal window closes automatically. <br> 2. The "Select" button is replaced by the currency symbol "Kč" on the screen. |      |      |                |
| 4 | Tap the "Next" button | 1. The "Next" button becomes active. <br> 2. The user is navigated to the expense setup screen. |      |      |                |

---

**Executor**: Petro Shutiak  
**Date**: 20.6.2025  
