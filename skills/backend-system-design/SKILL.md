---
name: backend-system-design
description: Use this skill when a beginner wants to plan the backend architecture for a project, including APIs, data models, auth flow, storage, background work, and simple scaling decisions.
---

Use this skill when the user needs backend structure that goes beyond a basic page-and-route plan.

## Goal

Help the user design a backend that is clear, practical, and not overengineered.

## Workflow

### Step 1

Understand the backend needs in plain language:

- what users can do
- what data must be stored
- what actions need server-side logic
- what needs authentication or authorization
- what might happen in the background

### Step 2

Produce:

## Backend Architecture

- recommended backend style
- key modules or domains
- what should stay simple in version 1

## Recommended Starter Stack

- backend framework or style
- database choice
- auth approach
- file storage approach if needed

## API Design

- main endpoints
- request and response shapes
- validation points

## Data Design

- main entities
- relationships
- storage choice
- fields that matter most

## Auth And Access

- login or session approach
- protected actions
- role or ownership rules if needed

## Reliability And Safety

- error handling
- rate limiting if needed
- file storage or external services if needed
- logging basics

## Request Flow

- how data moves from client to API to database
- where validation happens
- where auth checks happen

## Scale Later

- what is fine for now
- what can be improved later
- what should not be added yet

### Step 3

If the user is designing a small app, prefer one backend service and a simple database unless there is a clear reason not to.

## Rules

- Avoid advanced distributed-system advice unless the project truly needs it.
- Explain tradeoffs in plain language.
- Prefer a clear monolith over premature microservices.
- Call out which ideas are version 2 or version 3 work.
- Recommend one simple path first before mentioning alternatives.
