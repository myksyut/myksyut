```
$ whoami
Shota Miyaki — builds AI products, agent systems, and developer tools.
```

Product thinking, hands-on building. I care less about what a model can do in a demo
and more about the harness around it: who plans, who executes, and who gets to say "done".

&nbsp;

### Building

**[pev-harness](https://github.com/myksyut/pev-harness)** — a Claude Code plugin that runs coding tasks
through a Plan → Execute → Verify pipeline. An expensive model plans and orchestrates;
cheaper models (or Codex CLI) do the implementation and verification. The verifier runs as a
separate task, writes its own tests, and judges by exit code rather than the implementer's
self-report. Failures replan and retry up to three times before handing back to a human.

```
TRIAGE → PLAN → [ human gate ] → EXECUTE → VERIFY → done
          ↑                                  │
          └───────── fail → replan ──────────┘
```

&nbsp;

### Open source

- **[Mastra](https://github.com/mastra-ai/mastra)** — token-budgeted conversation history for agent memory.
  The [merged implementation](https://github.com/mastra-ai/mastra/pull/23238) builds on
  [my earlier PR](https://github.com/mastra-ai/mastra/pull/14116) and credits me as co-author.
- **[Chainlit](https://github.com/Chainlit/chainlit)** — Japanese localization ([#1720](https://github.com/Chainlit/chainlit/pull/1720)).

&nbsp;

### Exploring

`agent memory` · `coding harnesses` · `context management` · `AI-native dev environments`

&nbsp;

---

<sub>Japan · TypeScript and Python, mostly written alongside agents.</sub>
