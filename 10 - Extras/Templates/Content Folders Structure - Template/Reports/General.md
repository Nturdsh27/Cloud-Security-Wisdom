---
title: Reports
aliases:
  - Reports
  - Deliverables
  - Post-Mortems
tags:
  - index
  - reports
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

# Reports

## Purpose

Formal written outputs $em the documents we hand to someone else, and the write-ups of things that happened.

## What This Folder Contains

- One folder per report **kind**, then one folder per year inside it.
- Each report is a folder containing the report page, its findings and its source material.

## Structure

```text
Reports/
+-- General.md
+-- Assessments/          # reviews we were asked to perform
+-- Audits/               # formal, often externally driven
+-- Post-Mortems/         # write-ups of events: incidents, suspicious findings
+-- Periodic/             # recurring status and summary reports
    +-- General.md
    +-- YYYY/
        +-- General.md
        +-- YYYY-MM-DD - Report Name/
            +-- Report.md        # the report itself - start here
            +-- Findings/        # one page per finding
            +-- Source Material/ # sanitized data the report is based on
```

## Naming

- Kind folder: one of `Assessments`, `Audits`, `Post-Mortems`, `Periodic`. Add a new kind only if several reports will use it.
- Year folder: `2026`.
- Report folder: `YYYY-MM-DD - Report Name`, where the date is when the report was **delivered**.
- The report page inside is always `Report.md`.

## Good To Know

- **Kind before year**, because people look for `the last access-review assessment`, not `everything from March`.
- A report is the *conclusion*; the work behind it usually lives in `Missions` or `Studies`. Link both ways.
- Office and PDF deliverables are stored as attachments next to a Markdown page that summarizes them — see the repo [[README]].

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
