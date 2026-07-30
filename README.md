# Awesome-AI-Voice-Agent-Platform

## Similar Projects to AI Voice Agent Platforms

**AI Voice Agent** platforms enable real-time conversational voice AI — combining speech-to-text (STT), large language models (LLMs), text-to-speech (TTS), telephony/WebRTC, tool calling, and orchestration for phone agents, inbound/outbound calling, and voice assistants. Leading commercial tools include Vapi, Retell AI, Bland AI, PlayAI, Synthflow, Air AI, Voiceflow, Hume AI, PolyAI, and Deepgram Voice Agent offerings.

Below is a **curated list** of notable platforms and their open-source equivalents. Fully managed, production-ready voice agent platforms with visual builders are less common in pure open source, so the emphasis is on **self-hostable frameworks and platforms** that give full control over the stack (STT → LLM → TTS + telephony).

## 🏢 SaaS / Hosted Platforms

- **[Vapi](https://vapi.ai/)** — Developer-focused voice AI platform with strong APIs, visual workflow tools, telephony, and support for multiple STT/LLM/TTS providers. Popular for building production phone agents.
- **[Retell AI](https://www.retellai.com/)** — Managed voice agent platform emphasizing low latency, natural conversations, and ease of deployment for inbound/outbound calling.
- **[Bland AI](https://www.bland.ai/)** — Voice AI platform focused on high-volume outbound and phone automation with strong enterprise options.
- **[PlayAI](https://play.ai/)** — Conversational AI platform with voice agent capabilities.
- **[Synthflow](https://synthflow.ai/)** — No-code / low-code voice AI automation platform for building and deploying agents.
- **[Air AI](https://air.ai/)** — AI voice agent platform aimed at sales and customer engagement use cases.
- **[Voiceflow](https://www.voiceflow.com/)** — Conversational AI design platform (broader than pure voice) used for designing and deploying voice and chat agents.
- **[Hume AI](https://www.hume.ai/)** — Emotion-aware voice AI platform with expressive TTS and conversational models.
- **[PolyAI](https://poly.ai/)** — Enterprise conversational AI platform specialized in voice customer service agents.
- **[Deepgram](https://deepgram.com/)** — Speech AI platform (STT/TTS) with Voice Agent capabilities and real-time APIs frequently used as a building block or managed option.

## 🔓 Open-Source Software

### Full Platforms / Closest Vapi & Retell Alternatives
- **[Dograh](https://github.com/dograh-hq/dograh)** — Leading open-source, self-hostable voice AI platform and direct alternative to Vapi/Retell. Features a visual workflow builder, telephony support (Twilio, Vonage, etc.), BYOK for STT/LLM/TTS (or speech-to-speech), MCP support, post-call analytics, and full self-hosting (BSD license). Strong production-oriented feature set.

### Real-Time Voice Agent Frameworks
- **[Pipecat](https://github.com/pipecat-ai/pipecat)** — Open-source Python framework (from Daily) for building real-time voice and multimodal conversational agents. Highly modular pipelines for VAD, STT, LLM, TTS, transports, and multi-agent coordination. Excellent for engineers who want full control.
- **[LiveKit Agents](https://github.com/livekit/agents)** — Open-source framework (Apache 2.0) built on LiveKit’s real-time WebRTC infrastructure. Lets you add Python/Node.js agents as participants in rooms with streaming STT/LLM/TTS pipelines, tool calling, and telephony/SIP support. Very popular for production real-time agents.
- **[Vocode](https://github.com/vocodedev/vocode-core)** — Open-source library/framework for building voice agents with pluggable STT, LLM, and TTS components (frequently cited alongside Pipecat and LiveKit).
- **[TEN Framework / TEN-Agent](https://github.com/TEN-framework/TEN-Agent)** — Open-source framework for real-time multimodal conversational AI agents, including voice.

### Supporting Open-Source Building Blocks
- **Hugging Face speech-to-speech** and related cascaded pipelines — Modular open-source speech-to-speech stacks using Whisper/Parakeet (STT), open LLMs, and open TTS models.
- Local/open STT: faster-whisper, NVIDIA Parakeet, Silero VAD, etc.
- Local/open TTS: Kokoro, XTTS, Coqui, Fish Speech, Qwen-TTS, and others.
- Real-time media: LiveKit (self-hosted), WebRTC stacks.
- Many teams assemble a full open stack: **Dograh or Pipecat/LiveKit Agents** (orchestration) + preferred STT/LLM/TTS + telephony provider.

### Typical Open-Source Voice Agent Stack
A common production-oriented open-source approach:
1. **Orchestration** — Dograh (visual) or Pipecat / LiveKit Agents (code-first)
2. **STT** — Deepgram, Whisper, Parakeet, or self-hosted alternatives
3. **LLM** — Any OpenAI-compatible endpoint (cloud or self-hosted)
4. **TTS** — ElevenLabs, Cartesia, Kokoro, or other open models
5. **Transport** — Twilio/Vonage/SIP or LiveKit WebRTC

This gives full data ownership and eliminates per-minute platform markups while retaining flexibility.

---

**How to contribute**  
Fork this repository, add a new project (with link + short description + category), and open a pull request.  
Prefer actively maintained open-source projects that support real-time voice pipelines, telephony, or visual/code-based agent building.

**License**  
This list is public domain / CC0. Feel free to copy into your own awesome list or README.

Star the projects you find useful — open-source voice agent tooling is advancing rapidly! 🎙️
