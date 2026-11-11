---
title: 8 - Architectures - Department Level
aliases:
  - Department Architectures
  - Diagrams
  - Design
tags:
  - index
  - architecture
  - diagrams
  - department-level
author:
owner:
created: 11-11-2026
type: Folder Overview (General)
---

### Related Files:

[[ ]]

---

# 8 - Architectures - Department Level

## Purpose

Architecture and design documentation at department scope: how our environments, platforms and security controls fit together.

## What This Folder Contains

- Architecture diagrams (Mermaid, Excalidraw, draw.io).
- Data flow and trust boundary diagrams.
- Design decisions and the trade-offs behind them.
- Reference architectures we recommend or enforce.

## Good To Know

Prefer **diagrams-as-text** (Mermaid) wherever possible — they are reviewable in a Pull Request. Use Excalidraw / draw.io when the diagram is too complex for text, and always add a written explanation next to it.

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
