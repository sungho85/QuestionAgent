# QuestionAgent

## Translation Notice

I am a Korean developer.  
This README was originally written in Korean and translated into English using GPT.  
Please note that some expressions may sound unnatural.

---

## Overview

QuestionAgent is a question-driven development assistant designed to help non-developers design software through natural language conversation.

This repository currently focuses on documenting the **core ideas, philosophy, and system structure** behind QuestionAgent.  
Implementation and prototypes will be added incrementally.

---

## Why QuestionAgent?

While working on various software projects, I repeatedly encountered the same problem:

Most people can clearly explain what they want to build,  
but they struggle to translate that idea into a form that developers or AI coding tools can directly implement.

At the same time, modern LLMs such as GPT and Codex are already capable of generating large amounts of code —  
but only when given well-structured requirements and plans.

QuestionAgent was conceived to bridge this gap.

Instead of forcing users to understand technical terms, frameworks, or architectures,  
QuestionAgent focuses on asking the right questions and transforming the answers into a structured master plan that can be executed by coding models.

---

## What is QuestionAgent?

QuestionAgent is not just a code generator.

It is a system that:

- Identifies the user's skill level (especially non-developers)
- Uses an LLM to generate appropriate questions
- Gradually fills a structured master plan through conversation
- Produces a development-ready specification that tools like Codex can execute

The core idea is simple:

If we can automate the thinking and questioning process of a software architect,  
non-developers can design real software using only natural language.

---

## Development Approach

The prototype of QuestionAgent will be developed using **GPT / Codex-based "vibe coding"**.

Rather than manually writing large amounts of code, the approach focuses on:

- Designing clear master plans
- Generating step-by-step prompts
- Letting Codex create, validate, and iterate on actual implementations

This repository follows a **documentation-first approach**,  
with code and executable prototypes added later as the design stabilizes.

---

## Current Status

- Vision, mission, and purpose defined
- Prototype goals clarified
- Question-driven master plan generation structure documented
- Implementation is currently a work in progress

---

## Documentation

Key design documents can be found in the `docs/` directory:

- Vision, Mission, and Purpose
- Web Prototype Goal
- Question-driven Master Plan Generation Structure

---

## License

The license for this project has not been finalized yet.
