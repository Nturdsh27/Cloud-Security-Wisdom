---
title: Application Security - How To
aliases:
  - Application Security Guides
  - AppSec How To
  - How To
  - Instructions
tags:
  - index
  - how-to
  - guides
  - instructions
  - appsec
  - team-level
author:
owner:
created: 11-11-2026
type: Folder Overview (General)
---

### Related Files:

[[ ]]

---

# Application Security - How To

## Purpose

Practical, step-by-step instructions for the things this team actually does.

This folder answers one question: **"How do I do X?"** — nothing else. It exists so a new member can perform real work on their first week without shadowing someone, and so a veteran can remember the exact steps of something they last did eight months ago.

## What This Folder Contains

- One page per task, named as the task itself: `How To - <Do The Thing>.md`.
- Concrete steps, in order, with the exact commands, queries, console paths and screenshots needed.
- Prerequisites: required access, permissions and tools, stated up front.
- Verification: how to confirm the thing actually worked.
- Rollback: how to undo it if it did not.
- Common errors and what they mean.

## Suggested Guides For This Team

Use these as a starting point — add, split and rename as the team's work evolves:

- How To - Run a code review with a security focus
- How To - Perform a threat model for a new service
- How To - Onboard a repository to SAST and tune the first wave of findings
- How To - Add SCA / dependency scanning to a pipeline
- How To - Add secret scanning and handle a leaked secret
- How To - Run a DAST scan against a staging environment safely
- How To - Set up a security gate in a CI/CD pipeline
- How To - Triage and validate a finding (and recognize a false positive)
- How To - Write a finding report that developers will actually act on
- How To - Verify a fix and close a finding
- How To - Review authentication and authorization in an application
- How To - Review how an application stores and handles secrets
- How To - Test an API for the OWASP API Top 10
- How To - Review a container image and its base layers
- How To - Handle a disclosed vulnerability in a third-party dependency

## How To Write A Guide Here

- **Write it while you do it.** A guide written from memory skips the step that always breaks.
- **Be exact.** Real commands in fenced code blocks, real console paths, real field names. No "configure the settings appropriately".
- **Assume nothing.** The reader may have joined last week. Link prerequisites with `[[ ]]` instead of explaining them again.
- **Date what ages.** Tools and consoles change: "As of 11-11-2026, the setting is under Repository → Security."
- **Redact.** Repository names, tokens, internal URLs and customer data never appear in a guide. Use placeholders like `<repo-name>`.
- **Fix it when it breaks.** If you followed a guide and the steps were wrong, update it in the same session — that is the whole point of this folder.

## Contents

A short map of everything in this folder, so you can find what you need without opening each file.

| Item | Type | What it is about |
| --- | --- | --- |
| _Nothing here yet_ | | _Add the first page and list it here._ |

> Keep this table current. When you add, rename or remove a file in this folder, update the row in the same Pull Request — a stale index is worse than no index.

## How To Use It

- Read this page first — it is the index and the "why" of this folder.
- Keep the **Contents** table current — it is how people navigate this folder.
- Every file in this folder must start with the standard properties block followed by a `Related Files` section (see the repo [[README]]).
- In `author` write your full name, your username (the part of your organizational mail between the `xd.` and the `@`) or your initials — whichever you prefer, used consistently.
