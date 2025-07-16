# Job to Agent Compiler Spec

## Purpose
Automatically convert job descriptions or project scopes into structured agent deployments.

## Input
- Raw JD or scope (uploaded or scraped)
- Operator profile/context

## Output
- Task breakdown
- Mapped agent list
- Pre-filled agent manifests

## Steps
1. Parse JD using GPT
2. Normalize task list by function category
3. Match tasks to agents
4. Scaffold manifests with operator preferences
5. Log or execute agent queue
