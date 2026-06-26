---
name: security-check
description: Use this skill when a beginner wants to check a project or feature for common security issues such as unsafe input handling, weak auth flows, exposed secrets, or risky API behavior.
---

Use this skill when the project touches:

- forms
- authentication
- user input
- file upload
- local storage
- cookies
- APIs
- database writes

## Goal

Catch common security mistakes early in a way a beginner can understand.

## Review Focus

Check for:

- missing input validation
- trusting client-side checks too much
- secrets exposed in code
- unsafe storage of sensitive data
- weak auth or authorization logic
- dangerous API behavior
- obvious XSS or injection risk

## Output

Produce:

## Security Findings

- issue
- why it matters
- simplest safer fix

## Security Basics To Keep

- things already done well

## Next Safety Improvements

- highest-value next steps

## Rules

- Keep advice concrete and beginner-safe.
- Focus on real risks, not theory.
- Explain why each issue matters in plain language.
- Prioritize the fixes that reduce the most risk first.
