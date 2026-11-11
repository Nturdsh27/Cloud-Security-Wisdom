---
title: Cloud Security AWS - How To
aliases:
  - AWS Guides
  - AWS How To
  - How To
  - Instructions
tags:
  - index
  - how-to
  - guides
  - instructions
  - aws
  - team-level
author:
owner:
created: 11-11-2026
type: Folder Overview (General)
---

### Related Files:

[[ ]]

---

# Cloud Security AWS - How To

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

- How To - Create an IAM policy (and scope it down properly)
- How To - Create an IAM role and a trust policy for cross-account access
- How To - Write and apply a Service Control Policy (SCP)
- How To - Create a new AWS account in the Organization with the right baseline
- How To - Configure a Security Group / NACL rule and verify it
- How To - Set up a VPC with private subnets, NAT and endpoints
- How To - Enable and centralize CloudTrail across the Organization
- How To - Query CloudTrail with Athena to investigate an action
- How To - Enable GuardDuty, Security Hub and Config, and route the findings
- How To - Create and rotate a KMS key, and configure a key policy
- How To - Store and consume a secret from Secrets Manager / Parameter Store
- How To - Lock down an S3 bucket (public access block, policy, encryption)
- How To - Configure OIDC federation from GitHub Actions to AWS (no long-lived keys)
- How To - Investigate a compromised IAM user or access key
- How To - Find and remove unused IAM permissions with Access Analyzer

## How To Write A Guide Here

- **Write it while you do it.** A guide written from memory skips the step that always breaks.
- **Be exact.** Real `aws` CLI commands in fenced code blocks, real console paths, real field names. No "configure the settings appropriately".
- **Assume nothing.** The reader may have joined last week. Link prerequisites with `[[ ]]` instead of explaining them again.
- **Date what ages.** The console moves: "As of 11-11-2026, this is under IAM → Access Analyzer."
- **Redact.** Account IDs, ARNs with real names, access keys and customer data never appear in a guide. Use placeholders like `<account-id>` and `<role-name>`.
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
