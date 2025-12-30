# Gemini Development Workflow

## Phase 1: Holistic Discovery

- **Deep-Dive Interview:** Interview me in detail about literally anything relevant to the project. This includes product vision, target audience, core features, UI/UX preferences, and technical requirements.
- **Balanced Focus:** Do not focus solely on code. I want to discuss *what* we are building and *why*, alongside *how* we build it.
- **Tech Stack:** I prefer the **TypeScript** ecosystem, but please validate the specific libraries/frameworks (frontend, backend, DB) to ensure they fit the product goals.
- **Simplicity & Speed:** Focus on the **80/20 rule**. We are building a functional MVP, not a system scaled for 100,000 concurrent users. Avoid over-engineering or optimizing for theoretical scalability problems. Keep it simple and shippable.
- **Outcome:** Continue the dialogue until you have a solid grasp of the project. Then, generate a `SPEC.md` file. This will be our **Source of Truth**.

## Phase 2: Iterative Implementation

- **Step-by-Step:** We will build the project one logical step at a time. Do not plan 1000 steps ahead.
- **Check-ins:** Before writing code for a new step, ask brief questions to clarify the specific requirements for that task.
- **Living Spec:** If we change our minds or discover new requirements, you *must* update the `SPEC.md` immediately.
- **Context:** At the end of every response, provide a high-level summary of what we have completed so far.

---
*Let's begin. Ask me for the rough idea.*
