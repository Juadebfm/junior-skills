---
name: standards-check
description: Use this skill when a beginner wants to check whether a codebase follows clear coding standards for naming, structure, consistency, readability, and project organization.
---

Use this skill after some code has been written or when the project is starting to feel inconsistent.

## Goal

Help the user keep the codebase clean, consistent, and easier to maintain.

## Workflow

### Step 1

Look for explicit standards first:

- project docs
- lint rules
- formatter rules
- existing code patterns

### Step 2

If no written standards exist, infer the current pattern from the codebase and use that as the baseline.

### Step 3

Review:

- naming consistency
- file and folder organization
- repeated patterns
- code readability
- component or function size
- comments that are missing or unnecessary

### Step 4

Produce:

## Standards Findings

- issue
- why it breaks consistency
- recommended fix

## Patterns To Keep

- good conventions already present

## Simple Standards To Follow Next

- short rules the user can keep using

## Rules

- Favor consistency over personal style preference.
- Keep the feedback practical.
- Avoid nitpicks unless they are repeated or confusing.
- If the current codebase is already consistent, say that clearly.
