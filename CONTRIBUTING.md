# Contribute with any AI assistant

You do not need to know how to program.

1. Open the [GitHub Issues](https://github.com/klajdib12-lab/Hello-codex/issues) and choose a tiny, unblocked task.
2. Read the task instructions and the [project goal](GOAL.md).
3. Copy the task's AI instruction. Paste it into your own AI assistant. **Do not share your AI password, API key, subscription, or session.**
4. Ask your AI to work only on the specified files. If it can use GitHub with your permission, work in your fork/branch; otherwise ask it for a patch or the full changed file.
5. Run the stated test if possible. If you can't run it, say that honestly. Save an incomplete result and a checkpoint when you stop.
6. Open a Pull Request describing your changes and tests. Use `Closes #ISSUE` in the PR body to link its task. Do not merge your own work into `main`.

## A prompt you can paste into your AI

> I want to volunteer on this GitHub issue: [ISSUE URL]. Read GOAL.md and the issue. Explain the smallest deliverable, make only the requested change, check the acceptance criteria, and tell me what was actually tested. Do not request secrets or give unrelated commands. If you cannot use my GitHub connection, produce a patch or files I can submit. If usage ends early, leave: Done / Tested / Remaining / File or branch location. Never claim unfinished work is complete.

## Reviewers

Do not run untrusted scripts with privileged credentials. Require human review for code and dependencies. Keep the protected `main` branch under maintainer control. PR checks and branch protection need to be enabled separately by repository administrators.
