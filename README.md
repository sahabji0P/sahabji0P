# Shashwat Jain

AI engineer at [AiRA](https://github.com/AiraAi). I build agents that talk on calls and agents that use the browser.

### Voice agents

- Speech-to-speech on OpenAI Realtime, Gemini Live and Grok Voice
- Cascaded pipelines when I need control over each step
- Interruptions, backchannels ("mm-hmm"), tool calls while the user is still talking
- Long calls: dropped sockets, session limits, picking up where the call left off

### Browser agents

- Agents that get real work done on real websites: logins, forms, multi-step flows
- Playwright and CDP, reading pages through the accessibility tree and screenshots
- Pages that change under the agent, and recovering when a step fails

### Harness

- The layer around the model: tools, context, memory, retries, when to stop
- One interface over Anthropic, OpenAI, Gemini and DeepSeek
- Prompts structured around each provider's caching, for cost and first-token latency
- All on raw SDKs. I'd rather give the model good tools than script around it.

Before AiRA I was a backend developer.

**Stack:** Python, asyncio, FastAPI, WebSockets, TypeScript, Docker
**Daily tools:** Claude Code, Codex CLI, OpenCode

[Journal](https://shashwatjain.tech/) · [X](https://x.com/itsshashwatj) · [LinkedIn](https://www.linkedin.com/in/itsshashwatjain/)
