# Workflow Audit

How a **branch**, a **pull request**, an **issue**, and a **close-out** fit together end to end.

## Branch
Work happens on a working branch, cut from the default branch (here `main`), so unrelated or
work-in-progress changes never touch production directly. Keeping branches short-lived and
single-purpose makes every later step auditable.

## Pull request
A **pull request** is the review and merge path: the branch's changes are proposed against the
default branch, reviewed in a single shared view, and merged when the team agrees. Leaving the PR
open during review is normal — the audit artifact persists as a visible, discussion-tracked
state until a final call.

## Issue
An **issue** promises the *what* before the work starts: a checklist or a task with a comment trail.
The branch follows the issue; the PR captures the change behind it; closing the issue closes the
loop. Explicitly attaching follow-ups (sub-issues) keeps dependent work visible under one
parent.

## Close-out
Closure is deliberate, not accidental. The workflow is complete when:

1. The branch target PR is in place or merged.
2. The linked issue is resolved or properly closed with the reason noted.
3. Any outstanding follow-up lives in a separate, still-open sub-issue.

## Owner

| Field | Value |
|---|---|
| **Login** | HeziLiu |
| **Display name** | Hezi Liu |
| **Bio** | treat me like a tree |
| **Location** | Beijing/Guiyang |
| **Company** | BUPT/GZU |
| **Profile URL** | https://github.com/HeziLiu |
