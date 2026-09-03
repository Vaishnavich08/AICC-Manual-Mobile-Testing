# AICC (All India Casting Connect) – Manual & Mobile Testing

## 📌 Project Overview

**AICC (All India Casting Connect)** is a casting platform that connects artists with casting directors.

Artists can create professional profiles, showcase their talents, discover auditions, and apply for suitable opportunities. Casting directors can post auditions, browse artist profiles, review applications, shortlist suitable candidates, and select talent for their projects.

This project showcases my **Manual Testing and Android Mobile Application Testing** work on the AICC application.

---

## 👩‍💻 My Role

**Software Test Engineer – Manual & Mobile Testing**

### Responsibilities

- Designed and documented functional test cases.
- Performed manual testing of the Android application.
- Tested positive and negative scenarios.
- Performed smoke and regression testing.
- Tested UI elements, validations, navigation, and user workflows.
- Tested profile creation and profile editing functionality.
- Tested audition creation and audition application flows.
- Tested photo/video upload functionality.
- Tested social interactions such as likes, comments, and follow/unfollow.
- Tested location-based filtering.
- Tested direct messaging functionality.
- Identified, documented, and tracked defects.
- Performed defect re-testing after fixes.
- Maintained test execution and test summary documentation.

---

## 🧪 Testing Scope

| Module | Coverage |
|---|---|
| Audience Signup | Registration, validations, mobile number, email, location |
| Artist Signup | Registration, profile picture, resume, validations |
| Login & Logout | Authentication, invalid credentials, logout |
| Profile Management | View, edit, media, validation, persistence |
| Audition Management | Create, view, apply, validations |
| Posts & Media | Photo/video posts, likes, comments |
| Follow & Location | Follow/unfollow and location filtering |
| Direct Messaging | Conversations and message handling |
| Mobile Testing | Android UI, navigation, keyboard, media and stability |

---

## 🔍 Testing Types

- Functional Testing
- UI Testing
- Manual Testing
- Mobile Application Testing
- Smoke Testing
- Regression Testing
- Positive Testing
- Negative Testing
- Validation Testing
- Retesting

---

## 📊 Test Case Summary

The portfolio contains **143 documented test cases** across the major application modules.

| Metric | Count |
|---|---:|
| Total Test Cases | 143 |
| Representative Pass | 136 |
| Representative Fail | 7 |
| Blocked | 0 |
| Defects Logged | 24 |
| Defects Resolved | 23 |
| Defects Open | 1 |
| Retesting Passed | 23 |
| Retesting Failed | 1 |

> **Note:** The test execution numbers are portfolio/representative execution data based on the documented test cases and available defect history. They should not be interpreted as a claim that all 143 test cases were freshly executed end-to-end.

---

## 🐞 Defect Summary

During testing, **24 issues** were documented.

### Priority Distribution

| Priority | Count |
|---|---:|
| High | 9 |
| Medium | 12 |
| Low | 3 |
| **Total** | **24** |

### Defect Status

| Status | Count |
|---|---:|
| Resolved | 23 |
| Open | 1 |
| **Total** | **24** |

### Examples of Defects Identified

- USA country selection displayed India-related states and cities.
- Duplicate profiles could be created using the same mobile number.
- Invalid mobile number lengths were accepted.
- Password field was missing from Audience Signup.
- Deleted resume/profile picture was still displayed after account creation.
- Resume could appear as the profile picture.
- Profile picture and resume uploads failed during artist profile creation.
- Mandatory fields accepted whitespace-only values.
- Invalid audition date values were accepted.
- Audition pay accepted non-numeric values.
- Profile picture could not be updated through Edit Profile.
- Follow status was not retained after profile refresh.
- Post timestamp was not updated correctly.
- Like status was not retained when navigating back to the Home feed.

---

## 📁 Project Documentation

The repository contains:

```text
AICC-Manual-Mobile-Testing/
│
├── README.md
│
├── Test-Documentation/
│   └── AICC_Test_Cases.xlsx
│
├── Test-Evidence/
│   ├── Signup/
│   ├── Login/
│   ├── Profile/
│   ├── Auditions/
│   └── Posts/
│
└── Project-Summary/
    └── Test-Summary.md
```

### Excel Test Documentation

The Excel workbook contains:

- Project Overview
- Audience Signup Test Cases
- Artist Signup Test Cases
- Login & Logout Test Cases
- Profile Management Test Cases
- Audition Management Test Cases
- Posts & Media Test Cases
- Follow & Location Test Cases
- Direct Messaging Test Cases
- Mobile Testing Test Cases
- Test Execution Summary
- Test Summary Report
- Bug Report
- Bug Summary
- Execution Note

---

## 🛠️ Tools & Technologies

- **Application:** Android
- **Testing:** Manual Testing, Mobile Testing
- **Documentation:** Microsoft Excel
- **API Testing:** Postman
- **Database:** SQL / MySQL
- **Version Control:** Git / GitHub
- **Automation Skills:** Selenium WebDriver with Python, PyTest, POM

> Selenium/PyTest automation was not used to test the AICC application in this portfolio. Automation skills are demonstrated separately through automation projects.

---

## 🔄 Testing Approach

### 1. Requirement Understanding
Reviewed the available application functionality and identified the major user workflows.

### 2. Test Scenario Identification
Identified positive, negative, validation, UI, navigation, and persistence scenarios.

### 3. Test Case Design
Created structured test cases containing:

- Test Case ID
- Test Scenario
- Preconditions
- Test Steps
- Test Data
- Expected Result
- Actual Result
- Status
- Priority
- Remarks

### 4. Defect Reporting
For failed scenarios, defects were documented with:

- Defect ID
- Module/Page
- Description
- Expected Result
- Actual Result
- Priority
- Assignee
- Resolution
- Retesting Status

### 5. Retesting
After fixes, reported defects were re-tested and the results were tracked.

---

## 📱 Mobile Testing

Testing was focused on the **Android mobile application**.

Areas covered included:

- Application installation and launch
- Screen navigation
- Touch interactions
- Text fields and keyboard behavior
- Scrolling
- Back navigation
- Media upload
- Application stability
- Minimize/reopen behavior
- Network interruption scenarios
- Normal user workflow stability

The exact Android device model and OS version are not included because they were not recorded in the project documentation.

---

## 🎯 Key Learning Outcomes

Through this project, I gained practical experience in:

- Designing real-world test scenarios.
- Writing detailed test cases.
- Identifying functional and validation defects.
- Testing mobile application workflows.
- Understanding defect lifecycle and re-testing.
- Testing user-role based functionality.
- Testing data persistence and state management.
- Performing regression testing after fixes.
- Preparing professional QA documentation.

---

## 📌 Project Outcome

The project demonstrates practical experience in **Manual Testing, Android Mobile Testing, Functional Testing, Test Case Design, Defect Reporting, Retesting, Smoke Testing, and Regression Testing**.

A total of **24 defects** were documented from the available testing/defect history, with **23 defects resolved and passed during re-testing**, while **1 low-priority issue remained open**.

---

## 👤 Author

**Hari Vaishnavi Chimirala**

**Software Test Engineer | Manual Testing | Selenium Python | PyTest | API Testing | SQL**

