# Awesome Claude Statusline [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of statusline / status bar projects for [Claude Code](https://docs.anthropic.com/en/docs/claude-code) CLI.

Claude Code supports a customizable status line at the bottom of your terminal via the `statusLine` hook. This list collects all known open-source implementations — from minimal one-liners to full dashboard HUDs.

---

## Contents

- [Featured](#featured)
- [Full-Featured](#full-featured)
- [Minimal / Lightweight](#minimal--lightweight)
- [Powerline / Themed](#powerline--themed)
- [Language-Specific Implementations](#language-specific-implementations)
- [Integrations & Dashboards](#integrations--dashboards)
- [Fun & Creative](#fun--creative)
- [Starship Integration](#starship-integration)
- [Tutorials & Tips](#tutorials--tips)
- [Contributing](#contributing)

---

## Featured

> ⭐ 100+ stars — the most popular projects in this space.

| Project | Stars | Description |
|---------|-------|-------------|
| [nilbuild/claude-statusline](https://github.com/nilbuild/claude-statusline) | ⭐ 1215 | Minimal Claude Code statusline setup — the most starred standalone statusline |
| [daniel3303/ClaudeCodeStatusLine](https://github.com/daniel3303/ClaudeCodeStatusLine) | ⭐ 489 | Model, tokens, rate limits, and git info in real-time |
| [uppinote20/claude-dashboard](https://github.com/uppinote20/claude-dashboard) | ⭐ 463 | Comprehensive status line plugin with context usage, API rate limits, and cost tracking |
| [rz1989s/claude-code-statusline](https://github.com/rz1989s/claude-code-statusline) | ⭐ 446 | Atomic precision statusline — flexible layouts, real-time cost tracking, MCP monitoring, themes |
| [Wangnov/claude-code-statusline-pro](https://github.com/Wangnov/claude-code-statusline-pro) | ⭐ 216 | Pro statusline for Claude Code (中文支持) |
| [kcchien/claude-code-statusline](https://github.com/kcchien/claude-code-statusline) | ⭐ 122 | Gradient progress bar, smart hiding, git status, cost tracking |
| [martinemde/starship-claude](https://github.com/martinemde/starship-claude) | ⭐ 109 | Claude statusline via Starship prompt |
| [mnapoli/claude-usage-bar](https://github.com/mnapoli/claude-usage-bar) | ⭐ 111 | Claude Code usage status bar |
| [wolfdenpublishing/pyccsl](https://github.com/wolfdenpublishing/pyccsl) | ⭐ 82 | PyCCSL ("pixel") — Python Claude Code Status Line |

## Full-Featured

> Rich status lines with multiple data segments (context, cost, rate limits, git, etc.)

| Project | Stars | Description |
|---------|-------|-------------|
| [ersinkoc/claude-statusline](https://github.com/ersinkoc/claude-statusline) | ⭐ 77 | Feature-rich Claude Code statusline |
| [shanraisshan/claude-code-status-line](https://github.com/shanraisshan/claude-code-status-line) | ⭐ 55 | Context window usage, git status, and model information |
| [loadbalance-sudachi-kun/claude-code-statusline](https://github.com/loadbalance-sudachi-kun/claude-code-statusline) | ⭐ 53 | Claude Code statusline with rate limit display |
| [danielmackay/claude-code-statusline](https://github.com/danielmackay/claude-code-statusline) | ⭐ 42 | Comprehensive Claude Code statusline |
| [AndyShaman/claude-statusline](https://github.com/AndyShaman/claude-statusline) | ⭐ 32 | Model, context bar, usage limits (H/W), git branch, session time — cross-platform |
| [glauberlima/claude-code-statusline](https://github.com/glauberlima/claude-code-statusline) | ⭐ 30 | Git state, context usage, model info and cost at a glance |
| [tzengyuxio/claude-statusline](https://github.com/tzengyuxio/claude-statusline) | ⭐ 28 | Two-line status line with context bar, usage tracking, Nerd Font icons |
| [hell0github/claude-statusline](https://github.com/hell0github/claude-statusline) | ⭐ 25 | Lightweight plugin — context, cost usage, session reset time |
| [bartleby/claude-statusline](https://github.com/bartleby/claude-statusline) | ⭐ 25 | 18 themes, rate limits, context tracking, ASCII Claude avatar |
| [vfmatzkin/claude-statusline](https://github.com/vfmatzkin/claude-statusline) | ⭐ 24 | Claude Code statusline |
| [egerev/claude-status-line](https://github.com/egerev/claude-status-line) | ⭐ 16 | Rich status bar — context, cache, rate limits, prompt estimates |
| [dwillitzer/claude-statusline](https://github.com/dwillitzer/claude-statusline) | ⭐ 13 | Multi-provider AI support — Claude, OpenAI, Gemini, xAI Grok with verified context limits |
| [aromanarguello/claude-statusline](https://github.com/aromanarguello/claude-statusline) | ⭐ 12 | Rich multi-line status line |
| [bitcoin21ideas/claude-statusline](https://github.com/bitcoin21ideas/claude-statusline) | ⭐ 12 | Context window zones, rate limit countdowns, git branch |
| [felipeelias/claude-statusline](https://github.com/felipeelias/claude-statusline) | ⭐ 11 | Configurable status line for Claude Code |
| [philipshurpik/claude-code-status-line](https://github.com/philipshurpik/claude-code-status-line) | ⭐ 11 | Color-coded status line |
| [anthonymarandon/claude-statusline](https://github.com/anthonymarandon/claude-statusline) | ⭐ 10 | Directory, git branch, model, cost, duration |
| [darrell-tw/claudecode-statusline](https://github.com/darrell-tw/claudecode-statusline) | ⭐ 10 | Statusline snippets — 2x promotion indicator and more |
| [moon1ite/claude-statusline](https://github.com/moon1ite/claude-statusline) | ⭐ 9 | Real-time tools, agents, and todos display |
| [SergioTEC/claude-statusline](https://github.com/SergioTEC/claude-statusline) | ⭐ 7 | Token usage, model, cost, plan limits — always visible |
| [MatteoSchifano/claude-statusline](https://github.com/MatteoSchifano/claude-statusline) | ⭐ 6 | Model info, context window, rate limits, cost tracking, session data |
| [FahimFBA/claudecode-statusline](https://github.com/FahimFBA/claudecode-statusline) | ⭐ 6 | Nice and useful statusline |
| [galpratama/claude-statusline](https://github.com/galpratama/claude-statusline) | ⭐ 6 | AI model info, costs, git status, dev environment details |
| [kolindes/Claude-StatusLine-Metrics](https://github.com/kolindes/Claude-StatusLine-Metrics) | ⭐ 5 | StatusLine metrics tracking |
| [CreatmanCEO/claude-statusline](https://github.com/CreatmanCEO/claude-statusline) | ⭐ 5 | Smart status line with VPS health, auto-focus — pure bash + jq (featured on Habr, 9.3K reads) |
| [TheoBrigitte/claude-statusline](https://github.com/TheoBrigitte/claude-statusline) | ⭐ 5 | Fast and configurable |
| [nguyentran4896/my-claude-statusline](https://github.com/nguyentran4896/my-claude-statusline) | ⭐ 5 | Git status, project info, model details, and token tracking |

## Minimal / Lightweight

> Simple, focused status lines — often a single file, zero dependencies.

| Project | Stars | Description |
|---------|-------|-------------|
| [simplpear/claude-statusline-lite](https://github.com/simplpear/claude-statusline-lite) | ⭐ 13 | Single Python file, zero dependencies — real rate limits |
| [JungHoonGhae/claude-statusline](https://github.com/JungHoonGhae/claude-statusline) | ⭐ 31 | Pure bash, no Node.js required |
| [susomejias/claude-statusline](https://github.com/susomejias/claude-statusline) | ⭐ 4 | Context window, rate limits, git info, session stats |
| [wenoa/claude-statusline](https://github.com/wenoa/claude-statusline) | ⭐ 4 | Quota usage in real time |
| [GiladShoham/my-claude-statusline](https://github.com/GiladShoham/my-claude-statusline) | ⭐ 4 | Personal claude status line |
| [nerdalytics/claude-statusline](https://github.com/nerdalytics/claude-statusline) | ⭐ 3 | Single-file zsh statusline |
| [millenniumbismay/minimal-claude-status-line](https://github.com/millenniumbismay/minimal-claude-status-line) | ⭐ 3 | Minimal, information-dense — context, tokens, rate limits, git, cost |
| [pessini/claudecode-status-line](https://github.com/pessini/claudecode-status-line) | ⭐ 3 | Simple, color-coded — install with one command via npx |
| [littlehsun/claude-statusline](https://github.com/littlehsun/claude-statusline) | ⭐ 2 | Lightweight, zero-cost, 100% accurate rate limit |

## Powerline / Themed

> Beautiful, themed statuslines with powerline segments, gradients, and custom aesthetics.

| Project | Stars | Description |
|---------|-------|-------------|
| [spences10/claude-statusline-powerline](https://github.com/spences10/claude-statusline-powerline) | ⭐ 31 | 🦋 Powerline-style with git integration, session tracking, cost monitoring |
| [Thewhey-Brian/claude-statusline-hud](https://github.com/Thewhey-Brian/claude-statusline-hud) | ⭐ 6 | btop-inspired HUD plugin — cross-platform, adaptive terminal width |
| [Felipeness/claude-statusline](https://github.com/Felipeness/claude-statusline) | ⭐ 2 | Visual editor in browser — 16 components, 5 themes, drag-and-drop (single Go binary) |
| [Buckits/claude-statusline](https://github.com/Buckits/claude-statusline) | ⭐ 2 | 2-line dashboard with gradient progress bar, GSD notifications |

## Language-Specific Implementations

### Go
| Project | Stars | Description |
|---------|-------|-------------|
| [jftuga/claude-statusline](https://github.com/jftuga/claude-statusline) | ⭐ 5 | Custom status line renderer written in Go |
| [h2ik/claude-statusline](https://github.com/h2ik/claude-statusline) | ⭐ 4 | Claude Statusline in Go |

### Rust
| Project | Stars | Description |
|---------|-------|-------------|
| [d1egoaz/claude-status-line](https://github.com/d1egoaz/claude-status-line) | ⭐ 1 | Fast Rust binary for rendering Claude Code's status line |
| [hravnx/claude-status-line](https://github.com/hravnx/claude-status-line) | ⭐ 0 | Simple Claude code status line in Rust |

### TypeScript / Deno
| Project | Stars | Description |
|---------|-------|-------------|
| [JerrettDavis/ClaudeStatusLineWidgets](https://github.com/JerrettDavis/ClaudeStatusLineWidgets) | ⭐ 4 | TypeScript statusline plugin — cache TTL, usage, session metrics |
| [wyattjoh/claude-status-line](https://github.com/wyattjoh/claude-status-line) | ⭐ 0 | TypeScript/Deno-based — project info, git branch, model, session time |

### Python
| Project | Stars | Description |
|---------|-------|-------------|
| [wolfdenpublishing/pyccsl](https://github.com/wolfdenpublishing/pyccsl) | ⭐ 82 | PyCCSL ("pixel") — Python Claude Code Status Line |
| [simplpear/claude-statusline-lite](https://github.com/simplpear/claude-statusline-lite) | ⭐ 13 | Single Python file, zero deps |

## Integrations & Dashboards

> Status lines integrated with tmux, Zellij, Discord, or standalone monitoring dashboards.

| Project | Stars | Description |
|---------|-------|-------------|
| [hoangsonww/Claude-Code-Agent-Monitor](https://github.com/hoangsonww/Claude-Code-Agent-Monitor) | ⭐ 370 | Real-time monitoring dashboard — SQLite, Node.js, React, WebSockets |
| [MackDing/claude-cli-session-monitor](https://github.com/MackDing/claude-cli-session-monitor) | ⭐ 1 | Real-time monitoring dashboard — token usage, session health, context window utilization |
| [ishefi/zellaude](https://github.com/ishefi/zellaude) | ⭐ 53 | Claude Code-aware status bar plugin for Zellij |
| [thoo/claude-code-zellij-status](https://github.com/thoo/claude-code-zellij-status) | ⭐ 37 | Monitor Claude Code across multiple Zellij panes via zjstatus |
| [BrunoJurkovic/claude-code-discord-status](https://github.com/BrunoJurkovic/claude-code-discord-status) | ⭐ 14 | Live Discord Rich Presence card for Claude Code sessions |
| [Pr0zak/claude-code-statusbar](https://github.com/Pr0zak/claude-code-statusbar) | ⭐ 0 | 2-line tmux status bar — real-time session data, API usage, reset countdowns |
| [ingredlabs/claude-status-line](https://github.com/ingredlabs/claude-status-line) | ⭐ 0 | Always-on-top overlay — works with CLI and VS Code plugin |

## Fun & Creative

| Project | Stars | Description |
|---------|-------|-------------|
| [terryso/ccpet](https://github.com/terryso/ccpet) | ⭐ 64 | 🐾 A virtual pet for your Claude Code status line |
| [alvinunreal/openpets](https://github.com/alvinunreal/openpets) | ⭐ 723 | Desktop pets for AI coding agents — connect via MCP, see live coding status |
| [seangreenidge949-lang/claude-statusline](https://github.com/seangreenidge949-lang/claude-statusline) | ⭐ 3 | Session stats + Bramblewick — a rabbit who actually pays attention 🐰 |
| [kyleledbetter/claudecode-statusline](https://github.com/kyleledbetter/claudecode-statusline) | ⭐ 4 | Branded mini status app with auto-sizing box borders and live metrics |

## Starship Integration

| Project | Stars | Description |
|---------|-------|-------------|
| [martinemde/starship-claude](https://github.com/martinemde/starship-claude) | ⭐ 109 | ✳ Claude statusline via Starship prompt |

## Tutorials & Tips

| Project | Stars | Description |
|---------|-------|-------------|
| [ykdojo/claude-code-tips](https://github.com/ykdojo/claude-code-tips) | ⭐ 8329 | 45 tips for Claude Code — includes custom status line scripts and more |

## Windows Support

| Project | Stars | Description |
|---------|-------|-------------|
| [lc1995/ClaudeCodeStatusLineWindows](https://github.com/lc1995/ClaudeCodeStatusLineWindows) | ⭐ 0 | Skill for configuring statusLine on Windows with PowerShell |

---

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

Found a project that's missing? [Open an issue](https://github.com/MackDing/awesome-claude-statusline/issues) or submit a PR.

## How to Add a Project

1. Fork this repository
2. Add your project to the appropriate category in `README.md`
3. Follow the format: `| [owner/repo](url) | ⭐ N | Short description |`
4. Submit a pull request

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is released into the public domain under CC0 1.0.
