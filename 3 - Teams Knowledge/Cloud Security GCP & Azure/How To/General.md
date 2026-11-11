---
title: Cloud Security GCP & Azure - How To
aliases:
  - GCP Guides
  - Azure Guides
  - How To
  - Instructions
tags:
  - index
  - how-to
  - guides
  - instructions
  - gcp
  - azure
  - team-level
author:
owner:
created: 11-11-2026
type: Folder Overview (General)
---

### Related Files:

[[ ]]

---

# Cloud Security GCP & Azure - How To

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

Use these as a starting point — add, split and rename as the team's work evolves. Where a task exists on both clouds, say so in the guide and cover both — that comparison is this team's unique value.

**GCP**

- How To - Create a custom IAM role and bind it at the right level (org / folder / project)
- How To - Write and apply an Organization Policy constraint
- How To - Create a project with the standard security baseline
- How To - Configure VPC firewall rules and verify them
- How To - Set up VPC Service Controls / a service perimeter
- How To - Configure and export Cloud Audit Logs to a central sink
- How To - Query logs in Cloud Logging to investigate an action
- How To - Create and rotate a key in Cloud KMS
- How To - Secure a service account (and avoid service account keys entirely)
- How To - Configure Workload Identity Federation from CI/CD to GCP

**Azure**

- How To - Create a custom RBAC role and assign it at the right scope
- How To - Write and assign an Azure Policy (and a deny / remediation effect)
- How To - Create a subscription with the standard baseline and Management Group placement
- How To - Configure an NSG rule and verify effective rules
- How To - Configure Private Endpoints and restrict public network access
- How To - Configure Entra ID Conditional Access policies
- How To - Review an Entra ID app registration and its permissions
- How To - Configure Diagnostic Settings and ship logs to Log Analytics
- How To - Query Azure activity and sign-in logs with KQL
- How To - Store and consume a secret from Key Vault with Managed Identity

## How To Write A Guide Here

- **Write it while you do it.** A guide written from memory skips the step that always breaks.
- **Be exact.** Real `gcloud` / `az` commands in fenced code blocks, real portal paths, real field names. No "configure the settings appropriately".
- **Assume nothing.** The reader may have joined last week. Link prerequisites with `[[ ]]` instead of explaining them again.
- **Date what ages.** Both portals change constantly: "As of 11-11-2026, this is under Entra ID → Security."
- **Redact.** Project IDs, tenant IDs, subscription IDs, secrets and customer data never appear in a guide. Use placeholders like `<project-id>` and `<tenant-id>`.
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
