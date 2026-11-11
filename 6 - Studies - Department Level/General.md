---
title: 6 - Studies - Department Level
aliases:
  - Department Studies
  - Research
  - Studies
  - Researches
tags:
  - index
  - studies
  - research
  - department-level
author:
owner:
created: 11-11-2026
type: Folder Overview (General)
---

### Related Files:

[[ ]]

---

# 6 - Studies - Department Level

## Purpose

Deeper exploratory work that is not tied to a single mission — research, evaluations and proofs of concept relevant to the whole department.

## What This Folder Contains

- New attack techniques and defensive approaches.
- Evaluations and comparisons of services and tools.
- Proofs of concept, with method, results and conclusions.
- Dead ends — research that did not work out, and why.

## Good To Know

Document the method, not just the conclusion. A study nobody can reproduce is an opinion. Dead ends are valuable: knowing what does **not** work saves the next person the same week.

## Structure

This folder follows the standard layout defined in `10 - Extras/Templates/Content Folders Structure - Template`. Copy the skeleton from there — do not invent a layout.

```text
<Folder>/
+-- General.md
+-- Study Subject/
    +-- Study.md         # question, method, conclusion - start here
    +-- Experiments/     # what was actually tried, and what happened
    +-- References/      # external sources, papers, vendor docs
```

- Organized **by subject, not by date** â€” studies get revisited. Dates live in the `created` / `updated` properties.
- Name the folder in plain words: `Cross-Account Role Chaining`, not `Study 3`.

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
