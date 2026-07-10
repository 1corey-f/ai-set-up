# AI Assistant Setup — Kick-Off Prompt
# Your Project Instructions are already set up.
# Open your ChatGPT Project, start a new chat inside it, and paste everything in the code block below.

---

```
You're going to help me set up my AI assistant. Ask me this one question:

"Which best describes your primary need?
A) Technical — you work in an engineering or technical role and want an AI that knows your systems, documentation, and technical work.
B) Advisor/Coach — you want an AI that knows you, your goals, and helps you grow professionally and personally.
C) Both — you want technical help AND personal coaching in the same assistant."

Wait for my answer, then follow the path below.

---

IF I ANSWER A (Technical):

Say: "Great — let's build your context." Then fetch and run the onboarding prompts from this URL, working through them with me one question at a time:
https://raw.githubusercontent.com/1corey-f/ai-set-up/main/technical-team/onboarding-prompts.md

If you can't fetch the URL, say: "Open this link, click Raw, copy everything, and paste it here: https://github.com/1corey-f/ai-set-up/blob/main/technical-team/onboarding-prompts.md"

---

IF I ANSWER B (Advisor/Coach):

Say: "Great — let's build your context." Then fetch and run the onboarding prompts from this URL, working through them with me one question at a time:
https://raw.githubusercontent.com/1corey-f/ai-set-up/main/advisor-coach/onboarding-prompts.md

If you can't fetch the URL, say: "Open this link, click Raw, copy everything, and paste it here: https://github.com/1corey-f/ai-set-up/blob/main/advisor-coach/onboarding-prompts.md"

---

IF I ANSWER C (Both):

Say: "Great — we'll run two interviews back to back. The first covers your technical context, the second your goals and development. Let's start with the technical side."

First, fetch and run the onboarding prompts from:
https://raw.githubusercontent.com/1corey-f/ai-set-up/main/technical-team/onboarding-prompts.md

Once that interview is complete and the context file generated, say: "Now let's do the coaching and development side."

Then fetch and run the onboarding prompts from:
https://raw.githubusercontent.com/1corey-f/ai-set-up/main/advisor-coach/onboarding-prompts.md

If you can't fetch either URL, say: "Open these links, click Raw, copy everything, and paste each one here when prompted:
- Technical: https://github.com/1corey-f/ai-set-up/blob/main/technical-team/onboarding-prompts.md
- Advisor/Coach: https://github.com/1corey-f/ai-set-up/blob/main/advisor-coach/onboarding-prompts.md"
```
