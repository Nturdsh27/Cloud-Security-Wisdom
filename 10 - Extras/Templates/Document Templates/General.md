---
title: Document Templates
aliases:
  - Templates
  - Page Templates
  - Boilerplate
tags:
  - index
  - templates
  - conventions
  - meta
author:
owner:
created: 11-11-2026
type: Template
---

### Related Files:

[[Content Folders Structure - Template/General|Content Folders Structure - Template]]
[[Team Organization of Knowledge - Tempalte/General|Team Organization of Knowledge - Tempalte]]

---

# Document Templates

## Purpose

Ready-to-copy skeletons for every kind of document in this repository. Copy the right one instead of starting from a blank page — it is faster, and it means every mission, report and study is structured the same way for the next reader.

## What This Folder Contains

One template per document `type`. Each already contains the properties block, the `Related Files` section and the headings that document is expected to have.

## Contents

A short map of everything in this folder, so you can find what you need without opening each file.

| Item | Type | What it is about |
| --- | --- | --- |
| [[Architecture Overview]] | Template | A system or domain: components, flows, controls, decisions, limitations. |
| [[Decision Record]] | Template | One architectural decision (ADR): context, options, decision, consequences. |
| [[Experiment]] | Template | A single trial inside a study: hypothesis, setup, steps, result. |
| [[Finding]] | Template | One finding from a mission or report: severity, impact, recommendation, verification. |
| [[Meeting Summary]] | Template | A meeting: decisions, action items with owners, open questions. |
| [[Mission]] | Template | A mission record: context, scope, timeline, what we did, findings, lessons. |
| [[Post-Mortem]] | Template | A write-up of an event: timeline, root cause, impact, actions. |
| [[Presentation]] | Template | A talk: audience, key takeaways in text, outline, materials. |
| [[Report]] | Template | A formal deliverable: summary, scope and method, findings, recommendations. |
| [[Study]] | Template | Exploratory research: question, method, results, conclusion, dead ends. |

> Keep this table current. When you add, rename or remove a file in this folder, update the row in the same Pull Request — a stale index is worse than no index.

## How To Use A Template

1. Copy the file to the right folder — see [[Content Folders Structure - Template/General|Content Folders Structure - Template]] for where things go.
2. Rename it according to the naming rule of that folder (`YYYY-MM-DD - Mission Name`, `0003 - Decision`, and so on).
3. Fill in the properties block: `title`, `aliases`, `tags`, `author`, `owner`, `created`, `type`.
4. Fill in `Related Files` **before** you write the content — it forces you to notice what already exists.
5. Delete the sections that genuinely do not apply. Do not delete a section just because it is hard to fill in.

With the **Templater** plugin you can insert these directly from the command palette instead of copying files by hand.

## Good To Know

- The headings in a template are the **minimum** a reader expects. Add more if the subject needs it.
- A template is not a form to satisfy — it is a reminder of what the next reader will ask. If a section stays empty, ask yourself whether the page is finished.
- Improve the template when you find it lacking, in its own Pull Request, so every future document benefits.

## How To Use It

- Read this page first — it is the index and the "why" of this folder.
- Keep the **Contents** table above current — it is how people navigate this folder.
- Every file in this folder must start with the standard properties block followed by a `Related Files` section (see the repo [[README]]).
- In `author` write your full name, your username (the part of your organizational mail between the `xd.` and the `@`) or your initials — whichever you prefer, used consistently.
