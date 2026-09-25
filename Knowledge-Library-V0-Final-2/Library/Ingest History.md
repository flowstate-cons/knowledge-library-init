---
type: log
status: active
updated: {{YYYY-MM-DD}}
---

# Ingest History

**Function:** one entry for every source filed into the library: what arrived, where it went, what it changed, and why it was placed there. Oldest first. Added to, never rewritten.

## Overview

The log records every change in one line. This page holds the reasoning behind each ingest: why a source went where it did, what it updated, and any call that was not obvious (a source split across two pages, a suggestion that was turned down, a conflict with an existing page). That reasoning is what makes the library trustworthy months later, when someone asks why a page says what it says.

## Scope

- One entry per source, written by the library manager at the time of filing.
- Each entry: the date, the source (linked to its capture page in Library/Sources), where the original was filed in raw, the pages created or updated, and the reasoning for any placement that was a judgment call.
- Every ingest also gets its one-line entry in Library/log.md, pointing here.

## Limitations

- Changes that did not come from a source (a correction from the owner, a restructure) go in the log only.
- Entries are history. A later correction is a new entry, never an edit to an old one.

## Entries

[Entries are added here, oldest first, in this shape:]

[### {{YYYY-MM-DD}}: {{Source title}}]
[- Source: [[{{capture page}}]], filed at raw/{{folder}}/{{file}}]
[- Updated: [[{{page}}]], [[{{page}}]]]
[- Why: {{the reasoning for any placement that was not obvious}}]
