# QuestionAgent Question-Driven Master Plan Generation Structure (EN)

## 1. Overview
This document defines the **question-driven master plan generation mechanism** used by QuestionAgent, enabling non-developers to design software for any domain (Web, Maya, Console tools, etc.) through natural-language interaction.

## 2. Core Concept
Based on the user’s skill level and requirements, QuestionAgent uses an LLM to:

1. Identify the user's experience level  
2. Combine the domain-specific master plan template with the user’s initial description  
3. Let the LLM generate a complete question list tailored to the user's level  
4. Ask each question and fill the corresponding fields of the master plan  
5. Send the partially completed plan back to the LLM for refinement and completion  
6. Produce a final master plan that Codex or similar engines can execute

This enables non-developers to complete a full program design entirely through conversation.

## 3. Workflow

### Step 1: Initial User Input
- Natural-language explanation of what the user wants to create  
- User experience level (non-developer / beginner / PM / developer)

### Step 2: LLM-Generated Question List
The system sends the master plan template + initial user description to the LLM.  
The LLM returns a question list appropriate for the user's experience level.

### Step 3: Interactive Q&A
Each question is presented to the user, and answers are inserted into the master plan template.

### Step 4: Completion & Refinement
The partially completed plan + all user responses are sent to the LLM again,  
where missing items are filled, inconsistencies resolved, and structure finalized.

### Step 5: Execution by Codex
The final master plan enables Codex to:
- Create the project  
- Generate code  
- Validate functionality  
- Produce reports  

## 4. Advantages
- Domain-independent architecture  
- Adaptive question difficulty based on user level  
- Template-based extensibility (Web, Maya, UE5, etc.)  
- LLM-generated questioning reduces user confusion  
- Automatic master plan validation  

## 5. Summary
This mechanism is the core of QuestionAgent and enables anyone—from non-developers to experts—to design software through natural language.
