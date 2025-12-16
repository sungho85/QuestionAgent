# QuestionAgent Web Prototype – Goal Definition

## 1. Objective of the Prototype

The goal of this QuestionAgent prototype is to enable non-developers  
to create a small internal-use web application through conversational input only.

This prototype must generate a **development specification and master plan**  
that allows Codex to automatically create a functional web application including:

- Framework setup  
- Local database  
- Login functionality  
- CRUD pages

This goes beyond simple static 1–2 page websites.  
The target output is a **small internal business tool** such as:

- Login page  
- List page  
- Detail page  
- Create/Edit/Delete pages  

---

## 2. Expected Output

The prototype should produce:

1. Framework-based project structure  
2. Login page  
3. List page  
4. Detail page  
5. Edit/Create/Delete pages  
6. Template-based UI (Bootstrap or similar)  
7. Local DB (e.g., SQLite) for persistent storage

The user provides natural language requirements only;  
Codex executes the entire development plan automatically.

---

## 3. Required Features

### 3.1 User-friendly questioning system
Non-developers cannot answer questions like:

- What DB do you want?  
- Which framework should we use?  
- What template do you prefer?

Instead, the questions must be purpose-oriented:

Examples:
- “Where will this tool be used?”  
- “How many people will use it?”  
- “Is login required?”  
- “How long should the data be stored?”

---

### 3.2 LLM-based question generation

The system must convert internal technical requirements  
(DB, framework, authentication, routing, templates, etc.)  
into **easy, user-friendly questions**, then map the answers back into technical specifications.

Required internal structure:

1) List of technical requirements  
2) List of user-friendly questions  
3) Mapping rules from user answers → technical spec  
4) Generation of:
   - DB schema  
   - Page structure  
   - Routing  
   - Template layout  
   - Codex prompts for code generation  

---

## 4. Master Plan Requirements

When the master plan is provided to Codex, the following must occur automatically:

1. Project creation  
2. Framework installation and setup  
3. Step-by-step plan generation  
4. Prompt generation  
5. Code generation (with bilingual comments: Korean + English)  
6. Code validation per step  
7. Result and report saving  

The user only chats and observes;  
Codex handles all development tasks.

---

## 5. Required Guides

### 5.1 Environment Setup Guide
- How to install VS Code  
- How to install Codex or AntiGravity  
- Required extensions and how to run the project

---

### 5.2 Debugging Guide
- How to copy error messages and ask Codex to fix them  
- Basic explanation of web project structure and execution steps  

---

## 6. Core Goals Summary

- Non-developers must be able to create CRUD-based web tools  
- Technical choices (DB, framework, template) are not asked directly  
- LLM generates user-friendly questions and converts answers to specs  
- Codex executes the entire development workflow  
- QuestionAgent handles specification, planning, and question logic  
