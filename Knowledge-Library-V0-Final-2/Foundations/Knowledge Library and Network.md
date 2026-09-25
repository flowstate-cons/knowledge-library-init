---
type: reference
status: active
updated: {{YYYY-MM-DD}}
---

# Knowledge Library and Network

**Function:** how agents, their instructions, memory and the library fit together, so knowledge ends up in the right place and gets found again.

## Overview

The system has three layers:
1. **Instructions**, always loaded: AGENTS.md, plus any memories or system prompts an agent platform provides. Short, and read every session.
2. **The Knowledge Library**: the pages in this repository. The depth. Read when a task needs it.
3. **Raw**: the original documents the library was built from. Kept unchanged as the record.

## Placement

- If an agent must know it every single time, it belongs in the instructions, and should be short.
- If a person or agent reads it to understand or decide something, it belongs in the library.
- If it is an original document, it belongs in raw, and the library summarizes what it teaches.

When in doubt, put it in the library. Instructions that grow long get skimmed.

## Flow

1. **Capture:** a document lands in raw/Inbox.
2. **File:** the library manager moves it into the right raw folder and writes a short capture page in Library/Sources.
3. **Synthesize:** what it teaches goes into the relevant library pages.
4. **Retrieve:** agents start at index.md, follow hub pages, and read what applies.

## Platform Memory

Some platforms, such as Hyperagent, let an agent keep memories that load every turn. Use them for the few things that must always fire, such as the instruction to read this library. Keep the knowledge itself here, where it is versioned, readable by people, and portable to any agent or tool.
