### Test Case ID: TC030  
**Target Description**: Verify that banner automatically disappears when restaurant opens  
**Suite**: Ordering Time Restrictions  
**Type**: Functional / Timing  
**Priority**: High  
---

#### Pre-conditions:
1. The user is on any page where the banner should appear (e.g. Homepage: https://simply33food.com/en).  
2. Current system time: few minutes before opening (e.g. Friday 10:59).  
3. Restaurant is currently closed and banner is visible.

---

#### Steps to Execute:

| Step | Action | Expected Result | Pass | Fail | Bug Report ID |
|------|--------|------------------|------|------|----------------|
| 1 | Observe the banner while approaching opening time | The banner remains visible while the restaurant is closed |      |      |                |
| 2 | Wait until opening time is reached (e.g. 11:00) | Banner disappears automatically without manual action; ordering becomes available |      |      |                |

---

#### Notes:
- Working hours: Mo-Thu 16:00-0:00 | Fri 11:00-18:30 | Sat 19:00-2:00 | Sun 12:00-0:00

**Executor**: Petro Shutiak  
**Date**: 12.06.2025  
