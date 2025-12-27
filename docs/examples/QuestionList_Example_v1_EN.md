# Question List Example v1 (EN)
## Target: SystemMgmt_WebTool_Sample_v1

This document is a reference example of a question list that QuestionAgent should generate via an LLM.
It is not intended for direct user use, but for validating question quality and template mapping.

---

## A. Project Overview

### Q1
- Intent: Identify project purpose
- Target Field: Project Overview > Purpose
- Question Type: Free text
- Question:
  What would you like to manage with this program? Please describe in one sentence.

### Q2
- Intent: Identify main users
- Target Field: Project Overview > Users
- Question Type: Multiple choice
- Question:
  Who will mainly use this program?
  - Administrators only
  - Administrators and internal staff
  - Not decided yet

### Q3
- Intent: Estimate user scale
- Target Field: Project Overview > User count
- Question Type: Multiple choice
- Question:
  Approximately how many people will use this program?
  - 1–5
  - 6–20
  - 21+
  - Not sure

---

## B. Authentication and Permissions

### Q4
- Intent: Login requirement
- Target Field: Feature Scope > Authentication
- Question Type: Multiple choice
- Question:
  Does this program require user login?
  - Yes
  - No

### Q5
- Intent: Admin-only features
- Target Field: Feature Scope > Admin-only features
- Question Type: Multiple choice
- Question:
  Are there features or pages only administrators can access?
  - Yes
  - No

---

## C. Core Managed Entity (CRUD)

### Q6
- Intent: Define managed entity
- Target Field: Feature Scope > Managed Entity
- Question Type: Free text
- Question:
  What is the most important type of information you want to manage?

### Q7
- Intent: Describe managed entity
- Target Field: Feature Scope > Entity description
- Question Type: Free text
- Question:
  What kind of information will be managed with this entity?

### Q8
- Intent: Select required functions
- Target Field: Feature Scope > CRUD functions
- Question Type: Multiple choice (multiple)
- Question:
  Which functions are required?
  - List
  - Detail view
  - Create
  - Update
  - Delete

---

## D. System Configuration

### Q9
- Intent: Configuration screen requirement
- Target Field: Feature Scope > System configuration
- Question Type: Multiple choice
- Question:
  Do you need a configuration screen that only administrators can change?
  - Yes
  - No

### Q10
- Intent: Identify configuration content
- Target Field: System Configuration > Examples
- Question Type: Free text
- Question:
  If yes, what kind of settings would you like to change?

---

## E. Logs and Records

### Q11
- Intent: Logging requirement
- Target Field: Feature Scope > Logging
- Question Type: Multiple choice
- Question:
  Do you need to keep records of program usage?
  - Yes
  - No

### Q12
- Intent: Identify log types
- Target Field: Logging > Log types
- Question Type: Multiple choice (multiple)
- Question:
  What kind of records should be kept?
  - Access logs
  - Action logs
  - Change history
  - Not sure

---

## F. Operational Policies

### Q13
- Intent: Default admin account
- Target Field: Operational Policies > Admin account
- Question Type: Multiple choice
- Question:
  Should an administrator account be created automatically at first launch?
  - Automatically create
  - Create manually

### Q14
- Intent: Access restriction
- Target Field: Operational Policies > Access restriction
- Question Type: Multiple choice
- Question:
  Are there pages restricted to administrators only?
  - Yes
  - No
  - Not sure

---

## G. Additional Requirements

### Q15
- Intent: Additional requests
- Target Field: Notes
- Question Type: Free text
- Question:
  Are there any additional features you would like to have?
