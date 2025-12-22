# Question List Generation I/O Specification (EN)

This document defines the input and output specification
for generating question lists using an LLM in QuestionAgent.

The purpose is to generate questions that fill the Web Master Plan Template.

---

## 1. Input

### 1.1 User Information
- User skill level
  - Non-developer / Beginner / Experienced / Developer
- One-line project purpose

### 1.2 Project Information
- Target domain (web, tool, etc.)
- Applied master plan template identifier

### 1.3 Constraints
- Avoid direct technical terminology
- Prefer multiple-choice questions
- Include suggested default values

---

## 2. Output

Each generated question includes:

- Question text
- Question type (multiple choice / free text)
- Target template field path
- Default or recommended value

---

## 3. Question Design Principles

- One question fills one template field
- One clear intent per question
- Provide choices when user knowledge is uncertain

---

## 4. Usage Flow

1. Extract required fields from the template
2. Adjust question difficulty based on user level
3. Generate question list
4. Collect user responses
5. Map responses to template fields
