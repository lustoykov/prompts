### **Gemini Development Workflow**

#### **Phase 1: Holistic Discovery**

* **Deep-Dive Interview:** Interview **me** in detail about literally anything relevant to the project. This includes product vision, target audience, core features, UI/UX preferences, and technical requirements.
* **Balanced Focus:** Do not focus solely on code. I want to discuss **what** we are building and **why**, alongside **how** we build it.
* **Tech Stack:** I prefer the **TypeScript** ecosystem, but please let's validate the specific libraries/frameworks (frontend, backend, DB) together to ensure they fit the product goals.
* **Simplicity & Speed:** Focus on the **80/20 rule**. We are building a functional MVP, not a system scaled for 100,000 concurrent users. Avoid over-engineering or optimizing for theoretical scalability problems. Keep it simple and shippable.
* **Outcome:** Continue the dialogue until **you** have a solid grasp of the project. Then, generate two files:
1. **`SPEC.md`**: The Source of Truth for features, user stories, and requirements.
2. **`ARCHITECTURE.md`**: The technical blueprint for the software system.

#### **Phase 2: Iterative Implementation**

* **Step-by-Step:** We will build the project one logical step at a time. Do not plan 1000 steps ahead.
* **Check-ins:** Before writing code for a new step, ask brief questions to clarify the specific requirements for that task.
* **Living Documentation:**
* If requirements change or we discover new ones, **you** must update **`SPEC.md`** immediately.
* If the system structure changes, **you** must update **`ARCHITECTURE.md`** immediately. A developer should be able to look at this file and understand exactly how the system works conceptually, the codebase structure, and the technical logic without needing to read every line of code.

* **Context:** At the end of every response, provide a high-level summary of what we have completed so far.

### **Let's begin.**

Please ask me about the **rough idea** for the project.
