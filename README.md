## Hi, I'm Shushan 👋

I build production AI applications. Currently focused on RAG, agent workflows, and AI-native developer tools.

### What I'm working on

🚧 **[Postmark](#)** — *a memory layer for product experimentation, currently in active development*
A meta-tool that sits above experimentation platforms like Statsig and Eppo (both recently acquired — Statsig by OpenAI for $1.1B, Eppo by Datadog), providing:
- **Semantic search** across past experiments — *"have we tested anything around onboarding before?"* returns ranked past experiments with AI summaries
- **Pre-flight check** — paste a hypothesis, get risks, similar past tests, and sample-size critique
- **Lessons graph** — auto-detected meta-patterns across all experiments

Built with Next.js 16, TypeScript, SQLite + sqlite-vec, Voyage AI embeddings, and Claude Opus 4.7 / Haiku 4.5. MCP server exposes search and pre-flight to Claude Desktop. ~35% complete. Public repo launches with the working demo.

### Shipped projects

🔍 **[gdpr-qa](https://github.com/ps-cmd777/gdpr-qa)** — RAG over the EU's GDPR regulation. Voyage AI embeddings, Qdrant vector store, asymmetric retrieval. Article-aware chunking validated against ground truth; dimension-aware collection management.

📊 **[claude-analytics-dashboard](https://github.com/ps-cmd777/claude-analytics-dashboard)** — AI-powered CSV analytics dashboard with Claude's tool-use API. Drop a CSV, get streaming charts, narrative insights, and chat-with-your-data. FastAPI + React + Server-Sent Events.

📄 **[claude-data-reporter](https://github.com/ps-cmd777/claude-data-reporter)** — Command-line CSV analysis tool using Claude's tool-use API to generate statistical insights and narrative Markdown reports.

### Stack

**AI:** Claude API · Voyage AI embeddings · MCP · RAG · agent workflows
**Backend:** Python · FastAPI · TypeScript · Next.js · SQLite · Qdrant
**Frontend:** React · Tailwind · streaming UIs

