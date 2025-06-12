### Test Case ID: TC031  
**Target Description**: Verify that banner appears immediately after restaurant closing time  
**Suite**: Ordering Time Restrictions  
**Type**: Functional / Timing  
**Priority**: High  
---

#### Pre-conditions:
1. The user is on any page where the banner should appear (e.g. Homepage: https://simply33food.com/en).  
2. Current system time: few minutes before closing (e.g. Friday 18:29).  
3. Restaurant is still open, banner is not displayed.

---

#### Steps to Execute:

| Step | Action | Expected Result | Pass | Fail | Bug Report ID |
|------|--------|------------------|------|------|----------------|
| 1 | Observe the page while approaching closing time | No banner is displayed while the restaurant is open |      |      |                |
| 2 | Wait until closing time is reached (e.g. 18:30) | Banner appears immediately after restaurant closes, blocking interaction with the page |      |      |                |

---

#### Notes:
- Working hours: Mo-Thu 16:00-0:00 | Fri 11:00-18:30 | Sat 19:00-2:00 | Sun 12:00-0:00

**Executor**: Petro Shutiak  
**Date**: 12.06.2025  
