# Hi, I'm Nico

📍 Vancouver, BC
🔧 Open source agentic harness tooling
⚡ Senior Agent Engineer @ [Pika Labs](https://pika.art/)

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Shopify](https://img.shields.io/badge/-Shopify-7AB55C?style=flat-square&logo=shopify&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Pi](https://img.shields.io/badge/-Pi_Agent-8B5CF6?style=flat-square&logo=pi-hole&logoColor=white)
![CLI](https://img.shields.io/badge/-CLI-000000?style=flat-square&logo=gnu-bash&logoColor=white)
![macOS](https://img.shields.io/badge/-macOS-000000?style=flat-square&logo=apple&logoColor=white)
![Web](https://img.shields.io/badge/-Web-4285F4?style=flat-square&logo=google-chrome&logoColor=white)
&nbsp;&nbsp;[![Sponsored by Anoma.ly / OpenCode](https://img.shields.io/badge/Sponsored%20by-Anoma.ly%20%2F%20OpenCode-8B5CF6?style=flat-square)](https://github.com/sponsors/nicobailon)

I build tools for AI coding agents. My recent focus has been around building tooling for [pi coding agent](https://github.com/badlogic/pi-mono/) and contributing to core along the way.

When I started contributing, pi was a pretty opinionated tool with a fixed set of capabilities. I kept submitting PRs with increasingly wild ideas, and Mario kept entertaining them. When I'd hit a core limitation I'd prototype the change first, then work backward to figure out what extension points were needed and open an issue to discuss. Eventually he designed a proper extensions API with input from the whole community, and that opened everything up.

I like experimenting with cutting-edge agentic workflows and techniques, and I approach it all with a critical and practical lens. Background in Next.js and Shopify Plus (10+ years, DTC brands like SAXX, Livestock, Size Official, Saje Natural Wellness).

## [Pi](https://pi.dev/) Extensions &nbsp; [![packages](https://img.shields.io/badge/pi.dev-packages-8B5CF6?style=flat-square)](https://pi.dev/packages)

- 🐚 **[pi-interactive-shell](https://github.com/nicobailon/pi-interactive-shell)** - Run interactive CLIs in an observable overlay with full PTY emulation. User can take over anytime. `⭐ 474`
- 🧬 **[pi-subagents](https://github.com/nicobailon/pi-subagents)** - Delegate to child agents with chains, parallel execution, and async dispatch. `⭐ 1194`
- 💬 **[pi-messenger](https://github.com/nicobailon/pi-messenger)** - Multi-agent coordination through the filesystem. Agents join, claim tasks, reserve files, send messages. `⭐ 539`
- 📨 **[pi-intercom](https://github.com/nicobailon/pi-intercom)** - Direct 1:1 messaging between pi sessions on the same machine. Send context, findings, or requests between sessions. `⭐ 108`
- 📋 **[pi-interview-tool](https://github.com/nicobailon/pi-interview-tool)** - Web forms for gathering structured input instead of back-and-forth chat. `⭐ 263`
- 🔌 **[pi-mcp-adapter](https://github.com/nicobailon/pi-mcp-adapter)** - Single proxy tool that discovers MCP servers on demand instead of loading all tool definitions upfront. `⭐ 577`
- 🌐 **[pi-web-access](https://github.com/nicobailon/pi-web-access)** - Web search and content extraction. Works with Chrome cookies, Perplexity, or Gemini API. `⭐ 428`
- 🪃 **[pi-boomerang](https://github.com/nicobailon/pi-boomerang)** - Token-efficient task execution with automatic context collapse. Work gets done, tokens get saved. `⭐ 217`
- 🤖 **[pi-discord](https://github.com/nicobailon/pi-discord)** - Discord bot for Pi. Persistent sessions per channel, slash commands, full tool access. `⭐ 33`
- 💭 **[pi-side-chat](https://github.com/nicobailon/pi-side-chat)** - Fork conversations into side chats while the main agent keeps working. `⭐ 42`
- 🗜️ **[pi-custom-compaction](https://github.com/nicobailon/pi-custom-compaction)** - Swap the model and template Pi uses for compaction. Token-based triggers, profile support. `⭐ 31`
- ⏪ **[pi-rewind-hook](https://github.com/nicobailon/pi-rewind-hook)** - Git-backed checkpoints for AI coding sessions. Browse and restore file states. `⭐ 115`
- 🎯 **[pi-annotate](https://github.com/nicobailon/pi-annotate)** - Visual annotation mode for Chrome. Click elements, add comments, get CSS selectors and box model info. `⭐ 226`
- 🧲 **[pi-prompt-template-model](https://github.com/nicobailon/pi-prompt-template-model)** - Prompt templates with model, skill, and thinking frontmatter. Auto-switch, inject skills, and restore when done. `⭐ 234`
- 🎨 **[pi-skill-palette](https://github.com/nicobailon/pi-skill-palette)** - Command palette for selecting which skill to inject with your next message. `⭐ 73`
- 🔁 **[pi-review-loop](https://github.com/nicobailon/pi-review-loop)** - Automated code review loop that re-prompts until no issues found or max iterations hit. `⭐ 75`
- 📊 **[pi-powerline-footer](https://github.com/nicobailon/pi-powerline-footer)** - Powerline-style status bar with token usage, cost, model, and thinking level. `⭐ 203`
- 🔗 **[pi-foreground-chains](https://github.com/nicobailon/pi-foreground-chains)** - Multi-agent workflow orchestration with file-based handoff between different CLI agents. `⭐ 34`
- 🗺️ **[pi-coordination](https://github.com/nicobailon/pi-coordination)** - Parallel task execution with a dependency graph, worker agents, and review cycles. `⭐ 41`
- 🔀 **[pi-model-switch](https://github.com/nicobailon/pi-model-switch)** - Lets the agent switch its own model mid-session. `⭐ 82`
- 🎴 **[pi-design-deck](https://github.com/nicobailon/pi-design-deck)** - Multi-slide visual decision decks in the browser. Compare code, diagrams, and UI mockups side by side. `⭐ 255`

## Standalone Tools

- 🏄 **[surf-cli](https://github.com/nicobailon/surf-cli)** - CLI for controlling Chrome from any agent. Screenshots, navigation, element interaction. `⭐ 469`
- 🎙️ **[agent-interview-cli](https://github.com/nicobailon/agent-interview-cli)** - Web forms you can pipe. Opens a browser form, collects responses, outputs JSON to stdout. Zero deps. `⭐ 26`
- 📊 **[visual-explainer](https://github.com/nicobailon/visual-explainer)** - Agent skill that generates rich HTML pages for visual diff reviews, architecture overviews, and data tables. `⭐ 7850`

## Activity

![GitHub Contribution Graph](https://ghchart.rshah.org/nicobailon)

## Sponsors

<table>
  <tr>
    <td align="center" width="200">
      <a href="https://pi.dev/">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="pi-logo-light.svg">
          <source media="(prefers-color-scheme: light)" srcset="pi-logo-dark.svg">
          <img src="pi-logo-dark.svg" alt="Pi" height="36">
        </picture>
        <br><br>
        <strong><a href="https://x.com/badlogicgames">Mario Zechner</a></strong>
      </a>
    </td>
    <td align="center" width="200">
      <a href="https://opencode.ai/">
        <img src="opencode-logo.svg" alt="Anoma.ly / OpenCode" height="36">
        <br><br>
        <strong>Anoma.ly / OpenCode</strong>
      </a>
    </td>
  </tr>
</table>

Also thanks to [pi0](https://x.com/_pi0_) and [maxsumrall](https://x.com/maxsumrall) for their support.

## Connect

[![Email](https://img.shields.io/badge/-nico604@pm.me-8B89CC?style=flat-square&logo=protonmail&logoColor=white)](mailto:nico604@pm.me)
[![Twitter](https://img.shields.io/badge/-@nicopreme-1DA1F2?style=flat-square&logo=twitter&logoColor=white)](https://twitter.com/nicopreme)
[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/nicobailon)
