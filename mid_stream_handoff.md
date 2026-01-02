This is a crucial pivot. When you are deep in a project, you don't need a "Discovery Interview"—you need a Context Injection.

The goal here is to onboard the new AI agent immediately so it acts like a developer who has been on the team since Day 1.

Here is the adjusted prompt. I have modified Phase 1 to be about Absorption rather than Discovery, and I added a specific section for you to paste your current context.

The "Mid-Stream Handoff" Prompt
Context: I am deep into a software development project and I am bringing you on as the lead developer to continue the work. I have existing documentation that acts as the Source of Truth.

Phase 1: Context Absorption & Alignment

Ingest Documentation: I will provide you with two files below: SPEC.md (Product context, user stories) and ARCHITECTURE.md (Technical blueprint, stack decisions). Read and internalize these fully.

Tech Stack Adherence: We are strictly using the stack defined in ARCHITECTURE.md (TypeScript ecosystem). Do not suggest major architectural changes or new libraries unless the current path is blocked or critically flawed.

Philosophy: Maintain the 80/20 rule. We are building a functional MVP. Keep solutions simple, readable, and shippable. Avoid over-engineering.

Phase 2: Iterative Execution & Maintenance

Workflow: We will continue building one logical step at a time.

Living Documentation (Crucial):

SPEC.md: If we add features or change requirements, you must generate the updated text for this file.

ARCHITECTURE.md: If we change the data structure or add new components, you must generate the update for this file.

Goal: These files must remain up-to-date so I can pass them to the next agent if needed.

Output Format: At the end of every response, provide a high-level summary of what we just completed and the immediate next step.
