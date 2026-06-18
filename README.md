<div align="center">

# agent-canon

**Rules for AI agents that build software.**

*A short, durable operating canon — experience distilled into a set of rules an
agent (or a human) can carry into any codebase. No rule fits every case, agent, or
hand; take what serves, leave the rest.*

[**→ Read the Canon**](CANON.md) · [Adopt it](#adopt-it) · [Fork your own](#fork-your-own)

</div>

---

Most agent instructions are a pile of project trivia that the model skims and
forgets. This is the other thing: the *spine*. Not "use 2-space indent" — but
how to think, when to be bold, when to stop, how to verify, how not to lie to
yourself. The part that's true in every repo.

It was forged the hard way — by autonomous agents and their operator running a
relentless build → verify → critique → improve loop, and writing down what kept
saving them. Every rule earned its place by paying off, more than once.

## The rules

1. The loop improves the loop
2. Evidence before claim
3. Eat your own food
4. Systemic, never local
5. Consistency compounds
6. Code is a long-term inhabitant
7. Track everything
8. See the whole
9. Re-study before you touch
10. Hand off before the fog — keep the index lit
11. Simulate in the mind before the machine
12. Many minds, fresh eyes
13. Use every sense
14. Test in the widest sense — then use it yourself
15. Be your own adversary — then convene the council
16. Go for the root; watch the ripples
17. Repeatable, recorded, fed back
18. Every issue is a specimen — hunt the whole species
19. Hunt the corners; light the dark
20. Prefer the simplest thing that works
21. Make it work, then right, then fast
22. Say it plainly; fail it loudly
23. Match force to the stakes
24. Build for forever; let the foundation compound
25. Wield the loop; harness the harness
26. Use the best tools; forge what's missing; master both
27. Honesty first — even when it stings
28. Be bold; build, don't break
29. Learn from all — the others and the mirror
30. Speak plain; no sycophancy
31. Weigh every decision in the balance
32. You are concurrent — orchestrate, don't overreach
33. Never idle — every tick is an opportunity
34. Hold the north star; course-correct toward it
35. Do no harm; guard the irreversible

*The full text — one paragraph each — lives in [`CANON.md`](CANON.md).*

It has a shape. Rigor (**2, 4, 5, 14, 15, 18**) is balanced by restraint
(**20–24**), balanced again by boldness (**28**) — and **23**, *match force to
the stakes*, aims them all so the intensity lands where it matters and nowhere
else. Over all of it hangs **34**, the north star: rigor and process serve the
goal, never themselves; and **35**, the safety pole, brakes the autonomy so reach
never becomes harm. Read it once for the spine; return to it for the tension
between the rules.

## Adopt it

**1. Point at it (recommended).** Add one line to your agent's instructions file
(see the table) — or its system prompt:

```
Read and follow the canon operating rules at
https://raw.githubusercontent.com/huru-io/agent-canon/main/CANON.md
— these are rules, not suggestions.
```

That URL serves the raw Markdown, so any agent that can read a file or URL pulls
the canon itself and stays current as it's refined. (Human-readable view:
<https://github.com/huru-io/agent-canon/blob/main/CANON.md>.)

Claude Code users get a ready-made wrapper: this repo doubles as a skill. Copy it
(or just [`SKILL.md`](SKILL.md) + [`CANON.md`](CANON.md)) into
`~/.claude/skills/agent-canon/`, and Claude loads the live canon at the start of
engineering work.

| Tool | Instructions file |
|------|-------------------|
| Claude Code | `CLAUDE.md` |
| OpenAI Codex (and the cross-tool standard) | `AGENTS.md` |
| Gemini CLI | `GEMINI.md` |
| Cursor | `.cursor/rules/canon.mdc` (or legacy `.cursorrules`) |
| GitHub Copilot | `.github/copilot-instructions.md` |
| Anything else | its system prompt |

**2. Or vendor a fixed copy.** Prefer to pin a version or work offline? Copy
[`CANON.md`](CANON.md) into your repo and paste its contents into your instructions
file — or append it under a `# Operating canon` heading — to freeze the version you
reviewed. It's plain Markdown with a stable, grep-able shape — every rule is
`## N. Title` plus one paragraph — so you can extract any single rule by number or
name.

**3. Resolve conflicts the canon's way.** When a rule and a task conflict, prefer
the rule. When two rules conflict, prefer the whole over the part.

## Fork your own

This is released into the **public domain (CC0)** — no attribution required,
though a star or a link is always kind. Take it, cut it, bend it to your craft;
add the rules your own scars taught you and drop the ones that don't fit your
world. A canon is meant to be made yours. If you sharpen a rule, open a PR — the
best blade is the one many hands have honed.

## License

[CC0 1.0 Universal](LICENSE) — public domain dedication.
