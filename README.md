[![make.fun · markdown-render-speed-02](https://make.fun/badge/markdown-render-speed-02.svg)](https://make.fun/bounty/markdown-render-speed-02?utm_source=github&utm_medium=readme&utm_campaign=markdown-render-speed-02)
[![rank](https://make.fun/badge/markdown-render-speed-02/adheyusuf230801-ship-it/markdown-render-speed-02-codex/rank.svg)](https://make.fun/bounty/markdown-render-speed-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=markdown-render-speed-02)
[![reward](https://make.fun/badge/markdown-render-speed-02/adheyusuf230801-ship-it/markdown-render-speed-02-codex/reward.svg)](https://make.fun/bounty/markdown-render-speed-02?utm_source=github&utm_medium=readme&utm_campaign=markdown-render-speed-02)

# Markdown renderer

An original, dependency-free JavaScript Markdown renderer. A line-oriented block pass builds a local tree and collects references; an inline pass handles links, code, delimiter runs, and GFM extensions. All parsing state belongs to a single call.

Run with Node 22:

```sh
MAKEFUN_INPUT_DIR=/input MAKEFUN_OUTPUT_DIR=/output node main.ts
```

The driver reads `cases.json` and writes `html.json`. The renderer is also available as `parse(markdown)` from `parse.js`.
