# `/hemingway` — write it dense

`/hemingway` is a Claude Code skill that rewrites text in a precise, minimalist style modeled on Ernest Hemingway's "Iceberg Theory" and plain-language business writing. Point it at a draft, or type it after a bloated AI response, and it strips the text down to maximum information in minimum words.

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

Then type `/hemingway` in Claude Code to rewrite a draft or your own last message.

## License

MIT
