---
name: test-small
description: Use this skill when a beginner wants to know what to test in a small project or feature, including manual checks, critical flows, and simple edge cases.
---

Use this skill after planning or building a page, feature, or small app.

## Goal

Help the user test the most important things first.

## Workflow

### Step 1

Identify the critical flows:

- what must work
- what can fail
- what user inputs can go wrong

### Step 2

Produce:

## Must Test

- primary user flow
- important validation
- empty states
- error states
- responsive behavior

## Good Edge Cases

- missing input
- invalid input
- duplicate actions
- slow or missing data

## Suggested Test Approach

- manual checks
- unit tests if the project supports them
- integration tests if the project supports them

### Step 3

Keep the test plan realistic for the project size and the user's experience level.

## Rules

- Do not recommend a huge test suite for a tiny project.
- Start with manual verification when that is the right choice.
- Focus on user-visible behavior first.
- Make the checklist easy to follow.
