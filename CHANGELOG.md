# Changelog

Every entry is a framework version, newest first. This tracks the template itself, not any one library built from it. See `Framework/About.md` in your own library for the version you are running, and its Upgrade History for when you moved between versions.

## 1.1

- Grouped the framework's own pages under `Framework/` (`Framework/Foundations/`, `Framework/Library/`), separating them clearly from the business's own content.
- Added `Records/` for the library's own history. `Records/Log.md` now keeps the current month plus two, with older months archived verbatim to `Records/Log Archive/`. `Records/Source History.md` replaces Ingest History with one line per source. `Records/Library Maintenance Queue.md` is new, for small fixes set aside for the weekly review.
- Moved `Operating Principles` out of Foundations and into `Business/`, since it is a business page, not an agent-behavior page.
- Renamed `Decisions` to `Key Decisions` throughout, covering its folder, hub and blueprint, and added Context, Alternatives and a Notes revisit-trigger field to the blueprint.
- Renamed the three pillar-front hubs to end in Overview (`Business Overview.md`, `Personal Overview.md`, `Agentic Layer Overview.md`), since a reader arriving at a pillar is better served by a page named for that than for its folder.
- Split the old combined Personal hub into `Personal/Profile.md` and `Personal/Preferences.md`, each a guided page the owner fills during Initialization, plus a short `Personal Overview.md` hub pointing to both and to Voice and Style.
- Added `Framework/Foundations/Working Philosophy.md`, covering how people and agents work together across scope, pace, questions and disagreement, distinct from the Code of Conduct's conduct rules and the Preferences page's settled record.
- Retired the per-source capture page and the Sources hub. A filed source now gets a line in `Records/Source History.md` linking straight to the raw file, plus a short frontmatter summary on the file itself where it can carry one. `Library/Blueprints/Source Blueprint.md` now names that frontmatter instead of a page.
- Built out `Framework/Library/Knowledge Library Operating Manual.md` with the Function Line writing guide and its four checks, Change Authority principles for when to act and when to ask, a single weekly review cadence, and upload instructions for an owner without git access.
- Fixed `AGENTS.md`'s Access section so a single agent working alone (a terminal setup with no separate manager) is told plainly that it is the library manager, instead of reading a read-only rule that contradicted its own job.
- Added a Glossary Terms step, and Profile and Preferences questions, to `Initialization.md`, so business-specific vocabulary and the owner's own page are captured at setup rather than left to come up later.
- `Initialization.md` and `README.md` are now rewritten at the end of setup, dropping the guided-session and GitHub-setup content that no longer applies once a library is running.
- Removed the agent name ("Curator") from `README.md`'s baseline setup instructions, matching the rest of the template, which already names no agent so a client can name theirs freely.
- Confirmed that a People or Clients subfolder under Business is allowed. Nothing in a framework page, standard or blueprint forbids one.
- Added `Framework/About.md` (framework version, release date, initialization date, source) and this `CHANGELOG.md`.
- Renamed "injection" to Knowledge Intake and "ingest" to Knowledge Synthesis throughout.
- Removed every colon from written content outside frontmatter, wikilink and code syntax, times of day and the Function label, and removed every spaced-hyphen dash, across the whole template rather than only new text.
- Rebuilt `index.md` as a single page catalog with a Routing block at the top naming the Glossary, Page Standard, Code of Conduct, Log, Business Overview, Agents and the Operating Manual, criticality-scaled entry length, and Raw excluded from the catalog. Removed the page's own trailing self-correction note.
- Every hub page (19 of them) now runs Function, Overview, Contents and Connections, replacing the old Function, Overview, Scope, Limitations, Pages shape.
- Moved `Code of Conduct.md` to a Function, Overview, Conduct, Writing, Connections, Sources shape, folding the confidence threshold and the approval-versus-praise distinction into Conduct.
- Moved `Working Philosophy.md` to a four-section shape, Trust, Acting And Asking, Scope and Disagreement, plus Overview.
- Re-layered `Glossary.md`, adding an AI And Agent Fundamentals section ahead of the library's own terms, and folding Agents and Rules into a single Library Terms section.
- Added `Framework/Library/Page Standard.md`, holding Writing A Purpose, the Four Checks, Starting A Page (moved from the Blueprints hub) and the Hub Pages shape.
- Added `Framework/Library/Tag Set.md`, shipping nine baseline tags (skill, library, governance, agent, schema, memory, platform, prompt, visual) and the rule for adding more.
- Renamed `Knowledge Library and Network.md` to `Knowledge Network.md`, so the page name no longer collides with the Knowledge Library itself, and fixed every reference to the old title.
- `Records/Source History.md`'s entry line gained a submitter field and an optional note field.
- Updated the routing text in `AGENTS.md` and `README.md` to the current wording, and put it word for word in both.
- Added a short, filled-in example to every blueprint in `Framework/Library/Blueprints/`, marked clearly for deletion.
- `Agentic Layer/Key Decisions/Key Decisions.md`'s hub now states plainly that it holds the business's key decisions and why they were made, not only decisions about the agents.
- Drafted `Framework/About.md` on the Framework Parity model, so the framework version recorded there equals the library's own structure version.
- Reworded `README.md` to cover only the library itself, moving the guided setup session under a One-Time Setup heading that the library manager removes once setup is complete, and leaving GitHub, agent platform and editor setup to separate documentation.
- Added a closing step to `Initialization.md` that removes one-time setup text once setup is complete, and logs the removal.

## 1.0

Initial release.
