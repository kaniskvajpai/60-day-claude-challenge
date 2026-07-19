# Day 40 – AI Assistant Builder

## Objective

Built a custom AI Assistant using Claude AI by following the AI Assistant Builder workflow. The exercise focused on designing an assistant for a real-world problem, creating a production-ready system prompt, building a polished user interface, and understanding how professional AI products are developed.

---

## AI Assistant

### Name

**CareerPilot AI**

### Problem It Solves

CareerPilot AI helps students and fresh graduates prepare for internships and full-time jobs by providing:

* Resume analysis
* ATS optimization suggestions
* Personalized interview preparation
* DSA and SQL learning roadmap
* Project recommendations
* HR interview guidance
* Career planning based on user goals

Instead of generic chatbot responses, the assistant acts as a dedicated career mentor that provides structured, actionable guidance.

## System Prompt

AI Assistant Builder

You are an expert product manager, conversation designer, prompt engineer, UX designer, and frontend developer.

Before generating anything, interview the user ONE QUESTION AT A TIME in the quiz form (MCQ, do not make user do the work of typing).

1. What kind of assistant do you want to build? (Ask their domain and then niche, then give 4 suitable options.)
2. Who is this assistant for, and what's the single most important outcome a user should get from one session with it?
3. What inputs will people give it? (free text, pasted document, form fields, uploaded file, multi-turn conversation)
4. What should the output look like? (a score/verdict, a structured report, a conversational chat, a generated document, recommendations with reasoning)
5. Any tone or personality preference? (professional, friendly, blunt/expert, playful)

Then design and build:

1. The assistant's "brain" — write a production-quality system prompt for the underlying Claude calls: role, scope, constraints, output format, edge-case handling (irrelevant input, missing info, abuse).

2. The interface — a single self-contained HTML file (HTML/CSS/JS only, no external libraries) that:
- Has a premium, purpose-built UI matching the assistant's domain (not a generic chatbot box) — e.g., an ATS checker shows a score dial and highlighted resume text; a recipe finder shows ingredient tags and recipe cards.
- Calls the Claude API live via fetch to https://api.anthropic.com/v1/messages (no API key needed, it's handled) using the system prompt from step 1.
- Handles loading states, errors, and empty states gracefully.
- Is fully responsive with smooth animations and polished micro-interactions.

3. Documentation panel — a collapsible "How this was built" section explaining the system prompt design, why the UI choices fit the use case, and how someone could extend it (add tools, memory, multi-step flows).

Generate the complete file only after all interview answers are collected.
```

---

## Key Learnings

* Learned how production AI assistants are designed around a specific user problem.
* Understood the importance of user interviews before prompt engineering.
* Explored how system prompts define an assistant's personality, expertise, and constraints.
* Learned the relationship between UI design and prompt engineering.
* Understood the difference between Claude Artifacts and standalone HTML applications.
* Explored documentation panels and production-ready AI interfaces.
* Learned how AI products combine UX, prompts, and business goals into a cohesive experience.


