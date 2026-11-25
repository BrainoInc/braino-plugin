---
name: get-started
description: Orient a connected Braino account and help the user search, brief, read, or record shared team knowledge.
---

# Get started with Braino

Use Braino only when the user wants information from, or wants to record information in, their
connected team knowledge.

Start by showing the workspaces and collections the connection can reach. Use the returned handles
for later searches and writes; never guess a handle or imply access outside the returned grants.

- Use `braino_search` for a focused question within one collection.
- Use `braino_brief` when the user wants the rules, prior decisions, active work, and background
  relevant to a task.
- Use `braino_get` for a known record or collection API resource.
- Use `braino_capture` to record a new decision, rule, action, log, evaluation, reference, state, or
  idea after the user has identified the destination collection.

Preserve Braino ids and source links in the answer so the user can inspect the underlying record.
If access is denied, explain which collection or workspace was unavailable; do not claim the missing
knowledge was searched.
