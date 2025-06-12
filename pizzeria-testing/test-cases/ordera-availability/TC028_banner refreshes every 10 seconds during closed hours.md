### Test Case ID: TC028  
**Target Description**: Verify banner refreshes every 10 seconds during closed hours  
**Suite**: Ordering Time Restrictions  
**Type**: Functional / Timing  
**Priority**: High  
---

#### Pre-conditions:
1. The user is on any page where the banner should appear (e.g. Homepage: https://simply33food.com/en).  
2. Current system time: Friday 20:00 (closed hours).

---

#### Steps to Execute:

| Step | Action | Expected Result | Pass | Fail | Bug Report ID |
|------|--------|------------------|------|------|----------------|
| 1 | Observe banner appearance | Banner with message "The restaurant is currently closed" appears automatically |      |      |                |
| 2 | Keep the page open and observe | Banner refreshes automatically every 10 seconds (re-appears if manually closed) while the restaurant remains closed |      |      |                |

---

#### Notes:
- Working hours: Mo-Thu 16:00-0:00 | Fri 11:00-18:30 | Sat 19:00-2:00 | Sun 12:00-0:00

**Executor**: Petro Shutiak  
**Date**: 12.06.2025  
