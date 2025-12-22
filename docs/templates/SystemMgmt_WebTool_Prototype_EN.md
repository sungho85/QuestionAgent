## [English] System Management–Centered Internal Web Tool Prototype

### 1. Purpose
The goal of this stage is to generate a development specification (master plan)  
for an internal system management web tool used by administrators.

Target capabilities include:
- Authentication
- Admin-only pages
- CRUD operations
- System configuration
- Logs and status monitoring

This represents the minimum realistic internal tool.

### 2. Reference Project Usage
The rendering script web server is used only as a structural reference.

Features are extracted from:
- Page structure
- Permission structure
- Data structure
- Operational structure

### 3. Core Components

#### 1) Account and Permissions
- User accounts
- Admin vs user roles
- Policy-level authentication definition

#### 2) Core Data (CRUD)
- At least one core entity
- List / detail / edit / delete views

#### 3) Configuration Management
- Key / description / value structure
- Admin-only editing

#### 4) Logs and Monitoring
- Execution or event logs
- Admin access

#### 5) Common UI
- Top bar / side navigation
- Table-based layout

### 4. Master Plan Template Sections
1. Project Overview  
2. Feature Scope  
3. Page Structure  
4. Data Structure  
5. Operational Policies  
6. Development Execution Plan (Codex)

### 5. Connection to Question Generation
QuestionAgent asks an LLM to generate questions to fill this template,  
avoiding technical terms and mapping each question to a template field.
