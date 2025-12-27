# Ergo_taskmaster
A drag &amp; drop tool for volunteers on Ergo


What this project does

This repo is a copy-paste onboarding + task-assignment workflow for volunteers. You drop an up-to-date TSV/CSV task board into a chat with any LLM, and the prompt pack makes the model:

ask for a tiny volunteer profile (skills / time / solo-team / languages)

pick one real task from the table (no hallucinated work)

output a 30-minute, step-by-step checklist that a beginner can follow

clearly state where the volunteer should publish the result (e.g., GitHub issue/PR, Telegram thread, doc)

The goal is to turn “I want to help” into a concrete contribution with minimal friction, while keeping the model honest about what it can and can’t do.

---

**Note:** The GitHub repository name currently has a typo ("Ergo_tastmaster" instead of "Ergo_taskmaster"). See [REPOSITORY_RENAME_NEEDED.md](./REPOSITORY_RENAME_NEEDED.md) for details on the required fix.
