# hemingway — straight to the point

`hemingway` is a set of writing principles modeled on Ernest Hemingway's "Iceberg Theory" and plain-language business writing: maximum information in minimum words. It's not a slash command you invoke on a single draft — it's a standing style Claude follows by default once you give it these rules.

## How to use this

1. **Standing instructions (intended use).** Paste the body of `SKILL.md` into your assistant's custom instructions — Claude's general settings, a project's `CLAUDE.md`, or a system prompt — so it writes this way in every conversation, not just when asked.
2. **As a Claude Code skill.** Install it below and Claude applies the rules automatically when a task involves writing or rewriting prose. There's no `/hemingway` command to type.

## Rules

- **Concrete over abstract** — no abstract noun phrases or meta-terminology ("reusable assets," "synergistic mechanisms"). Describe what literally happens.
- **No meta-commentary** — no explaining the writing itself ("In summary...", "It is important to note..."). Just state the facts.
- **Short, declarative sentences** — one or two ideas per sentence. Simple coordination (*and*, *but*) over subordination (*although*, *whereas*). Key points land as short, punchy single clauses.
- **Banned vocabulary** — words like *leverage, optimize, utilize, streamline, framework, paradigm, landscape, nuanced, comprehensive, delve, mechanism* are forbidden. Find a plainer word or cut it.
- **Tone** — professional, direct, unadorned. Gets to the point immediately.

## Install

Copy `SKILL.md` into your Claude Code skills directory:

```sh
mkdir -p ~/.claude/skills/hemingway
cp SKILL.md ~/.claude/skills/hemingway/SKILL.md
```

Claude applies it automatically to writing tasks — no command to type.

## License

MIT
