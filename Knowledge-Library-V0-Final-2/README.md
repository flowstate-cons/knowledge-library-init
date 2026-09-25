# Knowledge Library

A starting template for your business's Knowledge Library: a folder of plain markdown pages that becomes your company's long-term memory. Your AI agents read it before they work, so they know how your business runs, who you serve, how you write, and what was decided and why. One agent manages it; every other agent reads it.

It is plain text in a git repository. Nothing here is tied to one AI product: any agent that can read files can use it, and you can open the whole folder in any markdown editor.

## Before You Start

**Keep your copy private.** This template is public, but your library will hold your business information. When you create your copy, choose **Private**.

## Setup

### 1. Make Your Copy

On GitHub, click **Use this template**, then **Create a new repository**. Name it (for example `knowledge-library`) and set it to **Private**.

### 2. Connect Your Agent

**On Hyperagent**

1. Install the Curator agent package. Curator is your library manager.
2. Create two GitHub fine-grained access tokens, each limited to this one repository:
   - read and write (Repository permissions, Contents: Read and write), for the **Manage Library** skill;
   - read only (Contents: Read-only), for the **Check Library** skill.
3. Add both skills to Curator and enter the repository URL and the matching token in each. Give Check Library to any other agent that should read the library.
4. Add the routing text below as a pinned memory, so every agent checks the library before it works.

The Curator package and both skills come from whoever gave you this template; they are not in this repository.

**In a terminal agent (Claude Code, Codex, Cursor and similar)**

1. Clone your private copy to your computer.
2. Open your agent in that folder. Codex reads `AGENTS.md` automatically, Claude Code reads it through `CLAUDE.md`, and Cursor supports a root `AGENTS.md` (if it does not load, start your first message with `@AGENTS.md`).

### 3. Run the Setup Session

Tell your agent: **"Let's set up my Knowledge Library."**

It opens `Initialization.md` and walks you through about 30 minutes of questions: your business, how you want it organized, your writing voice, how you like to work, and your first documents. It writes as you go and shows you each page. If you stop partway, it picks up where you left off next time.

## After Setup

- **Adding material:** drop any file (PDFs, notes, exports) in `raw/Inbox/`. The library manager files it and updates the pages it informs.
- **Asking questions:** ask any agent. It reads the library and tells you which pages it used.
- **Corrections:** tell the library manager. It makes every change and logs it in `Library/log.md`.

## What's Inside

| Folder | Holds |
|---|---|
| `Foundations/` | How your agents behave, and how the library works. |
| `Business/` | Your company: operations, sales and marketing, tools, website, brand, voice and content. |
| `Personal/` | You: profile, working style, and writing voice. |
| `Agentic Layer/` | Your agents: what each does, their skills, standards and decisions. |
| `Library/` | The change log, the ingest history, the blueprints new pages are built from, and a summary page for each original document. |
| `raw/` | Original documents, never edited. New files go in `raw/Inbox/`. |

Start at `index.md`. Each folder has a hub page named after it that says what belongs there.

## Routing Text

For platforms that use memories rather than `AGENTS.md`. Pin this as a memory that every agent sees:

```
A markdown repository is this system's long-term memory and source of truth: how the business runs, its people and clients, decisions and why they were made, standards and procedures, research, and instructions for agents. Not exhaustive. Before any substantive task, and whenever the conversation touches the business or past work, read the entry page (index.md) and follow it to what applies. If the entry page does not cover it, list the top-level folders and read each folder's hub page (the page named after the folder). Say what you found and used, or that you found nothing.
```

## Browsing

Pages link to each other with `[[Page Name]]`. Open the folder as a vault in Obsidian (free) to browse it by clicking through the links.
