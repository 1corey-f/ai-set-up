# Onboarding Prompt Sequence
# Run these in order inside your ChatGPT Project. Paste each prompt, answer the questions, then move to the next.

---

## Before you start

Open a new conversation inside your ChatGPT Project. Work through each prompt below in order — paste the prompt text into ChatGPT, then answer the questions it asks. Be as specific as you can. The more detail you give, the more useful your assistant will be.

This should take around 20–30 minutes. You only do it once.

---

## Prompt 1 of 5 — Role & Technical Context

```
We're going to build a context file so you can assist me effectively going forward. Start with my role and technical background.

Ask me these questions, one at a time, and wait for my answer before moving on:

1. What's your job title, and what are you actually responsible for day to day?
2. What systems, tools, programming languages, or platforms do you work with regularly?
3. Which specific integrations, processes, projects or systems do you personally own or maintain?
4. What does a productive week look like for you? And what does a frustrating one look like?
5. Is there anything about your role that's unusual or that I'd need to know to understand your context properly?

After I've answered all five, summarise back what you've understood. Ask me to correct anything that's wrong or missing before we move on.
```

---

## Prompt 2 of 5 — Current Projects & Documentation

```
Now let's cover the work I'm currently doing and the documentation I'm responsible for.

Ask me these questions, one at a time:

1. What projects or pieces of work are you actively involved in right now?
2. What governance or technical documentation do you own or regularly contribute to? (e.g. integration specs, change records, risk logs, runbooks, SOPs)
3. What project management tools do you use? (e.g. Jira, Confluence, MS Project, spreadsheets)
4. What documentation do you find hardest to write, keep current, or get right?
5. What project management or admin work takes up more time than it should?

After I've answered all five, summarise what you've understood. Ask me to correct anything before we move on.
```

---

## Prompt 3 of 5 — Skills Development

```
Now I want to capture what I'm trying to get better at. This will help you support my development, not just complete tasks.

Ask me these questions, one at a time:

1. What skills are you actively trying to build right now — technical or otherwise?
2. What areas of your work do you feel least confident in?
3. Is there anything you feel you should know better by now but never got properly taught or had time to learn?
4. What's one thing — if you got significantly better at it — would make you noticeably more effective in your role?
5. Is there anything you've been putting off learning? What's stopping you?

After I've answered all five, summarise what you've understood. Ask me to correct anything before we move on.
```

---

## Prompt 4 of 5 — How You Like to Work

```
This is important — I want you to adapt to how I actually think and work, not use a one-size-fits-all approach.

Ask me these questions, one at a time:

1. When you're stuck on something technical, do you prefer to be walked through it step by step, or do you want the direct answer and can figure out the rest yourself?
2. Do you want me to explain my reasoning when I give you an answer, or just give you the output?
3. What frustrates you most about AI responses? (e.g. too long, too cautious, over-explains basics, hedges instead of committing, starts with disclaimers)
4. Do you want to be challenged — pushed to think through problems yourself — or is this more of a tool you want to just get things done quickly?
5. What tone works best for you? For example: a peer-level colleague who gets straight to it, a patient explainer who walks you through things, a consultant who gives recommendations, a coach who is patient and understanding and gives you a good pep talk when needed — or something else?
6. Any other preferences or pet peeves I should know about?

After I've answered all six, summarise the picture you have of how I work. Ask me to correct anything before we move on.
```

---

## Prompt 5 of 5 — Generate Your Context File

```
We've now covered everything I need to build your context file. Using everything from our conversation today, generate a personal context file in Markdown format using this exact structure:

# [My name] — Clinical Systems Context File

## Role & Responsibilities
[What they do day to day]

## Technical Stack
[Systems, tools, languages, platforms]

## Integrations & Systems Owned
[Specific things they maintain]

## Active Projects
[Current work]

## Documentation Responsibilities
[Governance docs, specs, runbooks they own]

## Project Management
[Tools they use, where time gets lost]

## Skills Development Focus
[What they're building, what they're working on, what they've been avoiding]

## Working Style & Communication Preferences
[How they like to receive information, tone, level of explanation, pet peeves, direct vs exploratory]

---
*Last updated: [today's date]*

Be specific — use the exact details I gave you, not generic descriptions. After generating it, ask me if anything needs to be added, corrected, or adjusted before I save it.
```

---

## After Prompt 5

1. Copy the full output from ChatGPT
2. Save it as a file named `[yourname]-context.md` (e.g. `sarah-context.md`)
3. Go back to your ChatGPT Project main page (click the project name in the sidebar)
4. Click **Sources** → **Add sources** → upload your `.md` file

You're done. The system prompt already tells ChatGPT to read your context file at the start of every conversation — you don't need to add it to Instructions as well. From now on, start every conversation inside this project and ChatGPT will have full context.
