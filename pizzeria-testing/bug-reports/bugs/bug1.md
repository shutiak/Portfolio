# Bug Report

## Basic Information

| Field       | Value          |
|-------------|----------------|
| **ID**      | #1             |
| **Reporter**| Petro Shutiak  |
| **Assignee**| <dev's team>   |
| **Status**  | New            |
| **Type**    | UI/UX          |
| **Severity**| Trivial        |
| **Priority**| Lowest         |

---

## Environment

| Parameter           | Value                                        |
|---------------------|----------------------------------------------|
| OS                  | Windows 11 Home (26100.3775)                 |
| Browser             | Google Chrome 135.0.7049.96 (64-bit, Official Build) |
| Display resolution  | 1920 x 1080                                  |
| Browser zoom level  | 100%                                         |

---

## Summary

**Modal window cannot be scrolled up or down when opened, the Close (X) button becomes inaccessible at 100% zoom.**

---

## Description

When a modal window (e.g. with film _"Sinners"_) is opened at 100% browser zoom, the Close (X) button in the top-right corner may be hidden due to screen layout.  
The user is unable to scroll up to access the button, which prevents closing the modal through UI.

---

## Pre-conditions

1. The Filmoteka Home page is opened  
2. A modal window is opened (e.g. for film _"Sinners"_)

---

## Steps to Reproduce

1. Open any film modal from the Home page  
2. Try to locate the Close (X) button in the top-right corner  
3. Attempt to scroll within the modal window  
4. Observe whether the button is accessible  

---

## Actual Result

The Close (X) button is not visible and the user cannot scroll the modal window to reach it.

---

## Expected Result

The Close (X) button should always remain visible,  
**or** the user should be able to scroll the modal content vertically to access it.

---

## Attachments

- `cross.png`

---

## Additional Info

N/A
