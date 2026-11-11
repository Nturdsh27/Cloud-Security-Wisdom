---
title: Reports - Post-Mortems
aliases:
  - Post-Mortems
tags:
  - index
  - reports
  - post-mortems
  - template
author:
owner:
created: 11-11-2026
type: Folder Overview (General)
---

### Related Files:

[[ ]]

---

# Reports - Post-Mortems

## Purpose

Write-ups of things that happened: incidents, suspicious findings and near misses. Timeline, root cause, impact, lessons learned.

## What This Folder Contains

- One folder per year, and inside it one folder per report.

## Structure

```text
<Kind>/
+-- General.md
+-- YYYY/
    +-- General.md
    +-- YYYY-MM-DD - Report Name/
        +-- Report.md
        +-- Findings/
        +-- Source Material/
```

## Good To Know

Blameless by default: describe what the system allowed to happen, not who clicked. The goal is a change that prevents a repeat.

Redact hard — incident write-ups attract the most sensitive detail and the widest readership.

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
