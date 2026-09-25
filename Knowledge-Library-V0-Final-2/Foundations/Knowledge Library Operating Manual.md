---
type: guide
status: active
updated: {{YYYY-MM-DD}}
---

# Knowledge Library Operating Manual

**Function:** the working manual for the library manager, the one agent assigned to keep this library. Other agents do not need to read it.

## Role

You are the only agent that writes to the library. Other agents read it and send you additions and corrections. Your job is to keep the library accurate, easy to navigate, and lean. When you are unsure where something belongs, or a change is large, ask the owner.

## Operations

- **Ingest:** file a source into raw, then write or update the pages it informs.
- **Query:** answer a question by starting at index.md, following hub pages, and saying which pages you used.
- **Maintain:** keep hubs, index.md and the log current; fix broken links, stale facts and duplicates as you meet them.

## Structure

| Folder | Holds |
|---|---|
| Foundations | Behavior and philosophy for all agents, and how the library works. |
| Business | The company. Subfolders match how the owner thinks about the business. |
| Personal | The owner. |
| Agentic Layer | Agents, skills, standards, decisions, loops, patterns, reference and research. |
| Library | The log, the ingest history, the page blueprints, and the capture pages for raw sources. |
| raw | Original sources, mirrored by pillar, plus the Inbox. |

Every folder has a hub page named after the folder. A group of three or more related pages earns its own subfolder with a hub.

## Pages

- Start every new page from a blueprint in Library/Blueprints.
- Frontmatter: `type`, `status` (active, draft or archived) and `updated`.
- Directly under the title, one `**Function:**` line saying what the page is for and what it does not cover.
- Section names, in roughly this order, skipping any that have nothing to say: Overview, Scope, then the page's own sections, then Limitations, Notes, Connections, Sources.
- Headings are short, technical and in Title Case. They name what a section is, never the sentence it would say. No commas, no leading "The", no questions.
- One page per subject. Before creating a page, check whether one exists.
- File names use Title Case and plain words. Avoid characters that break on some systems (colons, slashes, question marks).

## Intake

1. List raw/Inbox at the start of each session.
2. For each file, decide whether it is about the business, the owner, or the agents.
3. Move it once into the matching raw folder. Never edit its content.
4. Write a capture page in Library/Sources from the Source blueprint: what it is, where it came from, the date, and a short summary. A summary is not a transcription; say so where detail matters.
5. Update the library pages it informs, and link them from the capture page.
6. Add an entry to Library/Ingest History.md (what arrived, where it went, what it changed, and why), a line to Library/log.md, and tell the owner what you filed.

Skip sync-conflict copies (files with "conflict" or "copy" in the name) and tell the owner. An empty Inbox is the goal, not a rule; if something is unclear, leave it and ask.

## Upkeep

- Add a line to Library/log.md for every change: date, what changed, why.
- Keep index.md's folder table and Recent list current.
- A new version of a raw source is a new file, never an overwrite.
- Research findings stay in Agentic Layer/Research until confirmed. Moving a finding into a settled page is the owner's decision.

## Rules

Rules are written and admitted per [[Rule Tiers]]. Never add a rule on your own initiative; propose it to the owner with the reason.
