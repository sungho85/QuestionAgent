# System Management Web Tool Sample v1 (EN)

## Overview
This document is a sample scenario demonstrating how the Web Master Plan Template v1
can be filled in a real-world context.

The sample assumes an **internal system management web tool used by non-developers**.

---

## 1. Project Overview

### Purpose
Provide an internal management tool that allows administrators to monitor and manage
job requests and their execution status.

### Target Users
- Administrators
- Internal staff

### Environment
- Execution environment: Internal server
- Internet connection: Required

---

## 2. Feature Scope

### Authentication
- Login enabled
- Administrator-only features included

### Core Managed Entity (CRUD)
- Entity name: Job Request
- Description: Manage internal job execution requests
- Functions:
  - List
  - Detail view
  - Create
  - Update
  - Delete

### System Configuration
- Configuration management enabled
- Example settings:
  - Maximum concurrent jobs
  - Default job priority

### Logging
- Logging enabled
- Log types:
  - Access logs
  - Job execution logs
  - Status change history

---

## 3. Page Structure

- Login page
- Dashboard page
- Job request list page
- Job request detail page
- Job request edit page
- System configuration page
- Log viewing page

---

## 4. Data Structure

### User
- ID
- Name
- Role
- Status

### Job Request
- Request ID
- Title
- Description
- Status
- Created time
- Updated time

### Log
- Log ID
- Timestamp
- User
- Event description

---

## 5. Operational Policies

- Default administrator account auto-created
- Configuration and logs restricted to administrators
- Log retention period: 90 days

---

## 6. Development Execution Plan (Summary)

1. Project creation
2. Framework setup
3. Database initialization
4. Authentication and authorization
5. Job request CRUD implementation
6. Admin UI template integration
7. Logging and configuration features
8. Testing and validation
9. Result report generation

---

## Notes
This document is a sample used to validate the template and QuestionAgent workflow.
