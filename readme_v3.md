# Ergo Volunteer Quick Task (Works with any LLM)

You will get:
1) an automatic skill/time mini-interview
2) exactly ONE real task that exists in the TSV snapshot
3) kid-simple step-by-step instructions
4) exact instructions where to post your finished work (Telegram/GitHub/THIS CHAT), with zero “I will forward…” nonsense

**Weekly accuracy rule (only when you ask for “weekly/current” content):**
The LLM must use only sources from the last 7 days, or explicitly switch to a *Live Snapshot* (dashboards) if no qualifying weekly events are found.

## How to use (2 minutes)
1) Open any LLM (ChatGPT, Claude, Gemini, etc.)
2) Copy-paste the full content of `one-paste.txt` into the chat and send it.
3) Answer the 4 profile questions.
4) The TSV file `project_tasks_prioritized.tsv` is already provided with the paste. **Do not re-upload or re-paste it.**
   - Only if your LLM truly cannot access attached files: then paste the full TSV contents when (and only when) it asks.
5) You will receive ONE task + exact posting instructions + a copy-paste template.

## TSV schema expectations (important)
The picker expects the TSV to have at least these columns:
ActivityBucket, Department, Project, Status, Archive?, Category, Language, GitHub, Telegram, Linked Project, Description, Notes

If you rename columns, update `one-paste.txt` and `systemprompt.txt` accordingly.

## Files on this page
- one-paste.txt  (paste this into any LLM)
- project_tasks_prioritized.tsv  (authoritative task list; do NOT re-paste unless your LLM cannot access attachments)
- systemprompt.txt (optional, only if your LLM supports system prompts)

## Updating
Keep `project_tasks_prioritized.tsv` updated regularly. The LLM must only pick tasks that exist in the TSV.
