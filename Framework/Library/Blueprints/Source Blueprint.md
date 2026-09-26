---
type: reference
status: active
updated: {{YYYY-MM-DD}}
---

# Source Blueprint

**Function:** name the frontmatter a filed raw source carries, so a document that was never synthesized can still be found and understood without reopening it. This is not a page blueprint. No page is created from it.

## Fields

When the filed source is itself a text or markdown file, add this block above its existing content.

```
---
filed: {{YYYY-MM-DD}}
origin: {{where it came from, a person, a URL, or a system}}
summary: {{what it says, in one line}}
---
```

## Limitations

- A binary file (a PDF, an image, an export) cannot carry frontmatter. Skip this step for one, and rely on its line in Records/Source History.md instead, which carries the same summary and a link to the file.
- This never becomes a substitute for Knowledge Synthesis. A summary orients a reader to a source that has not been synthesized yet. It is not the same as the source's content living in the library's own pages.

## Example

_A short filled example, using a fictional small bakery. Delete this section before starting a new page._

```
---
filed: 2026-03-04
origin: Emailed by the owner
summary: The bakery's current wholesale price sheet.
---
```
