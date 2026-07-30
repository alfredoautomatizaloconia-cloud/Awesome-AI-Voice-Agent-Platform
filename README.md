# Awesome AI Voice Agent Platform 🎙️

<div align="center">
  <img src="assets/banner.svg" alt="Awesome AI Voice Agent Platform Banner" width="100%" />
  
  <br/>
  
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a><a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</div>

A curated directory of leading commercial SaaS platforms, open-source frameworks, self-hostable tools, and building blocks for creating real-time conversational AI voice agents, automated phone callers, and interactive voice response (IVR) systems.

---

## 📌 Table of Contents
- [🏢 SaaS / Hosted Platforms](#-saas--hosted-platforms)
- [🔓 Open-Source Software](#-open-source-software)
  - [🚀 Full Platforms / Closest Vapi & Retell Alternatives](#-full-platforms--closest-vapi--retell-alternatives)
  - [🛠️ Real-Time Voice Agent Frameworks](#️-real-time-voice-agent-frameworks)
  - [🧱 Supporting Open-Source Building Blocks](#-supporting-open-source-building-blocks)
  - [⚙️ Typical Open-Source Voice Agent Stack](#️-typical-open-source-voice-agent-stack)
- [🤝 How to Contribute](#-how-to-contribute)
- [📄 License](#-license)

---

## 🤖 Similar Projects to AI Voice Agent Platforms

**AI Voice Agent** platforms enable real-time conversational voice AI — combining speech-to-text (STT), large language models (LLMs), text-to-speech (TTS), telephony/WebRTC, tool calling, and orchestration for phone agents, inbound/outbound calling, and voice assistants. Leading commercial tools include Vapi, Retell AI, Bland AI, PlayAI, Synthflow, Air AI, Voiceflow, Hume AI, PolyAI, and Deepgram Voice Agent offerings.

Below is a **curated list** of notable platforms and their open-source equivalents. Fully managed, production-ready voice agent platforms with visual builders are less common in pure open source, so the emphasis is on **self-hostable frameworks and platforms** that give full control over the stack (STT → LLM → TTS + telephony).

## 🏢 SaaS / Hosted Platforms

| Platform | Description | Pricing | Free Tier / Trial Limit | Company Size (Valuation/Revenue) |
| :--- | :--- | :--- | :--- | :--- |
| **[Deepgram](https://deepgram.com/)** | Speech AI platform (STT/TTS) with Voice Agent capabilities and real-time APIs frequently used as a building block. | Pay-as-you-go | $200 one-time free credit (non-expiring) | $1.3B Valuation |
| **[PolyAI](https://poly.ai/)** | Enterprise conversational AI platform specialized in voice customer service agents. | Enterprise-only / custom quotes | No free tier or trial | $750M Valuation |
| **[Vapi](https://vapi.ai/)** | Developer-focused voice AI platform with strong APIs, visual workflow tools, telephony, and support for multiple STT/LLM/TTS providers. | Pay-as-you-go (Base fee $0.05/min, total all-in cost ~$0.18–$0.33/min) | $10 one-time credit (~150–200 min) & 10 free phone numbers | $500M Valuation |
| **[Hume AI](https://www.hume.ai/)** | Emotion-aware voice AI platform with expressive TTS and conversational models. | Pay-as-you-go (paid plans start at $3/month) | 5 EVI minutes/month and 10,000 TTS characters/month (non-commercial) | $219M–$450M Valuation |
| **[Bland AI](https://www.bland.ai/)** | Voice AI platform focused on high-volume outbound and phone automation with strong enterprise options. | Pay-as-you-go ($0.14/min connected AI talk time, $0.05/min transfer time on Start tier) | 2 free credits, 1 phone number, 100 calls/day, and 10 concurrent calls | $200M+ Valuation |
| **[Air AI](https://air.ai/)** | AI voice agent platform aimed at sales and customer engagement use cases. | Enterprise licensing / custom quotes only (high upfront commitments reported) | No free tier or trial | $150M+ Valuation |
| **[Voiceflow](https://www.voiceflow.com/)** | Conversational AI design platform (broader than pure voice) used for designing and deploying voice and chat agents. | Pro plan starts at $60/month | 2 agents and 100 credits/month (evaluation only, ChatGPT only) | $105M Valuation |
| **[Retell AI](https://www.retellai.com/)** | Managed voice agent platform emphasizing low latency, natural conversations, and ease of deployment for inbound/outbound calling. | Pay-as-you-go (Base voice infra $0.07–$0.08/min, all-in cost ~$0.11–$0.31/min) | $10 one-time credit & 20 concurrent calls | $84M Valuation (~$60M ARR) |
| **[PlayAI](https://play.ai/)** | Conversational AI platform with voice agent capabilities. | Subscription-based (Play.ht plans) and pay-as-you-go options | 12,500 characters/month (non-commercial, watermarked) | ~$30M Valuation |
| **[Synthflow](https://synthflow.ai/)** | No-code / low-code voice AI automation platform for building and deploying agents. | Pay-as-you-go (Base voice engine $0.09/min, all-in cost ~$0.11–$0.24/min) | Free trial to build/test with limited test minutes | ~$15M Valuation |

## 🔓 Open-Source Software

### 🚀 Full Platforms / Closest Vapi & Retell Alternatives
- **[Dograh](https://github.com/dograh-hq/dograh)** [![GitHub stars](https://img.shields.io/github/stars/dograh-hq/dograh?style=social&color=white)](https://github.com/dograh-hq/dograh/stargazers) — Leading open-source, self-hostable voice AI platform and direct alternative to Vapi/Retell. Features a visual workflow builder, telephony support (Twilio, Vonage, etc.), BYOK for STT/LLM/TTS (or speech-to-speech), MCP support, post-call analytics, and full self-hosting (BSD license). Strong production-oriented feature set.

### 🛠️ Real-Time Voice Agent Frameworks
- **[Pipecat](https://github.com/pipecat-ai/pipecat)** [![GitHub stars](https://img.shields.io/github/stars/pipecat-ai/pipecat?style=social&color=white)](https://github.com/pipecat-ai/pipecat/stargazers) — Open-source Python framework (from Daily) for building real-time voice and multimodal conversational agents. Highly modular pipelines for VAD, STT, LLM, TTS, transports, and multi-agent coordination. Excellent for engineers who want full control.
- **[LiveKit Agents](https://github.com/livekit/agents)** [![GitHub stars](https://img.shields.io/github/stars/livekit/agents?style=social&color=white)](https://github.com/livekit/agents/stargazers) — Open-source framework (Apache 2.0) built on LiveKit’s real-time WebRTC infrastructure. Lets you add Python/Node.js agents as participants in rooms with streaming STT/LLM/TTS pipelines, tool calling, and telephony/SIP support. Very popular for production real-time agents.
- **[TEN Framework / TEN-Agent](https://github.com/TEN-framework/TEN-Agent)** [![GitHub stars](https://img.shields.io/github/stars/TEN-framework/TEN-Agent?style=social&color=white)](https://github.com/TEN-framework/TEN-Agent/stargazers) — Open-source framework for real-time multimodal conversational AI agents, including voice.
- **[Vocode](https://github.com/vocodedev/vocode-core)** [![GitHub stars](https://img.shields.io/github/stars/vocodedev/vocode-core?style=social&color=white)](https://github.com/vocodedev/vocode-core/stargazers) — Open-source library/framework for building voice agents with pluggable STT, LLM, and TTS components (frequently cited alongside Pipecat and LiveKit).

### 🧱 Supporting Open-Source Building Blocks
- **Hugging Face speech-to-speech** and related cascaded pipelines — Modular open-source speech-to-speech stacks using Whisper/Parakeet (STT), open LLMs, and open TTS models.
- 🎙️ Local/open STT: faster-whisper, NVIDIA Parakeet, Silero VAD, etc.
- 🗣️ Local/open TTS: Kokoro, XTTS, Coqui, Fish Speech, Qwen-TTS, and others.
- ⚡ Real-time media: LiveKit (self-hosted), WebRTC stacks.
- Many teams assemble a full open stack: **Dograh or Pipecat/LiveKit Agents** (orchestration) + preferred STT/LLM/TTS + telephony provider.

### ⚙️ Typical Open-Source Voice Agent Stack
A common production-oriented open-source approach:
1. 🛠️ **Orchestration** — Dograh (visual) or Pipecat / LiveKit Agents (code-first)
2. 📝 **STT** — Deepgram, Whisper, Parakeet, or self-hosted alternatives
3. 🧠 **LLM** — Any OpenAI-compatible endpoint (cloud or self-hosted)
4. 🔊 **TTS** — ElevenLabs, Cartesia, Kokoro, or other open models
5. 📞 **Transport** — Twilio/Vonage/SIP or LiveKit WebRTC

This gives full data ownership and eliminates per-minute platform markups while retaining flexibility.

---

**🤝 How to contribute**  
Fork this repository, add a new project (with link + short description + category), and open a pull request.  
Prefer actively maintained open-source projects that support real-time voice pipelines, telephony, or visual/code-based agent building.

**📄 License**  
This list is public domain / CC0. Feel free to copy into your own awesome list or README.

Star the projects you find useful — open-source voice agent tooling is advancing rapidly! 🎙️

##  Star History
<div align="center">
<a href="https://www.star-history.com/?repos=ishandutta2007%2FAwesome-AI-Voice-Agent-Platform&type=date&legend=bottom-right">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-AI-Voice-Agent-Platform&type=date&theme=dark&legend=bottom-right" />
<source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-AI-Voice-Agent-Platform&type=date&legend=bottom-right" />
<img alt="Star History Chart" src="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-AI-Voice-Agent-Platform&type=date&legend=bottom-right" />
</picture>
</a>
</div>
