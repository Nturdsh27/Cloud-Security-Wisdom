---
title: 5 - Reports - Department Level
aliases:
  - Department Reports
  - Reports
  - Deliverables
tags:
  - index
  - reports
  - department-level
  - deliverables
author:
owner:
created: 11-11-2026
type: Folder Overview (General)
---

### Related Files:

[[ ]]

---

# 5 - Reports - Department Level

## Purpose

Formal written outputs produced at department level — the documents we hand to someone else.

## What This Folder Contains

- Assessment, audit and review reports.
- Periodic status and summary reports.
- Findings and recommendations documents.
- Write-ups of past events: incidents, suspicious findings and post-mortems — timeline, root cause, impact and lessons learned.
- The source material and data behind each report, where it can be shared.

## Good To Know

If the deliverable is an Office or Google file, store the exported PDF/`.docx` alongside a Markdown summary page that explains what it is, when it was produced and for whom. See the repo [[README]] section on non-Markdown files.

## Structure

This folder follows the standard layout defined in `10 - Extras/Templates/Content Folders Structure - Template`. Copy the skeleton from there — do not invent a layout.

```text
<Folder>/
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

- **Kind before year**, because people look for "the last access review", not "everything from March".
- Report folder: `YYYY-MM-DD - Report Name`, dated when it was **delivered**. The page inside is always `Report.md`.

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
