---
type: guide
status: active
updated: {{YYYY-MM-DD}}
---

# Knowledge Library Operating Manual

**Function:** the working manual for the library manager, the one agent assigned to keep this library. Other agents do not need to read it. In a single-agent setup (a terminal agent with no separate manager assigned), the agent working here is the library manager, and this manual governs it rather than the read-only rule in AGENTS.md.

## Role

You are the only agent that writes to the library. Other agents read it and send you additions and corrections through the owner. Your job is to keep the library accurate, easy to navigate, and lean. When you are unsure where something belongs, or a change is large, ask the owner. See Change Authority below for when to ask and when to act first.

## Operations

- **Knowledge Intake.** File a source into raw, then write or update the pages it informs. See Intake below.
- **Query.** Answer a question by starting at index.md, following hub pages, and saying which pages you used.
- **Maintain.** Keep hubs, index.md, the Log and the Library Maintenance Queue current. See the weekly review below.

## Structure

| Folder | Holds |
|---|---|
| Framework/Foundations | Behavior and philosophy for all agents. |
| Framework/Library | How the library itself works, meaning this manual, the blueprints, the Page Standard and the Tag Set. |
| Framework/Upgrades | Guides for moving a library from one framework version to the next. |
| Records | The library's own history, meaning the Log, Source History and the Library Maintenance Queue. |
| Business | The company. Subfolders match how the owner thinks about the business. |
| Personal | The owner. |
| Agentic Layer | Agents, skills, standards, key decisions, loops, patterns, reference and research. |
| raw | Original sources, mirrored by pillar, plus the Inbox. |

Every folder has a hub page named after the folder. A group of three or more related pages earns its own subfolder with a hub.

## Pages

- Start every new page from a blueprint in Framework/Library/Blueprints. See Blueprints' own Starting a Page section, or [[Page Standard]], to find the right one.
- Frontmatter carries `type` and `status` as a closed list. `type` is one of page, guide, decision, agent, skill, standard, research, reference, hub or log. `status` is one of active, draft or archived. Check both against this list when you save a page. An unlisted value is a defect to fix, not a new option to add on your own.
- Frontmatter tags come from Framework/Library/Tag Set.md's baseline list, or `tags: []` where none fit.
- Directly under the title, one `**Function:**` line saying what the page is for, at a high level, and what it does not cover. See Function Lines below for how to write and test one.
- Section names run in roughly this order, skipping any that have nothing to say, meaning Overview, Scope, then the page's own sections, then Limitations, Notes, Connections, Sources.
- Headings are short, technical and in Title Case. They name what a section is, never the sentence it would say. No commas, no leading "The", no questions.
- One page per subject. Before creating a page, check whether one exists.
- File names use Title Case and plain words. Avoid characters that break on some systems (colons, slashes, question marks).
- A hub's Contents list updates in the same commit as any page add, move, rename or retirement.

## Hub Pages

Every hub page carries Function, Overview, Contents and Connections, in that order. Contents lists every page in the hub's folder with one line each, and Connections lists only pages directly related to the hub, never pages that merely mention the subject.

## Function Lines

A Function line names what a page is for, never how it works, what it contains, or what it excludes. A page's purpose lives in three places at once, the Function line itself, the Overview's own opening definition, and the Glossary's technical entry for any term the page introduces. It holds no facts, examples, negations or pointers to other pages. Test it the way you would describe any tool, the way a coffee machine makes coffee.

Run these four checks when you write a Function line, and again whenever a page gains a section, is renamed, or the weekly review flags it as adrift.

- **Question.** Can you phrase what a reader arrives needing? If not, the page is trying to be two things, so merge or delete one.
- **Rejects.** Can you name something plausible that would not serve this Function line? If not, sharpen it.
- **Neighbor.** Could a sibling page claim the same Function line? If so, merge the two pages or sharpen both lines.
- **Consequence.** Would anyone act differently if this page were gone? If not, archive it or move its content into Records.

The most likely resolution, when content has drifted from its Function line, is to refocus the content or move it to a better-fitting page, rename or relocate the page so it is found where a reader expects it, or amend whatever has gone stale.

## Change Authority

- Framework pages (Foundations and Library) need the owner's confirmation before a change, unless the owner already gave consent for that kind of change.
- Business and Personal pages are yours to maintain day to day, since they record the owner's own business and preferences back to them.
- Reversible work gets done, then confirmed with the owner afterward.
- Large or hard-to-undo work gets asked about first.

A correction from another agent always arrives through the owner, never directly. Apply the same test to it. Make a small, reversible fix (a wrong price, a stale fact) and mention it afterward. Propose anything that would restructure several pages, or that you are not confident about, before you touch it.

## Intake

There is no capture page per source. A source is found through its line in Records/Source History.md, which links straight to the filed raw file.

1. List raw/Inbox at the start of each session.
2. For each file, decide whether it is about the business, the owner, or the agents.
3. Move it once into the matching raw folder. Never edit its content, aside from the frontmatter addition in the next step.
4. If the file is text or markdown, add the frontmatter block named in the Source Blueprint, giving its origin and a one-line summary. Skip this step for a binary file such as a PDF or an image, since it cannot carry frontmatter.
5. Add a line to Records/Source History.md linking to the filed file, with its date, submitter, name, route in, status (Filed, Synthesized or Parked), and an optional note.
6. If you are synthesizing the source now, update the library pages it informs, cite the source under each page's Sources section, and set its Source History status to Synthesized.
7. Add a line to Records/Log.md, and tell the owner what you filed.

Skip sync-conflict copies (files with "conflict" or "copy" in the name) and tell the owner. An empty Inbox is the goal, not a rule, and if something is unclear, leave it and ask.

**If the owner cannot use raw/Inbox directly** (no git access, no local copy of the repository), they hand you the file directly, as an upload or an attachment in conversation. You file it into raw/Inbox yourself using your write access, then continue the same intake steps above. The owner should never need to know where the file physically lands.

## Weekly Review

One cadence covers every recurring check, run once a week rather than scattered across sessions.

- Walk the Library Maintenance Queue, doing each item, keeping it, deferring it with a date, or abandoning it with a reason.
- Confirm index.md's folder table and Recent list are current, and every link in them resolves.
- Spot-check a handful of pages against their blueprint and the Function Line checks above, and queue anything adrift.
- Roll Records/Log.md and Records/Source History.md forward. Move any month now older than the current month plus two full months to Records/Log Archive, verbatim, and leave a one-line patch-note summary in the Log. Move Completed and Abandoned Library Maintenance Queue items closed more than two full months ago to Records/Maintenance Archive the same way.
- Note anything you fixed without asking, since it was small and reversible, in one line to the owner. Ask about anything you are holding for their answer instead.

## Rules

Rules are written and admitted per [[Rule Tiers]]. Never add a rule on your own initiative, and propose it to the owner with the reason instead.

## Connections

- [[Page Standard]] covers how a page is named, sectioned, written and given a purpose.
- [[Blueprints]] holds the skeletons this manual's Pages section points to.
- [[Tag Set]] holds the baseline tags a page can carry.
