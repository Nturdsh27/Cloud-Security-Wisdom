---
title: Studies
aliases:
  - Studies
  - Research
  - Evaluations
tags:
  - index
  - studies
  - research
  - template
author:
owner:
created: 11-11-2026
type: Folder Overview (General)
---

### Related Files:

[[ ]]

---

# Studies

## Purpose

Exploratory work that is not tied to a single mission: techniques, service evaluations, proofs of concept and the conclusions drawn from them.

## What This Folder Contains

- One folder per study, named after the **subject** $em not the date.
- Each study holds its conclusion page, its method, its experiments and its references.

## Structure

```text
Studies/
+-- General.md
+-- Study Subject/
    +-- Study.md         # question, method, conclusion - start here
    +-- Experiments/     # what was actually tried, and what happened
    +-- References/      # external sources, papers, vendor docs
```

## Naming

- Study folder: the subject in plain words $em `Cross-Account Role Chaining`, `Wiz vs Native CSPM`.
- No dates in the name: studies get revisited. Put the dates in the properties (`created`, `updated`).

## Good To Know

- **Document the method, not just the conclusion.** A study nobody can reproduce is an opinion.
- **Dead ends are results.** Write up what did not work and why — it saves the next person the same week.
- A study that turns out to matter beyond its team should be promoted to `6 - Studies - Department Level`, leaving a link behind.

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
