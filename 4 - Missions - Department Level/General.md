---
title: 4 - Missions - Department Level
aliases:
  - Department Missions
  - Missions
  - Operations
tags:
  - index
  - missions
  - department-level
  - records
author:
owner:
created: 11-11-2026
type: Folder Overview (General)
---

### Related Files:

[[ ]]

---

# 4 - Missions - Department Level

## Purpose

Records of missions carried out at department scope — work that involved more than one team, or whose outcome concerns the entire department.

## What This Folder Contains

- One folder per year, and inside it one folder per mission.
- Each mission record covers: context, scope, timeline, what we did, findings, impact, deliverables, lessons learned.
- Findings, sanitized evidence and deliverables, each in their own sub-folder.

## Good To Know

A mission page is written while the mission is fresh, not reconstructed months later.

Team-scoped missions live under the owning team in `3 - Teams Knowledge/<Team>/Missions`. Same structure and conventions — only the scope differs.

Formal write-ups and post-mortems that come out of a mission belong in `5 - Reports - Department Level` — link them from the mission record.

**Redact before you write.** No credentials, customer identifiers or raw sensitive logs.

## Structure

This folder follows the standard layout defined in `10 - Extras/Templates/Content Folders Structure - Template`. Copy the skeleton from there — do not invent a layout.

```text
<Folder>/
+-- General.md
+-- YYYY/
    +-- General.md
    +-- YYYY-MM-DD - Mission Name/
    |   +-- Mission.md          # the record itself - start here
    |   +-- Findings/           # one page per finding
    |   +-- Evidence/           # sanitized queries, outputs, screenshots
    |   +-- Deliverables/       # what was handed over
    +-- YYYY-MM-DD - Small Mission.md
```

- Year folder: `2026`. Mission folder: `YYYY-MM-DD - Mission Name`, dated when the mission **started**.
- The record inside a mission folder is always `Mission.md`.
- A mission with no attachments can stay a single file under the year folder.

## Contents

A short map of everything in this folder, so you can find what you need without opening each file.

| Item | Type | What it is about |
| --- | --- | --- |
| _Nothing here yet_ | | _Add the first page and list it here._ |

> Keep this table current. When you add, rename or remove a file in this folder, update the row in the same Pull Request — a stale index is worse than no index.

## How To Use It

- Read this page first — it is the index and the "why" of this folder.
- Keep the **Contents** table above current — it is how people navigate this folder.
- Every file in this folder must start with the standard properties block followed by a `Related Files` section (see the repo [[README]]).
- In `author` write your full name, your username (the part of your organizational mail between the `xd.` and the `@`) or your initials — whichever you prefer, used consistently.
