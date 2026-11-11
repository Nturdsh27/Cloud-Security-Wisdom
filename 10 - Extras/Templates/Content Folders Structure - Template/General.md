---
title: Content Folders Structure - Template
aliases:
  - Content Structure Template
  - Folder Layouts
  - Standard Layouts
tags:
  - index
  - template
  - structure
  - conventions
  - meta
author:
owner:
created: 11-11-2026
type: Template
---

### Related Files:

[[ ]]

---

# Content Folders Structure - Template

## Purpose

The canonical internal layout of the six recurring content folders: **Missions**, **Reports**, **Studies**, **Presentations**, **Architectures** and **Meeting Summaries**.

These folders exist at department level (`4`-`9`), inside every team and inside every project. Their layout is identical everywhere — only the scope changes. Copy the relevant skeleton from here instead of inventing a layout.

## What This Folder Contains

- One skeleton per content folder, with its `General.md` and its sub-folders already in place.
- Placeholder folders named with the pattern to follow (`YYYY`, `YYYY-MM-DD - Name`).
- Ready-to-copy document templates in `Document Templates`.

## Structure

```text
Content Folders Structure - Template/
+-- Missions/
+-- Reports/
+-- Studies/
+-- Presentations/
+-- Architectures/
+-- Meeting Summaries/
```

## Good To Know

**Two organizing principles, applied consistently:**

| Principle | Used by | Why |
| --- | --- | --- |
| **By date** — YYYY/ then YYYY-MM-DD - Name | Missions, Reports, Presentations, Meeting Summaries | These are *events*. They happened once, on a date, and are never updated afterwards. Chronology is how people look for them. |
| **By subject** — <Subject>/ | Studies, Architectures | These are *living*. They get revisited, extended and superseded. A date in the path would be a lie within a year. |

**One item = one folder when it has attachments, one file when it does not.** A mission with screenshots and exports gets a folder; a two-paragraph meeting summary is just a file. Start as a file, promote to a folder when it grows.

## Contents

A short map of everything in this folder, so you can find what you need without opening each file.

| Item | Type | What it is about |
| --- | --- | --- |
| _Nothing here yet_ | | _Add the first item and list it here._ |

> Keep this table current. When you add, rename or remove a file in this folder, update the row in the same Pull Request — a stale index is worse than no index.

## How To Use It

- Read this page first — it is the index and the "why" of this folder.
- Keep the **Contents** table above current — it is how people navigate this folder.
- Every file in this folder must start with the standard properties block followed by a `Related Files` section (see the repo [[README]]).
- In `author` write your full name, your username (the part of your organizational mail between the `xd.` and the `@`) or your initials — whichever you prefer, used consistently.
