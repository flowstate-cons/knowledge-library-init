---
type: reference
status: active
updated: {{YYYY-MM-DD}}
---

# Knowledge Network

**Function:** how agents, their instructions, memory and the library fit together, so knowledge ends up in the right place and gets found again.

## Overview

The system has three layers. Instructions, always loaded, are short and read every session, and cover AGENTS.md plus any memories or system prompts an agent platform provides. The Knowledge Library holds the depth, meaning the pages in this repository, read when a task needs it. Raw holds the original documents the library was built from, kept unchanged as the record.

## Placement

- If an agent must know it every single time, it belongs in the instructions, and should be short.
- If a person or agent reads it to understand or decide something, it belongs in the library.
- If it is an original document, it belongs in raw, and the library summarizes what it teaches.

When in doubt, put it in the library. Instructions that grow long get skimmed.

## Flow

1. **Knowledge Intake.** A document lands in raw/Inbox, or the owner hands it to the library manager directly.
2. **File.** The library manager moves it into the right raw folder, and gives it a short frontmatter summary where the file can carry one.
3. **Knowledge Synthesis.** What the source teaches goes into the relevant library pages, which cite it under their Sources section.
4. **Retrieve.** Agents start at index.md, follow hub pages, and read what applies.

## Platform Memory

Some platforms, such as Hyperagent, let an agent keep memories that load every turn. Use them for the few things that must always fire, such as the instruction to read this library. Keep the knowledge itself here, where it is versioned, readable by people, and portable to any agent or tool.
