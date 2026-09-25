---
type: guide
status: active
setup: not-started
step: 0
completed:
updated: {{YYYY-MM-DD}}
---

# Initialization

**Function:** the guided first session that turns this template into the owner's own Knowledge Library. Run by the library manager, with the owner, once.

## Overview

About 30 minutes. The agent asks, writes what it hears into the right pages, and shows the owner what it wrote. After each step, update `step` in the frontmatter above. If the session is interrupted, resume from the recorded step. When the last step is done, set `setup: complete` and the date in `completed`.

## Agent Rules

- Ask one short group of questions at a time. Never ask the owner to fill in a form.
- Write only what the owner actually said. Do not invent details, goals or principles.
- Show each page you created or changed, in a sentence or two, before moving on.
- Anything that sounds like a principle or a rule goes to the Candidates section of Foundations/Core Philosophy.md. It is not a rule yet. Principles are earned in real work, not declared on day one.
- If the owner does not know an answer yet, leave the section empty and say so. An honest gap beats a guess.

## 1. Identity

Ask:
- What is the business called, and what does it do, in a sentence?
- Who does it serve?
- Who is on the team, and what does each person do?
- What is your name and role?

Write to: `Business/Business.md` (title it with the business name) and `Personal/Personal.md`. Fill in `Library manager: [agent name]` in AGENTS.md with your own agent name. Create your own page in `Agentic Layer/Agents/` from the Agent blueprint, and a page for each library skill you carry in `Agentic Layer/Skills/` from the Skill blueprint. Fill in the rows of both hub tables.

## 2. Structure

Show the owner the starting Business folders: Operations, Sales and Marketing, Tools and Tech, Website, Brand, Voice and Content. Ask:
- Do these fit how you think about your business?
- Would you rename, merge or add any?

Rename or add folders to match. Every new folder gets a hub page named after it, and a line in index.md.

## 3. Voice

Ask for two or three things the owner actually wrote and sent: emails, posts, a proposal. People describe their own writing poorly; real samples do not. Build `Personal/Voice and Style.md` from those samples. If the business has its own voice (a brand voice that differs from the owner's), note it in `Business/Voice and Content/Voice and Content.md`.

## 4. Working Style

Ask:
- How do you like updates: short or detailed?
- When should an agent just act, and when should it check with you first?
- What would annoy you in how an agent works with you?

Write to the Working Style section of `Personal/Personal.md`.

## 5. First Sources

Ask for three to five existing documents that describe how the business works: an SOP, the offer, a pitch deck, a price sheet. Have the owner drop them in `raw/Inbox/`, or upload them. File each one (see the Operating Manual), then write or update the pages they inform.

## Close

Tell the owner, in five lines or less:
- what was created,
- where their business and personal information now lives,
- that anything they drop in raw/Inbox gets filed,
- that agents will check the library before working,
- one thing to do this week (usually: drop in two more documents).

Then replace `{{YYYY-MM-DD}}` with today's date on every page outside `Library/Blueprints/` (the blueprints keep their placeholders; they are templates), and set `setup: complete`.
