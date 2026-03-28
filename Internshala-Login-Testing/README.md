
# Internshala Login Page Testing | Manual Testing 

## Project Overview

This project contains **manual testing of the Internshala login page**, focusing on functionality, input validation, UI consistency, security, and user experience.

The goal was to identify **real-world bugs, edge cases, and usability improvements** using industry-standard QA practices.

## Scope of Testing

The following areas were covered:

* Email & Password validation
* Login functionality (valid/invalid scenarios)
* Google OAuth login flow
* Forgot Password functionality
* Navigation links (Sign up, Logo)
* Password visibility toggle
* Error message behavior
* UI responsiveness (mobile & desktop)
* Security checks (HTTPS, brute-force protection)

## Tools Used

* Jira (test case management & bug tracking)
* Google Sheets (test documentation)
* Google Chrome (browser testing)

## Test Artifacts

### Test Cases

* Total: **26 test cases**
* Covers: Positive, Negative, Boundary, UI, Security, Performance

File:
([Internshala-Login-Testing/Internshala_Login _Page _Testing_Artifacts.xlsx](https://github.com/R1ya-sh/manual-qa-testing-mobile-web-project/blob/fcf2e9578ab833d1816cb51a1c27453358200348/Internshala-Login-Testing/Internshala_Login%20_Page%20_Testing_Artifacts.xlsx))
### Bug Reports

The following key bugs were identified:

1. **Password visibility toggle missing on web (Chrome)**
2. **No CAPTCHA / account lock after multiple failed attempts (Security issue)**
3. **Email validation inconsistency (Signup vs Login)**
4. **No response on long password input (critical UX issue)**

### UX/UI Suggestions

1. **Real-time inline validation (on blur)**

   * Improves error feedback and usability

2. **Consistent text selection behavior in password field**

   * Enhances user interaction consistency

## Key Findings

* Validation inconsistencies across modules
* Poor handling of edge-case inputs (long password)
* Missing security mechanisms (no lockout / CAPTCHA)
* Minor UI inconsistencies across platforms

## Test Artifacts (Sheet)

Excel file:  https://docs.google.com/spreadsheets/d/1t9k7pf8qZdHZxFk9JySX9bhkEe0LTAAIDhDRN92oJHA/edit?usp=sharing

* Test Cases
* Bug Reports
* UX/UI Suggestions

## Jira Project

Access available on request

## Author

Riya Shrotriya
