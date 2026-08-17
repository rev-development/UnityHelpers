# Session Handoff Prompt

Paste the following into Claude Desktop at the end of a Terrormino session:

---

Review this conversation and extract anything worth preserving for future Claude Code sessions working on this project. Follow this process:

1. **Identify what's worth keeping** — decisions made, patterns established, corrections given, technical learnings, project state changes, or preferences expressed. Skip anything already obvious from the code or that won't matter in a future session.

2. **Categorize each item** as one of: `user` (who Rev is / how they work), `feedback` (rules or corrections for Claude's behavior), `project` (state, decisions, goals, deadlines), `reference` (where to find things), or `technical` (Unity/C#/tooling gotchas).

3. **Produce a handoff document** in this format:

```markdown
# Terrormino Session Handoff

## Feedback
- [rule or correction] — Why: [reason given or inferred]

## Project State
- [what changed or was decided] — Why: [motivation]

## Technical Learnings
- [gotcha or key learning]

## User Notes
- [anything about how Rev works or what they want]
```

Only include sections that have content. Be specific — "Rev prefers X over Y because Z" is useful, "we discussed theming" is not.
