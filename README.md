# Shashwat Jain

Currently AI Engineer @ [AiRA](https://airaai.in), where I own the AI infrastructure.

## Agents

### Voice
- Built on OpenAI Realtime, Grok Voice, Cartesia and ElevenLabs
- Both speech-to-speech and separate listen, think and speak steps, depending on how much control a product needs
- Replies in under a second, and the agent stops cleanly when someone cuts in
- Sending audio as raw binary instead of text, which made streams about 5x smaller

### Browser
- An agent that drives a real cloud browser on its own, step by step
- Asks a human before doing anything risky
- Passwords and secrets stay in a vault, never in what the model sees

## Under the hood
- My own agent harness, built directly on provider SDKs. I'd rather give the model good tools than script around it.
- One codebase across OpenAI, Anthropic, Gemini, Groq and Cerebras
- Memory that remembers users across conversations: short, mid and long term
- Prompts structured so providers can reuse them: 98–99% cache hits, which cuts cost and response time
- Every prompt change gets tested before it goes live: a bigger model grades the answers, people review them, and regression tests catch anything that broke
- Tracing and cost per call, so failures and spend are visible

## More about me
- My [journal](https://shashwatjain.tech/) is run by my own agents. They know what I'm working on, keep it updated and redesign it, and it tracks my token usage across all of them.
- **Stack:** Python, TypeScript, FastAPI, WebSockets, Redis, MongoDB, Qdrant, Docker

## Contact
Want the details? Email me at [shashwatjain2k3@gmail.com](mailto:shashwatjain2k3@gmail.com) and we'll set up a call.

[X](https://x.com/itsshashwatj) · [LinkedIn](https://www.linkedin.com/in/itsshashwatjain/)
