# AI Collective — Pilot goal

**Problem:** People with no programming knowledge and small AI usage budgets want to help build useful public software.

**Goal:** Make the smallest repeatable process for a volunteer to find a tiny task, copy a project-aware AI instruction, work with their own AI assistant, and submit a reviewed contribution.

## Version 0

1. GitHub Issues are the task queue and source of truth.
2. The page `index.html` helps a volunteer see example tasks and copy an AI prompt.
3. Every task must specify scope, acceptance criteria, a test, and a checkpoint.
4. Contributors use their own forks or branches; accepted pull requests update the project.
5. Public contributions benefit everyone, including people who don't participate.

## Non-goals

No central AI subscription pooling, AI account sharing, background agents, automated quotas, payments, database, or direct main-branch editing. GitHub is the coordination layer.

## Safety

Never store credentials in prompts or issues. Treat external contributions as untrusted. Review code before merging. This pilot does not claim that a task has been validated merely because an AI generated it.

## Pilot success criteria

A non-programmer can open `index.html`, copy a task instruction, use an AI tool of their choice, preserve partial work, and open a reviewable pull request.
