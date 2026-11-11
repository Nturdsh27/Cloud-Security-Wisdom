---
title: Missions
aliases:
  - Mission Records
  - Operations
tags:
  - index
  - missions
  - records
  - template
author:
owner:
created: 11-11-2026
type: Folder Overview (General)
---

### Related Files:

[[ ]]

---

# Missions

## Purpose

Records of missions and engagements: what we were asked to do, what we did, what we found and what it meant.

## What This Folder Contains

- One folder per year, and inside it one folder per mission.
- Each mission folder holds the mission record plus its findings, evidence and deliverables.
- A small mission with no attachments may be a single file directly under the year folder.

## Structure

```text
Missions/
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

## Naming

- Year folder: `2026`.
- Mission folder or file: `YYYY-MM-DD - Mission Name`, where the date is when the mission **started**.
- The record inside the folder is always called `Mission.md`, so the path reads `2026-03-14 - Prod IAM Review/Mission.md`.

## Good To Know

- **Write it while it is fresh.** A mission reconstructed six months later is a story, not a record.
- **Evidence is sanitized evidence.** Never paste raw logs, raw exports or unredacted screenshots. Summarize, redact, use placeholders.
- A mission that is part of a project belongs under that project's `Tasks` folder instead.
- Formal write-ups and post-mortems that come out of a mission go to `Reports` — link them from the mission record.

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
