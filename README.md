<h1 align="center">ChunHao Chen</h1>
<p align="center">Full-stack Developer · Open Source Contributor</p>

<p align="center">
  <a href="https://blog.chczee.dpdns.org/">Blog</a> ·
  <a href="https://www.threads.com/@chc_web_dev">Threads</a> ·
  <a href="https://x.com/ChunHao_Chen">X</a> ·
  <a href="https://www.linkedin.com/in/chchen-dev">LinkedIn</a>
</p>

---

### 🌍 Open Source Contributions

| Project | Description |
|---------|-------------|
| [openclaw/openclaw](https://github.com/openclaw/openclaw) ![GitHub stars](https://img.shields.io/github/stars/openclaw/openclaw?style=flat&label=⭐) | Support Telegram thread IDs in cron add/edit |
| [vercel-labs/agent-browser](https://github.com/vercel-labs/agent-browser) ![GitHub stars](https://img.shields.io/github/stars/vercel-labs/agent-browser?style=flat&label=⭐) | Network request detail & filtering for request tracking |
| [openabdev/openab](https://github.com/openabdev/openab) ![GitHub stars](https://img.shields.io/github/stars/openabdev/openab?style=flat&label=⭐) | Issue templates, RFC template, GitHub Actions workflow & Discord thread-detection fix |

### 📝 Technical Writing

> Deep-dive articles from contributing to open source — [dev-journal](https://github.com/ChunHao-dev/dev-journal)

**openclaw/openclaw**
- [Understanding ACP in OpenClaw](https://github.com/ChunHao-dev/dev-journal/blob/main/docs/en/openclaw-acp-explained.md) — How Agent Client Protocol connects skills, gateway, and Telegram · [my ACP implementation](https://github.com/ChunHao-dev/kiro-acp-telegram)
- [OpenClaw Multi-Agent Routing Architecture](https://github.com/ChunHao-dev/dev-journal/blob/main/docs/en/openclaw-multi-agent-routing.md) — From Telegram Bot to AI Personas
- [OpenClaw TTS Voice Message Bug Fix](https://github.com/ChunHao-dev/dev-journal/blob/main/docs/en/openclaw-tts-voice-message-bug-fix.md) — Debugging Telegram voice format issues

**openabdev/openab**
- [Helm Upgrade Deleted Our PVC](https://github.com/ChunHao-dev/dev-journal/blob/main/docs/en/openab-helm-pvc-data-loss.md) — A lesson on Kubernetes data persistence

**vercel-labs/agent-browser**
- [agent-browser CDP Connection Bug Fix](https://github.com/ChunHao-dev/dev-journal/blob/main/docs/en/agent-browser-cdp-discarded-tab-hang-fix.md) — Memory Saver frozen tabs causing hangs

### 🛠 Tech Stack

<p>
  <img src="https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/-Next.js-000?logo=next.js&logoColor=white" />
  <img src="https://img.shields.io/badge/-Node.js-339933?logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/-Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/-AWS-232F3E?logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/-Cloudflare-F38020?logo=cloudflare&logoColor=white" />
  <img src="https://img.shields.io/badge/-WebSocket-010101?logo=socketdotio&logoColor=white" />
  <img src="https://img.shields.io/badge/-TCP%2FIP-005571" />
</p>

### 📌 Projects

- **[LingoBitz](https://github.com/ChunHao-dev/LingoBitz-Dictation-Pro)** — Practice language listening with YouTube videos — dictation with 3 difficulty levels, sentence-by-sentence playback, and AI-generated summaries. [🔗 Website](https://www.lingobitz.com)
- **[Whisper AI Pipeline](https://github.com/ChunHao-dev/whisper-ai-pipeline)** — Automated YouTube video processing pipeline — MLX Whisper transcription, AI-powered segmentation, multi-language translation, difficulty analysis, and auto-upload to Cloudflare R2. Orchestrated via AWS SQS with horizontal scaling
- **[Kiro TDD Workflow](https://github.com/ChunHao-dev/Kiro-TDD-workflow)** — npm CLI tool for AI-assisted TDD — four-stage workflow (Design → Test → Implement → Verify), supports React/Vue/Next.js. `npx kiro-tdd-workflow init`
- **[Kiro PTY](https://github.com/ChunHao-dev/Kiro-pty)** — VS Code extension wrapping kiro-cli in a pseudoterminal (node-pty) — image paste, Finder file drag-and-drop, inline `@` fuzzy file picker. TypeScript
- **[Kiro ACP Telegram](https://github.com/ChunHao-dev/kiro-acp-telegram)** — Telegram bot bridge for Kiro CLI via ACP protocol — streaming responses with smart throttling, JSON-RPC 2.0, rate limiting, and message chunking
