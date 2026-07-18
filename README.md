Most AI-coding advice comes from solo builders shipping greenfield demos. I run engineering for
regulated, safety-critical enterprise systems — 100+ engineers, multi-account infrastructure,
auditors who read the commit history — and I ship AI-assisted code there every day. The
difference between those two worlds is verification: a demo can assert, production has to prove.
Everything on this account is that one thesis applied in public: AI can write most of the code,
but only a verification layer — tests that actually run, claims that trace to evidence, gates
that refuse to pass what they can't prove — makes it shippable. The recipes are the *what*, the
framework is the *how*, and the scorecards are the *receipts*.

## Start here

| Repo | What it is |
|---|---|
| [claude-code-recipes](https://github.com/sgharlow/claude-code-recipes) | 100 field-tested recipes for shipping real work with Claude Code — the *what* |
| [ai-control-framework](https://github.com/sgharlow/ai-control-framework) | The verification methodology: deployment-readiness scoring, evidence-backed gates — the *how* |
| [orchestra-lite](https://github.com/sgharlow/orchestra-lite) | Parallel multi-agent orchestration for real repos — the *scale* |
| [ai-pr-bot](https://github.com/sgharlow/ai-pr-bot) | PR-time enforcement: the gates run where the code lands — the *enforcement* |
| [skillcrossroads](https://github.com/sgharlow/skillcrossroads) | Evidence-cited grading for Claude Code artifacts, live at [skillcrossroads.com](https://skillcrossroads.com) — the *grade* |
| [distraction](https://github.com/sgharlow/distraction) | A live civic-tech product built end-to-end with the method — the *case study* |

The tools above form **[Workshown](https://sgharlow.github.io/ai-control-framework/)** — show
your work. The evidence behind the claims (including the unflattering numbers) lives in
[benchmarks/](https://github.com/sgharlow/ai-control-framework/tree/main/benchmarks).

VP of Engineering, 30 years building software, author of
[*The Foreign Mind: Ender's Reframe for AI Leadership*](https://www.amazon.com/dp/B0GYN5CQ9Z).
Everything here follows one rule: no claim without a check you can run.

> **How this account runs:** one maintenance block a week across the pinned repos · one release
> a month across the Workshown line · at most one new repo per quarter, and only after the last
> one earned it · quarterly review against a public metrics table.

**Contact:** [sgharlow@gmail.com](mailto:sgharlow@gmail.com) · [LinkedIn](https://www.linkedin.com/in/stevengharlow/)
