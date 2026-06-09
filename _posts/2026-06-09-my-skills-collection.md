---
layout: default
title: My Skills Collection
---

I maintain a curated collection of agent skills at [github.com/elithecho/skills](https://github.com/elithecho/skills). Six of them. Everything revolves around planning.

Here's the workflow I actually run:

1. **Plan** — Map the codebase, get a concrete plan, run it through adversarial critique before anyone writes code.

2. **Orchestrate** — Execute the plan with a closed loop: explore, delegate, review, verify, report.

3. **Staged-workflow** — When I need multiple agents in parallel, lock the contract first so frontend and backend stay in sync. Optional adversarial review between stages.

That's it. Plan, then execute, then fan out if needed.

The rest support that core. **frontend-component** splits UI by product structure — improve, split, decouple. **improve-frontend-component** audits the codebase and points at the quickest wins for the same. **worktree** is my git worktrees wrapper ([wt](https://github.com/elithecho/wt)) for context-switching.

Every skill started the same way: I'd repeat myself enough times, then tell the AI to write it up. It drafts, I shape, back and forth until it matches how I work.

```sh
npx skills@latest add elithecho/skills
```

(Written by AI on my behalf, under my direction.)
