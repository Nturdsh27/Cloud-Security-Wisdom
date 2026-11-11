---
title: Project Architectures
aliases:
  - Project Diagrams
  - Project Design
tags:
  - index
  - architecture
  - diagrams
  - project
author:
owner:
created: 11-11-2026
type: Folder Overview (General)
---

### Related Files:

[[ ]]

---

# Project Architectures

## Purpose

Architecture, design and data-flow documentation for this project.

## What This Folder Contains

- System and network diagrams, trust boundaries and data flows.
- Design decisions and the trade-offs behind them.
- Diagram sources (Mermaid blocks, Excalidraw, draw.io) together with a written explanation.

## Good To Know

Prefer Mermaid so the diagram is diff-able in a Pull Request. Every diagram needs a sentence explaining what the reader should take away from it.

## Structure

This folder follows the standard layout defined in `10 - Extras/Templates/Content Folders Structure - Template`. Copy the skeleton from there — do not invent a layout.

```text
<Folder>/
+-- General.md
+-- System or Domain/
    +-- Overview.md     # what it is, how it fits together - start here
    +-- Diagrams/       # Mermaid, Excalidraw, draw.io
    +-- Decisions/      # one page per decision (ADR), numbered
    +-- Flows/          # data flows and trust boundaries
```

- Organized **by subject, not by date** â€” architectures are living documents.
- Decisions are numbered (`0003 - Centralize Logs In One Account.md`) and never rewritten; a new record supersedes an old one.

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
