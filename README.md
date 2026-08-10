# Awesome Claude Code Statusline [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

**The most comprehensive collection of Claude Code statusline and status bar projects on GitHub.**

> 80+ open-source statusline implementations for [Claude Code CLI](https://docs.anthropic.com/en/docs/claude-code) — customize your terminal with real-time token usage, rate limits, cost tracking, git status, and more.

[![GitHub stars](https://img.shields.io/github/stars/MackDing/awesome-claude-statusline?style=social)](https://github.com/MackDing/awesome-claude-statusline)
[![Last Updated](https://img.shields.io/badge/last%20updated-May%202026-brightgreen)](https://github.com/MackDing/awesome-claude-statusline)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/MackDing/awesome-claude-statusline/pulls)

## What is Claude Code Statusline?

**Claude Code** is Anthropic's official CLI agent for software development. It supports a **customizable status line** at the bottom of your terminal via the `statusLine` hook in `.claude/settings.json`. The status line displays real-time session information like:

- 📊 **Context window usage** — how much of the token limit you've consumed
- ⏱️ **Rate limit tracking** — 5-hour and 7-day usage bars with reset countdowns
- 💰 **Cost monitoring** — session and daily spend in real-time
- 🔀 **Git integration** — branch name, dirty state, commit info
- 🤖 **Model info** — which Claude model (Sonnet, Opus, Haiku) is active
- 🎨 **Themes & styling** — powerline segments, gradients, Nerd Font icons

This awesome list collects **every known open-source Claude Code statusline project** — from minimal bash one-liners to full monitoring dashboards.

---

## Contents

- [Featured (100+ ⭐)](#featured)
- [Full-Featured Statuslines](#full-featured-statuslines)
- [Minimal & Lightweight](#minimal--lightweight)
- [Powerline & Themed](#powerline--themed)
- [Language-Specific Implementations](#language-specific-implementations)
  - [Go](#go)
  - [Rust](#rust)
  - [TypeScript / Deno](#typescript--deno)
  - [Python](#python)
- [Monitoring Dashboards & Integrations](#monitoring-dashboards--integrations)
- [Zellij & Tmux Plugins](#zellij--tmux-plugins)
- [Fun & Creative](#fun--creative)
- [Starship Prompt Integration](#starship-prompt-integration)
- [Tutorials & Tips](#tutorials--tips)
- [Windows Support](#windows-support)
- [FAQ](#faq)
- [Contributing](#contributing)

---

## Featured

> ⭐ 100+ stars — the most popular Claude Code statusline projects.

| Project | Stars | Description |
|---------|-------|-------------|
| [nilbuild/claude-statusline](https://github.com/nilbuild/claude-statusline) | ⭐ 1215 | Minimal Claude Code statusline — the most starred standalone statusline project |
| [daniel3303/ClaudeCodeStatusLine](https://github.com/daniel3303/ClaudeCodeStatusLine) | ⭐ 489 | Shows model, tokens, rate limits, and git info in real-time |
| [uppinote20/claude-dashboard](https://github.com/uppinote20/claude-dashboard) | ⭐ 463 | Comprehensive Claude Code dashboard plugin — context usage, API rate limits, cost tracking |
| [rz1989s/claude-code-statusline](https://github.com/rz1989s/claude-code-statusline) | ⭐ 446 | Atomic precision statusline — flexible layouts, real-time cost tracking, MCP monitoring, beautiful themes |
| [Wangnov/claude-code-statusline-pro](https://github.com/Wangnov/claude-code-statusline-pro) | ⭐ 216 | Pro statusline for Claude Code with 中文支持 (Chinese language support) |
| [kcchien/claude-code-statusline](https://github.com/kcchien/claude-code-statusline) | ⭐ 122 | Gradient progress bar, smart hiding, git status, cost tracking |
| [mnapoli/claude-usage-bar](https://github.com/mnapoli/claude-usage-bar) | ⭐ 111 | Clean Claude Code usage status bar |
| [martinemde/starship-claude](https://github.com/martinemde/starship-claude) | ⭐ 109 | Claude Code statusline via Starship prompt framework |
| [wolfdenpublishing/pyccsl](https://github.com/wolfdenpublishing/pyccsl) | ⭐ 82 | PyCCSL ("pixel") — Python-based Claude Code Status Line |

## Full-Featured Statuslines

> Rich Claude Code status lines with multiple data segments — context window, cost, rate limits, git branch, model info, and more.

| Project | Stars | Description |
|---------|-------|-------------|
| [ersinkoc/claude-statusline](https://github.com/ersinkoc/claude-statusline) | ⭐ 77 | Feature-rich Claude Code statusline |
| [shanraisshan/claude-code-status-line](https://github.com/shanraisshan/claude-code-status-line) | ⭐ 55 | Context window usage, git status, and model information |
| [loadbalance-sudachi-kun/claude-code-statusline](https://github.com/loadbalance-sudachi-kun/claude-code-statusline) | ⭐ 53 | Claude Code statusline with rate limit display |
| [danielmackay/claude-code-statusline](https://github.com/danielmackay/claude-code-statusline) | ⭐ 42 | Comprehensive Claude Code statusline with all key metrics |
| [AndyShaman/claude-statusline](https://github.com/AndyShaman/claude-statusline) | ⭐ 32 | Model, context bar, usage limits (H/W), git branch, session time — cross-platform |
| [glauberlima/claude-code-statusline](https://github.com/glauberlima/claude-code-statusline) | ⭐ 30 | Git state, context usage, model info and cost at a glance |
| [tzengyuxio/claude-statusline](https://github.com/tzengyuxio/claude-statusline) | ⭐ 28 | Two-line status line with context bar, usage tracking, Nerd Font icons |
| [hell0github/claude-statusline](https://github.com/hell0github/claude-statusline) | ⭐ 25 | Lightweight plugin — context, cost usage, session reset time |
| [bartleby/claude-statusline](https://github.com/bartleby/claude-statusline) | ⭐ 25 | 18 themes, rate limits, context tracking, ASCII Claude avatar |
| [vfmatzkin/claude-statusline](https://github.com/vfmatzkin/claude-statusline) | ⭐ 24 | Claude Code statusline with comprehensive metrics |
| [egerev/claude-status-line](https://github.com/egerev/claude-status-line) | ⭐ 16 | Rich status bar — context, cache, rate limits, prompt estimates |
| [dwillitzer/claude-statusline](https://github.com/dwillitzer/claude-statusline) | ⭐ 13 | Multi-provider AI support — Claude, OpenAI, Gemini, xAI Grok with verified context limits |
| [aromanarguello/claude-statusline](https://github.com/aromanarguello/claude-statusline) | ⭐ 12 | Rich multi-line status line for Claude Code |
| [bitcoin21ideas/claude-statusline](https://github.com/bitcoin21ideas/claude-statusline) | ⭐ 12 | Context window zones, rate limit countdowns, git branch display |
| [felipeelias/claude-statusline](https://github.com/felipeelias/claude-statusline) | ⭐ 11 | Configurable status line for Claude Code CLI |
| [philipshurpik/claude-code-status-line](https://github.com/philipshurpik/claude-code-status-line) | ⭐ 11 | Color-coded status line with visual indicators |
| [anthonymarandon/claude-statusline](https://github.com/anthonymarandon/claude-statusline) | ⭐ 10 | Shows directory, git branch, model, cost, duration |
| [darrell-tw/claudecode-statusline](https://github.com/darrell-tw/claudecode-statusline) | ⭐ 10 | Statusline snippets — 2x promotion indicator and more |
| [moon1ite/claude-statusline](https://github.com/moon1ite/claude-statusline) | ⭐ 9 | Real-time tools, agents, and todos display |
| [SergioTEC/claude-statusline](https://github.com/SergioTEC/claude-statusline) | ⭐ 7 | Token usage, model, cost, plan limits — always visible at terminal bottom |
| [MatteoSchifano/claude-statusline](https://github.com/MatteoSchifano/claude-statusline) | ⭐ 6 | Model info, context window, rate limits, cost tracking, session data |
| [FahimFBA/claudecode-statusline](https://github.com/FahimFBA/claudecode-statusline) | ⭐ 6 | Nice and useful Claude Code statusline |
| [galpratama/claude-statusline](https://github.com/galpratama/claude-statusline) | ⭐ 6 | AI model info, costs, git status, dev environment details |
| [kolindes/Claude-StatusLine-Metrics](https://github.com/kolindes/Claude-StatusLine-Metrics) | ⭐ 5 | StatusLine metrics tracking for Claude Code |
| [CreatmanCEO/claude-statusline](https://github.com/CreatmanCEO/claude-statusline) | ⭐ 5 | Smart status line with VPS health, auto-focus — pure bash + jq (featured on Habr, 9.3K reads) |
| [TheoBrigitte/claude-statusline](https://github.com/TheoBrigitte/claude-statusline) | ⭐ 5 | Fast and configurable Claude Code statusline |
| [nguyentran4896/my-claude-statusline](https://github.com/nguyentran4896/my-claude-statusline) | ⭐ 5 | Git status, project info, model details, and token tracking |

## Minimal & Lightweight

> Simple, zero-dependency Claude Code status lines — often a single file. Perfect for getting started quickly.

| Project | Stars | Description |
|---------|-------|-------------|
| [JungHoonGhae/claude-statusline](https://github.com/JungHoonGhae/claude-statusline) | ⭐ 31 | Rich statusline for Claude Code — pure bash, no Node.js required |
| [simplpear/claude-statusline-lite](https://github.com/simplpear/claude-statusline-lite) | ⭐ 13 | Single Python file, zero dependencies — real rate limits |
| [susomejias/claude-statusline](https://github.com/susomejias/claude-statusline) | ⭐ 4 | Context window, rate limits, git info, session stats |
| [wenoa/claude-statusline](https://github.com/wenoa/claude-statusline) | ⭐ 4 | Displays quota usage in real time |
| [GiladShoham/my-claude-statusline](https://github.com/GiladShoham/my-claude-statusline) | ⭐ 4 | Personal Claude Code status line config |
| [nerdalytics/claude-statusline](https://github.com/nerdalytics/claude-statusline) | ⭐ 3 | Single-file zsh statusline for Claude Code |
| [millenniumbismay/minimal-claude-status-line](https://github.com/millenniumbismay/minimal-claude-status-line) | ⭐ 3 | Minimal, information-dense — context, tokens, rate limits, git, cost |
| [pessini/claudecode-status-line](https://github.com/pessini/claudecode-status-line) | ⭐ 3 | Simple, color-coded — install with one command via npx |
| [littlehsun/claude-statusline](https://github.com/littlehsun/claude-statusline) | ⭐ 2 | Lightweight, zero-cost, 100% accurate rate limit tracking |

## Powerline & Themed

> Beautiful Claude Code statuslines with powerline segments, gradient colors, and custom themes.

| Project | Stars | Description |
|---------|-------|-------------|
| [spences10/claude-statusline-powerline](https://github.com/spences10/claude-statusline-powerline) | ⭐ 31 | 🦋 Powerline-style with git integration, session tracking, cost monitoring |
| [Thewhey-Brian/claude-statusline-hud](https://github.com/Thewhey-Brian/claude-statusline-hud) | ⭐ 6 | btop-inspired HUD plugin — cross-platform with adaptive terminal width |
| [Felipeness/claude-statusline](https://github.com/Felipeness/claude-statusline) | ⭐ 2 | Visual editor in browser — 16 components, 5 themes, drag-and-drop (single Go binary) |
| [Buckits/claude-statusline](https://github.com/Buckits/claude-statusline) | ⭐ 2 | 2-line dashboard with gradient progress bar and GSD notifications |

## Language-Specific Implementations

> Claude Code statusline projects written in Go, Rust, TypeScript, Python, and other languages beyond bash/shell.

### Go

| Project | Stars | Description |
|---------|-------|-------------|
| [jftuga/claude-statusline](https://github.com/jftuga/claude-statusline) | ⭐ 5 | Custom Claude Code status line renderer written in Go |
| [h2ik/claude-statusline](https://github.com/h2ik/claude-statusline) | ⭐ 4 | Claude Code statusline in Go |

### Rust

| Project | Stars | Description |
|---------|-------|-------------|
| [d1egoaz/claude-status-line](https://github.com/d1egoaz/claude-status-line) | ⭐ 1 | Fast Rust binary for rendering Claude Code's status line |
| [hravnx/claude-status-line](https://github.com/hravnx/claude-status-line) | ⭐ 0 | Simple Claude Code status line in Rust |

### TypeScript / Deno

| Project | Stars | Description |
|---------|-------|-------------|
| [JerrettDavis/ClaudeStatusLineWidgets](https://github.com/JerrettDavis/ClaudeStatusLineWidgets) | ⭐ 4 | TypeScript statusline plugin — cache TTL, usage, session metrics |
| [wyattjoh/claude-status-line](https://github.com/wyattjoh/claude-status-line) | ⭐ 0 | TypeScript/Deno-based — project info, git branch, model details, session time |

### Python

| Project | Stars | Description |
|---------|-------|-------------|
| [wolfdenpublishing/pyccsl](https://github.com/wolfdenpublishing/pyccsl) | ⭐ 82 | PyCCSL ("pixel") — full-featured Python Claude Code Status Line |
| [simplpear/claude-statusline-lite](https://github.com/simplpear/claude-statusline-lite) | ⭐ 13 | Single Python file, zero dependencies |

## Monitoring Dashboards & Integrations

> Standalone monitoring dashboards, Discord Rich Presence, and other integrations for tracking Claude Code sessions.

| Project | Stars | Description |
|---------|-------|-------------|
| [hoangsonww/Claude-Code-Agent-Monitor](https://github.com/hoangsonww/Claude-Code-Agent-Monitor) | ⭐ 370 | Real-time Claude Code monitoring dashboard — SQLite, Node.js, React, WebSockets |
| [MackDing/claude-cli-session-monitor](https://github.com/MackDing/claude-cli-session-monitor) | ⭐ 1 | Real-time monitoring dashboard — token usage, session health, context window utilization |
| [BrunoJurkovic/claude-code-discord-status](https://github.com/BrunoJurkovic/claude-code-discord-status) | ⭐ 14 | Live Discord Rich Presence card showing Claude Code session activity |
| [ingredlabs/claude-status-line](https://github.com/ingredlabs/claude-status-line) | ⭐ 0 | Always-on-top overlay — works with both CLI and VS Code plugin |

## Zellij & Tmux Plugins

> Claude Code status bar plugins for terminal multiplexers like Zellij and tmux.

| Project | Stars | Description |
|---------|-------|-------------|
| [ishefi/zellaude](https://github.com/ishefi/zellaude) | ⭐ 53 | Claude Code-aware status bar plugin for Zellij |
| [thoo/claude-code-zellij-status](https://github.com/thoo/claude-code-zellij-status) | ⭐ 37 | Monitor Claude Code across multiple Zellij panes via zjstatus |
| [Pr0zak/claude-code-statusbar](https://github.com/Pr0zak/claude-code-statusbar) | ⭐ 0 | 2-line tmux status bar — real-time session data, API usage, reset countdowns |

## Fun & Creative

> Unique and creative approaches to Claude Code status display — virtual pets, desktop companions, and more.

| Project | Stars | Description |
|---------|-------|-------------|
| [alvinunreal/openpets](https://github.com/alvinunreal/openpets) | ⭐ 723 | Desktop pets for AI coding agents — connect Claude Code via MCP, see live coding status |
| [terryso/ccpet](https://github.com/terryso/ccpet) | ⭐ 64 | 🐾 A virtual pet that lives in your Claude Code status line |
| [krayong/ccsidekick](https://github.com/krayong/ccsidekick) | ⭐ 20 | Reactive ASCII character that comments on your session, with 33 widgets and 75+ themes |
| [kyleledbetter/claudecode-statusline](https://github.com/kyleledbetter/claudecode-statusline) | ⭐ 4 | Branded mini status app with auto-sizing box borders and live metrics |
| [seangreenidge949-lang/claude-statusline](https://github.com/seangreenidge949-lang/claude-statusline) | ⭐ 3 | Session stats + Bramblewick — a rabbit who actually pays attention 🐰 |

## Starship Prompt Integration

> Use Claude Code statusline with the [Starship](https://starship.rs/) cross-shell prompt.

| Project | Stars | Description |
|---------|-------|-------------|
| [martinemde/starship-claude](https://github.com/martinemde/starship-claude) | ⭐ 109 | ✳ Claude Code statusline via Starship prompt framework |

## Tutorials & Tips

> Guides and tips that include Claude Code statusline configuration.

| Project | Stars | Description |
|---------|-------|-------------|
| [ykdojo/claude-code-tips](https://github.com/ykdojo/claude-code-tips) | ⭐ 8329 | 45 tips for Claude Code — includes custom status line scripts, system prompt optimization, and more |

## Windows Support

> Claude Code statusline projects with explicit Windows / PowerShell support.

| Project | Stars | Description |
|---------|-------|-------------|
| [lc1995/ClaudeCodeStatusLineWindows](https://github.com/lc1995/ClaudeCodeStatusLineWindows) | ⭐ 0 | Skill for configuring Claude Code statusLine on Windows with PowerShell |

---

## How to Set Up a Claude Code Statusline

Add this to your `~/.claude/settings.json`:

```json
{
  "hooks": {
    "StatusLine": [
      {
        "matcher": "",
        "hooks": [
          {
            "type": "command",
            "command": "/path/to/your/statusline-script.sh"
          }
        ]
      }
    ]
  }
}
```

Most projects in this list include their own installation instructions. Check each project's README for specific setup steps.

---

## FAQ

### What is the best Claude Code statusline?

The most popular is [nilbuild/claude-statusline](https://github.com/nilbuild/claude-statusline) with 1200+ stars. For a feature-rich option, try [daniel3303/ClaudeCodeStatusLine](https://github.com/daniel3303/ClaudeCodeStatusLine) (489 ⭐) or [rz1989s/claude-code-statusline](https://github.com/rz1989s/claude-code-statusline) (446 ⭐). For Python users, [wolfdenpublishing/pyccsl](https://github.com/wolfdenpublishing/pyccsl) (82 ⭐) is excellent.

### How do I customize Claude Code's status bar?

Claude Code reads the `statusLine` hook from `~/.claude/settings.json`. You point it to any script (bash, Python, Go, Rust, etc.) that outputs formatted text. The script receives session data as JSON via stdin and returns styled status text.

### Can I track Claude Code API costs in the terminal?

Yes — many statuslines in this list display real-time cost tracking. Projects like [uppinote20/claude-dashboard](https://github.com/uppinote20/claude-dashboard), [rz1989s/claude-code-statusline](https://github.com/rz1989s/claude-code-statusline), and [hell0github/claude-statusline](https://github.com/hell0github/claude-statusline) show per-session and daily costs.

### How do I see Claude Code rate limits in my terminal?

Most statuslines display 5-hour and 7-day rate limit bars with reset countdowns. Check the [Featured](#featured) section for the most polished implementations.

### Does Claude Code statusline work on Windows?

Most statuslines are built for macOS/Linux. For Windows support, see [lc1995/ClaudeCodeStatusLineWindows](https://github.com/lc1995/ClaudeCodeStatusLineWindows) or use WSL with any Linux-compatible statusline.

### How do I monitor multiple Claude Code sessions?

For multi-session monitoring, check out [hoangsonww/Claude-Code-Agent-Monitor](https://github.com/hoangsonww/Claude-Code-Agent-Monitor) (web dashboard) or [thoo/claude-code-zellij-status](https://github.com/thoo/claude-code-zellij-status) (Zellij panes).

---

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

Found a project that's missing? [Open an issue](https://github.com/MackDing/awesome-claude-statusline/issues) or submit a PR.

### How to Add a Project

1. Fork this repository
2. Add your project to the appropriate category in `README.md`
3. Follow the format: `| [owner/repo](url) | ⭐ N | Short description |`
4. Submit a pull request

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is released into the public domain under [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/).
