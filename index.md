---
layout: default
title: "Awesome Claude Code Statusline — 80+ Open Source Status Bar Projects"
description: "The most comprehensive collection of Claude Code statusline projects on GitHub. Find the best status bar for your Claude Code CLI terminal — token usage, rate limits, cost tracking, git status, themes and more."
---

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "SoftwareSourceCode",
  "name": "Awesome Claude Code Statusline",
  "description": "A curated list of 80+ open-source Claude Code statusline and status bar projects for the Claude Code CLI terminal",
  "url": "https://github.com/MackDing/awesome-claude-statusline",
  "codeRepository": "https://github.com/MackDing/awesome-claude-statusline",
  "programmingLanguage": ["Bash", "Python", "Go", "Rust", "TypeScript"],
  "applicationCategory": "DeveloperApplication",
  "keywords": "claude code, statusline, status bar, claude code cli, anthropic, terminal, developer tools, awesome list",
  "author": {
    "@type": "Person",
    "name": "MackDing",
    "url": "https://github.com/MackDing"
  },
  "about": {
    "@type": "Thing",
    "name": "Claude Code",
    "description": "Anthropic's official CLI agent for software development",
    "url": "https://docs.anthropic.com/en/docs/claude-code"
  }
}
</script>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What is the best Claude Code statusline?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The most popular is nilbuild/claude-statusline with 1200+ stars. For feature-rich options, try daniel3303/ClaudeCodeStatusLine (489 stars) or rz1989s/claude-code-statusline (446 stars). For Python users, wolfdenpublishing/pyccsl (82 stars) is excellent."
      }
    },
    {
      "@type": "Question",
      "name": "How do I customize Claude Code's status bar?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Claude Code reads the statusLine hook from ~/.claude/settings.json. Point it to any script (bash, Python, Go, Rust) that outputs formatted text. The script receives session data as JSON via stdin and returns styled status text."
      }
    },
    {
      "@type": "Question",
      "name": "Can I track Claude Code API costs in the terminal?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes — many statuslines display real-time cost tracking. Projects like uppinote20/claude-dashboard, rz1989s/claude-code-statusline, and hell0github/claude-statusline show per-session and daily costs."
      }
    },
    {
      "@type": "Question",
      "name": "How do I see Claude Code rate limits in my terminal?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Most statuslines display 5-hour and 7-day rate limit bars with reset countdowns. The Featured section of this list contains the most polished implementations."
      }
    },
    {
      "@type": "Question",
      "name": "Does Claude Code statusline work on Windows?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Most statuslines are built for macOS/Linux. For Windows support, see lc1995/ClaudeCodeStatusLineWindows or use WSL with any Linux-compatible statusline."
      }
    },
    {
      "@type": "Question",
      "name": "How do I monitor multiple Claude Code sessions?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "For multi-session monitoring, check out hoangsonww/Claude-Code-Agent-Monitor (web dashboard) or thoo/claude-code-zellij-status (Zellij panes)."
      }
    }
  ]
}
</script>
