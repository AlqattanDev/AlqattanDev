# Ali AlQattan

**Software Engineer — Platform, Cloud Automation & AI Tooling**
Manama, Bahrain · building as **exidex**

I work on production cloud systems and on tools for AI coding agents. I build by directing AI coding agents, including Claude Code and Codex, and I own the requirements, design decisions, integration, verification and operation of what ships.

I am looking first for remote AI/agent-tooling and developer-tool roles, and for senior platform/cloud roles in the Gulf.

[Portfolio](https://exidex.dev) · [How I work](https://exidex.dev/about) · [Technical breakdowns](https://exidex.dev/breakdowns) · [CV](https://exidex.dev/resume) · [Contact](https://exidex.dev/contact) · [LinkedIn](https://www.linkedin.com/in/alqattanali)

## Engineering work

- **[Vox](https://github.com/AlqattanDev/vox-mcp)** — a local voice runtime and MCP server for coding agents on macOS: one persistent daemon, a shared operation queue so several agents can use the speaker without talking over each other, cancellation that clears queued work, and reconnectable clients. Speech recognition and synthesis (whisper.cpp, Kokoro) run on the Mac. Open source (MIT) with a one-command `install.sh`; [the latency breakdown](https://exidex.dev/breakdowns/vox-latency) covers the engineering.
- **[Messages API bridge](https://github.com/AlqattanDev/kiro-claude-bridge)** — an inspectable TypeScript proxy translating requests and streaming events between two API protocols. Zero runtime dependencies; requires the user’s own backend account and a local Node runtime.
- **[bro](https://github.com/AlqattanDev/bro)** — a macOS menu-bar companion with a durable request queue, voice, a floating answer panel and explicit screen-capture controls. Requires local installation and a configured agent backend.
- **[room](https://exidex.dev/breakdowns/room-untrusted)** *(retired)* — tmux tooling that made each agent’s state visible in pane labels, window names and the status bar. The write-up covers handling untrusted agent output before tmux interprets it.
- **[The Grove](https://exidex.dev/p/the-grove)** — a persistent multiplayer browser town, one of the self-hosted games on the portfolio.

## Production experience

At Bank ABC (ila Bank), I run cloud operations for a licensed digital bank in Bahrain and Jordan: Jenkins production deploys, Python and Systems Manager automation, Terraform modules, the legacy core-banking estate, the monitoring that emails the service desk, and a guarded toolkit that lets AI coding agents work on production infrastructure under audit. Employer systems and code remain private; [The Guardrails Are the Product](https://exidex.dev/breakdowns/guardrails-product) explains the approach with synthetic examples.

Earlier work includes Flutter and web products, a newsroom distribution pipeline, and an employee-management platform used by institutes in Bahrain.

**Python · TypeScript · AWS · Terraform · CI/CD · MCP · Flutter · React**

Everything else, including the playable games, is on [the portfolio](https://exidex.dev/projects).
