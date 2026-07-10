# AI Setup — Clinical Systems Team

A set of prompts and instructions for setting up a personalised AI assistant in ChatGPT. There are two versions depending on what you need.

---

## Which folder is for me?

### [`advisor-coach/`](./advisor-coach)
For anyone who wants an AI that acts as a **personal advisor and coach** — helps with goals, development, work challenges, and the whole person. Includes coaching on patterns, assertiveness, and things you're working on.

→ **Start here if:** you want an AI that knows you, challenges you, and helps you grow — not just complete tasks.

### [`technical-team/`](./technical-team)
For **engineers and technical roles** who want an AI that knows their stack, their integrations, and their documentation responsibilities. Focused on technical problem-solving, governance docs, and project management.

→ **Start here if:** you want an AI that understands your technical context and helps you work faster.

---

## How it works

1. Create a **ChatGPT Project** at [chat.openai.com](https://chat.openai.com) → your name → Projects → New Project
2. Open the project → click **...** → **Edit** → copy [`system-prompt.md`](./system-prompt.md) into the Instructions field → Save
3. Start a **new chat inside the project** and paste the contents of [`kick-off.md`](./kick-off.md)
4. Answer one question (Technical or Advisor/Coach) — your onboarding interview begins immediately
5. At the end, upload the generated files via **Sources → Add sources**

Done. Every conversation in that project will have full context about who you are and how you work.

---

## Keeping it current

Your context file will get stale. When something significant changes — new project, new goal, role shift — open a chat in your project, paste the section that's out of date, describe what changed, and ask ChatGPT for an updated version. Replace the file in Sources.
