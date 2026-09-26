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
- Anything that sounds like a principle or a rule goes to the Candidates section of `Framework/Foundations/Core Philosophy.md`. It is not a rule yet. Principles are earned in real work, not declared on day one.
- If the owner does not know an answer yet, leave the section empty and say so. An honest gap beats a guess.

## 1. Identity

Ask.
- What is the business called, and what does it do, in a sentence?
- Who does it serve?
- Who is on the team, and what does each person do?
- What is your name and role?

Write the business answers to `Business/Business Overview.md` (title it with the business name). Write the owner's name and role to `Personal/Profile.md`'s Identity section. Fill in `Library manager: [agent name]` in `AGENTS.md` with your own agent name. Create your own page in `Agentic Layer/Agents/` from the Agent blueprint in `Framework/Library/Blueprints/`, and a page for each library skill you carry in `Agentic Layer/Skills/` from the Skill blueprint. Fill in the rows of both hub tables.

## 2. Profile

Ask.
- What are you especially good at, that agents should hand back to you rather than attempt themselves?
- Is there a habit or a way things tend to go wrong for you, that an agent should watch for or adjust to?

Write the answers to `Personal/Profile.md`'s Strengths and Watch-Outs sections. Leave either empty and say so if the owner has nothing yet.

## 3. Structure

Show the owner the starting Business folders, meaning Operations, Sales and Marketing, Tools and Tech, Website, Brand, Voice and Content. Ask.
- Do these fit how you think about your business?
- Would you rename, merge or add any?

Rename or add folders to match. Every new folder gets a hub page named after it, and a line in index.md. Renaming or merging a folder means finding and repairing every path reference the rename touches, including AGENTS.md, README.md, the Operating Manual and this file, since a missed reference fails silently.

## 4. Voice

Ask for two or three things the owner actually wrote and sent, such as emails, posts or a proposal. People describe their own writing poorly, while real samples do not. Build `Personal/Voice and Style.md` from those samples. If the business has its own voice, meaning a brand voice that differs from the owner's, note it in `Business/Voice and Content/Voice and Content.md`.

## 5. Preferences

Ask.
- How do you like updates, short or detailed?
- When should an agent just act, and when should it check with you first?
- What would annoy you in how an agent works with you?

Write the answers to the Register section of `Personal/Preferences.md`.

## 6. Glossary Terms

Ask whether there are words this business uses in its own way, that an outsider might misread, such as a product name, an internal shorthand, or a term of art in this industry. Write each one, with its meaning, to the Business section of `Framework/Foundations/Glossary.md`. If the owner cannot think of any yet, leave the section as it is and say so. Terms can be added the first time one causes confusion.

## 7. First Sources

Ask for three to five existing documents that describe how the business works, such as an SOP, the offer, a pitch deck or a price sheet. If the owner can drop them in `raw/Inbox/` themselves, have them do that. If they cannot, because they have no git access or local copy of the repository, have them upload the files directly to you in this conversation, and file them into `raw/Inbox/` yourself using your write access. Either way, file each one (see the Operating Manual) with a one-line summary in its frontmatter, add its line to `Records/Source History.md`, and write or update the pages it informs.

## Close

Tell the owner, in five lines or less, what was created, where their business and personal information now lives, that anything they drop in `raw/Inbox`, or hand you directly, gets filed, that agents will check the library before working, and one thing to do this week, usually dropping in two more documents.

Then.
1. Replace `{{YYYY-MM-DD}}` with today's date on every page outside `Framework/Library/Blueprints/` (the blueprints keep their placeholders, since they are templates), and set `setup: complete` plus the completion date in this file's frontmatter.
2. Fill in `Framework/About.md` with the release date, this initialization date, and today as the last updated date.
3. Replace this file's own body (everything below its frontmatter) with a short line, "Setup is complete. This library was initialized on {{the date}}. See Framework/About.md." Keep the frontmatter so the completion is still recorded. The guided steps have done their job once the library is running.
4. Remove the one-time setup instructions that no longer apply now that setup is complete, meaning `README.md`'s "One-Time Setup" heading and its contents. No other section currently carries one-time setup text. Add a line to `Records/Log.md` recording the removal, and confirm `setup: complete` is set in this file's frontmatter.
