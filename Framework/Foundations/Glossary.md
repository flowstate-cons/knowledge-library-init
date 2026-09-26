---
type: reference
status: active
updated: {{YYYY-MM-DD}}
---

# Glossary

**Function:** short definitions of the terms used in this library. Look terms up here, it is not meant to be read through.

## AI And Agent Fundamentals

Portable, general terms from the wider field of AI and agents, true of any system built this way.

- **Model.** The underlying AI system that generates a response from a prompt and its context.
- **Agent.** An AI system that pursues a goal across multiple steps, calling tools and carrying memory, rather than answering once and stopping.
- **Prompt.** The instructions and context an agent or model reads before it responds.
- **System Prompt.** The standing instructions that set an agent's identity, scope and rules, loaded before any message in the conversation.
- **Context Window.** The total text a model can hold in view at once, including the prompt, memory and the conversation so far.
- **Tool.** A discrete capability an agent can call during its own reasoning, such as a search or a calculation.
- **Memory.** A short instruction or fact an agent platform keeps loaded for an agent, small and always on. The library holds the depth.
- **Skill.** A packaged capability, usually code and credentials, that extends what an agent can do beyond its own reasoning.
- **Hallucination.** A model or agent stating something false or unsupported with full confidence, rather than signaling uncertainty.

## Library Terms

- **Knowledge Library.** This markdown repository, the business's long-term memory and source of truth, read by every agent.
- **Markdown Repository.** The technical name for the library, a folder of plain text files kept in version control.
- **Framework.** The pages that define how the library and its agents work, meaning Foundations and Library, as opposed to the business's own content.
- **Records.** The folder holding the library's own history, meaning the Log, Source History and the Library Maintenance Queue.
- **Entry Page.** index.md, where every agent starts.
- **Hub Page.** The page named after its folder, saying what belongs in the folder and listing its pages. The pillar-level hubs (Business Overview, Personal Overview, Agentic Layer Overview) are the one exception, named for the reader arriving rather than for the folder.
- **Blueprint.** A page skeleton in Framework/Library/Blueprints. Every new page starts from one.
- **Frontmatter.** The short block of fields at the top of a page, holding type, status and updated.
- **Raw.** The folder of original source material, never edited except for the frontmatter a filed source gains.
- **Inbox.** raw/Inbox, where anyone can drop a file for the library manager to file.
- **Source.** One original document in raw. It has no page of its own. Its line in Source History, and its own frontmatter where the file supports one, describe it.
- **Knowledge Intake.** Sending a document into the library, by dropping it in raw/Inbox or handing it to the library manager.
- **Knowledge Synthesis.** Turning a filed source into the library pages it informs.
- **Log.** Records/Log.md, a dated line for every change to the library, covering the current and two previous months.
- **Log Archive.** Records/Log Archive, one file per older month, holding that month's log entries verbatim.
- **Source History.** Records/Source History.md, one line per source filed, giving its date, submitter, name, route in, status and a link to the file.
- **Library Maintenance Queue.** Records/Library Maintenance Queue.md, small library fixes set aside for the weekly review.
- **Library Manager.** The one agent assigned to manage the library, and the only agent that writes to it.
- **AGENTS.md.** The file agents read automatically at the start of every session.
- **Tag.** One word from the Tag Set applied to a page's frontmatter to make it findable. See [[Tag Set]].
- **Law.** A rule with no exceptions. See [[Rule Tiers]].
- **Principle.** An expected behavior that allows a departure with a stated reason. See [[Rule Tiers]].
- **Candidate.** A proposed principle, waiting to prove itself in real work. See [[Core Philosophy]].
- **Key Decision.** A dated page recording a choice, the options considered, and why. See What Goes Where below for where it lives.

## What Goes Where

- **Standard.** A rule agents must follow. If an agent can be in violation of it, it is a Standard. Lives in Agentic Layer/Standards.
- **Pattern.** A proven method an agent chooses to use. Skipping it is not a violation. Lives in Agentic Layer/Patterns.
- **Reference.** A settled fact to look up, such as how a tool behaves, a limit, or how something is set up. Lives in Agentic Layer/Reference.
- **Research.** An investigation and its findings, not yet confirmed. It moves to a settled page once confirmed. Lives in Agentic Layer/Research.
- **Key Decision.** Never edited later. A reversal is a new record, and the old one is marked superseded. Lives in Agentic Layer/Key Decisions.
- **Loop.** A recurring process, with its trigger and steps. Lives in Agentic Layer/Loops.
- **Guide.** Step by step instructions for a business task. Lives in the Business folder it belongs to.

## Business

[Terms specific to this business, confirmed with the owner at setup and added as new ones come up.]
