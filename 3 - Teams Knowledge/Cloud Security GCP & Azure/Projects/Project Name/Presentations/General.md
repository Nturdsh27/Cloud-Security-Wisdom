---
title: Project Presentations
aliases:
  - Project Slides
  - Project Decks
tags:
  - index
  - presentations
  - project
author:
owner:
created: 11-11-2026
type: Folder Overview (General)
---

### Related Files:

[[ ]]

---

# Project Presentations

## Purpose

Presentations given about this project — status updates, design reviews, demos and final debriefs.

## What This Folder Contains

- Slide decks (`.pptx`, Google Slides export, PDF) and Markdown-native decks.
- A short Markdown page per deck: topic, audience, date, presenter, key takeaways.

## Good To Know

Binary decks are not searchable. Always pair them with a Markdown summary page.

## Structure

This folder follows the standard layout defined in `10 - Extras/Templates/Content Folders Structure - Template`. Copy the skeleton from there — do not invent a layout.

```text
<Folder>/
+-- General.md
+-- YYYY/
    +-- General.md
    +-- YYYY-MM-DD - Topic/
        +-- Presentation.md  # topic, audience, takeaways - start here
        +-- Deck/            # the deck: .pptx / .pdf / Markdown slides
        +-- Demo/            # demo scripts, commands, recordings
```

- Presentation folder: `YYYY-MM-DD - Topic`, dated when it was **presented**.
- `Presentation.md` carries the takeaways in text so they are searchable. The deck is an attachment, not the knowledge.

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
