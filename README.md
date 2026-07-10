# Clinical Systems Team — AI Assistant Setup

This folder contains everything an engineer needs to set up their own personalised AI assistant in ChatGPT. Once set up, it will know their role, their projects, how they like to work, and what they're trying to get better at — and it will use that context in every conversation.

---

## What you'll end up with

A ChatGPT Project that:
- Knows your technical context and the systems you own
- Helps with governance documentation, integration work, and project management
- Adapts its responses to how you actually like to work
- Tracks your skills development focus over time

---

## Setup — do this once

**Step 1 — Create a ChatGPT Project**
In ChatGPT, click your name → Projects → New Project. Give it a name (e.g. "Clinical Systems").

**Step 2 — Add the system prompt**
Open the project → Instructions → paste the full contents of `system-prompt.md` into the custom instructions field. Save.

**Step 3 — Run the onboarding prompts**
Start a new conversation inside your project. Open `onboarding-prompts.md` and work through each prompt in order — paste each one into ChatGPT and answer the questions it asks. This usually takes 20–30 minutes.

**Step 4 — Generate and save your context file**
The final prompt tells ChatGPT to generate your personal context file. Copy the output, save it as `[yourname]-context.md`, and upload it to your project files (paperclip icon in the project sidebar).

**Step 5 — Done**
Every conversation in this project now has full context. You don't need to re-explain who you are or what you're working on.

---

## Keeping it current

Your context file will get stale. Update it when:
- You take on a new project or hand one off
- Your skills focus changes
- Something in your role shifts significantly

To update: open a conversation in your project, paste the relevant section of your `.md` file, describe what's changed, and ask ChatGPT to give you an updated version. Replace the file in your project.

---

## Files in this folder

| File | What it is |
|---|---|
| `README.md` | This file — the setup guide |
| `system-prompt.md` | Paste into ChatGPT Project custom instructions |
| `onboarding-prompts.md` | Run these in order to build your context file |
| `context-template.md` | Reference for what your context file should contain |
