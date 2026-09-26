# Knowledge Library

A starting template for your business's Knowledge Library, a folder of plain markdown pages that becomes your company's long-term memory. Your AI agents read it before they work, so they know how your business runs, who you serve, how you write, and what was decided and why. One agent manages it, and every other agent reads it.

It is plain text in a git repository. Nothing here is tied to one AI product. Any agent that can read files can use it.

## What's Inside

| Folder | Holds |
|---|---|
| `Framework/` | How your agents behave and how the library itself works, plus the About page recording your framework version. |
| `Business/` | Your company, covering operating principles, operations, sales and marketing, tools, website, brand, voice and content. |
| `Personal/` | You, covering your profile, preferences and writing voice. |
| `Agentic Layer/` | Your agents, covering what each does, their skills, standards, key decisions, loops, patterns, reference and research. |
| `Records/` | The library's own history, covering the change log, the source history, and the library maintenance queue. |
| `raw/` | Original documents, never edited except for a short frontmatter summary. New files go in `raw/Inbox/`. |

Start at `index.md`. Each folder has a hub page named after it that says what belongs there, apart from the three pillar-front hubs (Business Overview, Personal Overview, Agentic Layer Overview), which are named for the reader arriving instead. `Framework/About.md` records which version of this framework your library is running, and `CHANGELOG.md` records what changed between versions.

## One-Time Setup

Tell your agent, "Let's set up my Knowledge Library."

It opens `Initialization.md` and walks you through about 30 minutes of questions covering your business, how you want it organized, your writing voice, how you like to work, and your first documents. It writes as you go and shows you each page. If you stop partway, it picks up where you left off next time.

Once setup is complete, this heading and its contents no longer apply, and the library manager removes them.

## After Setup

- **Adding material.** Drop any file, such as a PDF, a note or an export, in `raw/Inbox/` if you can. If you do not have a way to add it there yourself, upload the file directly to the library manager in conversation instead, and it files the file into `raw/Inbox/` on your behalf. Either way, the library manager files it and updates the pages it informs.
- **Asking questions.** Ask any agent. It reads the library and tells you which pages it used.
- **Corrections.** Tell the library manager. It makes every change and logs it in `Records/Log.md`.

## Routing Text

For platforms that route agents by memory rather than by a file such as `AGENTS.md`. Pin this as a memory that every agent sees.

```
KNOWLEDGE LIBRARY = SOURCE OF TRUTH. A markdown repository on GitHub holding how this business runs and how its agents work. Before any substantive task, and whenever conversation touches the business or past work: open it with the skill that accesses it via GitHub, read AGENTS.md at the root (index.md if there is none), follow it. Read the live pages it points to and anything relevant every time, never answer from recall.

MEMORIES: only the agent that maintains the knowledge library and context layer creates them. Any other agent that sees something fitting a memory rather than the library escalates it to that agent, through the user or through a memory request skill if one exists. Never create one yourself.
```
