# Junior Skills

`junior-skills` is a small, beginner-friendly skills pack for early developers.

It is designed for people who can code a little already, but still need help turning ideas into a simple build plan, growing a project safely, and checking the result without getting lost in advanced engineering language.

## What This Repo Helps With

- understanding a brief
- adding more features without chaos
- planning a simple frontend and backend structure
- planning a reusable frontend design system
- building one page or feature at a time
- deciding what to test
- checking security basics
- checking whether the codebase follows clear standards

## One Look Guide

```text
Have a brief?
  -> use understand-brief

Want to add more features or complexity?
  -> use grow-project

Need a simple frontend + backend plan?
  -> use plan-stack

Need a reusable UI system for multiple screens?
  -> use design-system-plan

Need backend architecture beyond the basics?
  -> use backend-system-design

Ready to build one small part?
  -> use build-small

Want to know what to test?
  -> use test-small

Want a beginner-friendly review?
  -> use check-my-work

Want to check security basics?
  -> use security-check

Want to check coding standards?
  -> use standards-check
```

## Recommended Flow

```text
brief
  ->
understand-brief
  ->
grow-project
  ->
plan-stack
  ->
design-system-plan
  ->
backend-system-design
  ->
build-small
  ->
test-small
  ->
check-my-work
  ->
security-check + standards-check
```

You do not need every skill every time. Most beginners will usually use 3 to 5 of them on a small project.

## Skills At A Glance

| Skill | Use it when... | What it gives you |
| --- | --- | --- |
| `understand-brief` | you have a project brief or idea | pages, features, MVP, build order |
| `grow-project` | you want to add more features or abstraction | phased scope growth without overcomplicating things |
| `plan-stack` | you need frontend and backend structure | pages, components, routes, models, folders, build order |
| `design-system-plan` | you want multiple screens to feel consistent | tokens, UI components, states, and responsive rules |
| `backend-system-design` | you need deeper backend planning | APIs, data models, auth flow, storage, and scale-later decisions |
| `build-small` | you want to build one page or feature now | a small, clear implementation path |
| `test-small` | you want to know what to test | manual checks, critical flows, edge cases |
| `check-my-work` | you finished a page or feature | a simple review with the most important fixes |
| `security-check` | your feature touches forms, auth, APIs, storage, or user input | a beginner-level security checklist |
| `standards-check` | you want the codebase to stay consistent | coding-style and structure feedback |

## Real Use Cases

### Case 1: You have a design brief

Prompt:

```text
Use understand-brief on this project brief and give me the easiest MVP for a beginner.
```

Then:

```text
Use plan-stack and help me plan the frontend and backend for this MVP.
```

Then:

```text
Use design-system-plan and help me define the colors, typography, spacing, and reusable UI pieces for this MVP.
```

Then:

```text
Use backend-system-design and help me define the APIs, data models, auth flow, and what backend choices should wait until later.
```

### Case 2: You already built one page

Prompt:

```text
Use check-my-work and tell me the top issues in this page before I continue.
```

Then:

```text
Use test-small and tell me what I should test manually.
```

### Case 3: You want to make the project bigger

Prompt:

```text
Use grow-project and help me add auth, user profiles, and saved progress without making the app too complex for my level.
```

## Install From GitHub

Once this repo is pushed to GitHub, install it like this:

```bash
npx skills@latest add Juadebfm/junior-skills
```

Install all skills for Codex in the current project:

```bash
npx skills@latest add Juadebfm/junior-skills --all -a codex -y
```

Install one skill only:

```bash
npx skills@latest add Juadebfm/junior-skills --skill understand-brief -a codex -y
```

If you publish under a different GitHub path, replace `Juadebfm/junior-skills` with your real repo path.

## Repo Shape

This repo follows the same simple installable pattern as the reference repo you shared:

- each skill lives inside `skills/`
- each skill has a `SKILL.md`
- each skill can also have `agents/openai.yaml`
- the repo can be installed externally from GitHub with the `skills` CLI

## Repo Layout

```text
skills/
  understand-brief/
  grow-project/
  plan-stack/
  design-system-plan/
  backend-system-design/
  build-small/
  test-small/
  check-my-work/
  security-check/
  standards-check/
examples/
  codetrack/
  taskflow/
```

## Example Files

- `examples/codetrack/project-brief.md`
- `examples/codetrack/example-prompts.md`
- `examples/taskflow/project-brief.md`
- `examples/taskflow/example-prompts.md`

## Publishing Notes

Before publishing:

1. Push this repo to GitHub.
2. If your final repo path is not `Juadebfm/junior-skills`, update the install commands and package URLs.
3. Update `package.json` author details if needed.
4. Keep new skills short, practical, and beginner-safe.
