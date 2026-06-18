---
name: agent-canon
description: Load and apply "The Canon" — a short, durable set of operating rules for AI agents (and humans) that build software. This skill should be used at the start of any coding, debugging, code review, planning, refactoring, or autonomous engineering session to ground behavior in the canon's principles (evidence before claim, systemic fixes over local patches, simulate before building, match force to the stakes, guard the irreversible, and more). It fetches the latest canon from its live URL, with a bundled offline copy as fallback.
---

# Agent Canon

Ground engineering work in The Canon — a compact, durable set of operating rules
for building software. Keep this file lean and stable; the rules themselves live
in `CANON.md` and are refined over time.

## Load the canon

Fetch the live file (always the latest) and read it in full before proceeding:

```
https://raw.githubusercontent.com/huru-io/agent-canon/main/CANON.md
```

If the URL cannot be reached (offline or no web access), read the bundled
`CANON.md` sitting alongside this file instead.

## Apply the canon

- Treat every rule as a rule, not a suggestion.
- When a rule and a task conflict, prefer the rule. When two rules conflict,
  prefer the whole over the part.
- Read "you" as "your collective": fork subagents and parallel threads where the
  work allows, and weave their results back (canon rule 32).
- Re-read the canon at the start of substantial work rather than relying on
  memory — it changes as it is sharpened.

Full text, context, and license (CC0): <https://github.com/huru-io/agent-canon>
