# See some of my projects below. They were all built out of needs I experienced myself, and hopefully they may be of use to you as well.

## Products

- **[catalens-one](https://github.com/haniabdemai/catalens-one)**: Catalens One for agentic ecommerce. See your store the way AI shopping agents do. Paste any store URL and get a scored, product-by-product agent-readiness audit: what an agent can identify, verify and recommend; what it silently skips; and exactly what to fix, ranked worst-first. Works on any platform with zero merchant integration, exports as PDF, Markdown and JSON. Live at [catalens.one](https://catalens.one).
- **[whatsapp-voice](https://github.com/haniabdemai/whatsapp-voice)**: a personal AI that drafts WhatsApp replies in your voice. It builds a training set from your own chat history with a privacy-first pipeline (read-only snapshot, HMAC pseudonymisation, aggregate-only auditing), LoRA fine-tunes a local model on Apple Silicon, and serves a local drafting desk. Fifteen years of conversations never leave the machine.
- **[instagram-inspiration-library](https://github.com/haniabdemai/instagram-inspiration-library)**: turns your Instagram saved posts from a write-only archive into a searchable, tagged local library. Official data export in; scheduled human-paced downloads; local speech-vs-music classification so you only pay to transcribe actual speech; everything lands in one SQLite file with full-text search.
- **[event-recommender](https://github.com/haniabdemai/event-recommender)**: a weekly pipeline that discovers local events from newsletters, Meetup, Luma and venue sites, scores them against your personal taste profile (deterministic vetoes and weighted signals, then an LLM sense-check), computes travel times, and surfaces the picks worth leaving the house for on a Notion board. Ships with a guided taste-profile setup so it recommends for you, not for its author.

## Methods

- **[product-management-skills](https://github.com/haniabdemai/product-management-skills)**: a product-management operating system for AI assistants: PRDs, feature discovery, user stories, prioritisation, roadmaps and personas as composable skills that work together, chained by an orchestrator with shared context files and a decision log. One system an AI can drive end to end, rather than six disconnected templates.
- **[formal-appeals](https://github.com/haniabdemai/formal-appeals)**: a complete working method for appeals, reconsiderations and formal complaints to institutions: evidence verification before drafting, conclusion-first structure, a rejected-vs-shipped wording table, tone rules, print-ready document packs and adversarial review. Every rule was earned through a rejected draft.

## Utilities

- **[local-transcription](https://github.com/haniabdemai/local-transcription)**: transcription plus speaker diarization, fully local on Apple Silicon: mlx-whisper on the GPU at 18-28x real time, pyannote speaker turns aligned to the transcript so you know who said what. Free, private, proven on a 22-hour real-world corpus. Built on mlx-whisper and pyannote.audio.
- **[mac-panic-watch](https://github.com/haniabdemai/mac-panic-watch)**: your Mac kernel-panicked overnight and you would never know. A 40-line launchd watcher that pushes new kernel panic reports to your phone via ntfy, so intermittent hardware and kernel bugs stop hiding.

## Claude Code tooling

- **[claude-toolkit](https://github.com/haniabdemai/claude-toolkit)**: three working systems that make AI coding assistants safer and more disciplined, each born from a real failure. parallel-sessions is an orchestration protocol plus git guards so multiple Claude Code sessions can work one repo without destroying each other's work. claude-project-tracker is a set of hooks that make "done" mean verified against acceptance criteria, built for Notion and driven by your own coding agent, no Notion AI needed. safety-guards adds an API cost gate, a Keychain-enumeration block and a config-file lock.
- **[gmail-writer-mcp](https://github.com/haniabdemai/gmail-writer-mcp)**: a local MCP server that gives Claude working Gmail write operations, built after diagnosing why the hosted Gmail MCP's write tools can never work: its tool cap forces read-only OAuth scopes. The README carries the post-mortem; the server carries the fix.

## Collections

- **[everyday-ai-tools](https://github.com/haniabdemai/everyday-ai-tools)**: the small tools for the unglamorous parts of life and work: appeals letters, a meeting-heavy inbox, hours of unwatched video, a Mac that panics at 3am. Gathered in one place with a side-by-side comparison of what each does and why it beats the obvious alternatives.

More about the work at [haniabdemai.com](https://haniabdemai.com).
