# Helix AI

![Helix AI Logo](image0.jpg)

> *Your personal AI assistant — local & cloud, voice & text. No account needed.*

---

## ✨ What is Helix?

**Helix AI** is a fully self-contained, single-file AI assistant that runs entirely in your browser. It combines the power of cloud AI models (via Pollinations.ai — **free, no API key required**) with on-device AI using WebGPU, giving you the best of both worlds: speed, privacy, and intelligence.

---

## 🚀 Features

| Feature | Description |
|---|---|
| 🧠 **4 AI Personas** | Azur (fast), Pyre (reasoning), Quar (balanced), Jade (creative/code) |
| ☁️ **Free Cloud AI** | GPT-4.1, GPT-4o, DeepSeek-R1, Qwen-Coder via Pollinations — no key needed |
| 🖥️ **On-Device AI** | Fully private, offline inference via WebLLM + WebGPU |
| 🔑 **Custom API Keys** | Bring your own key: OpenAI, Anthropic, Groq, Gemini, OpenRouter, Mistral |
| 🎙️ **Voice Mode** | Full voice conversation with animated orb UI |
| 🔊 **Kokoro TTS Studio** | High-quality offline text-to-speech with 20+ voices |
| 📎 **File Attachments** | Images, PDFs, code files — attach and analyze |
| ⚡ **Projects** | Auto-generates HTML apps, code, diagrams, Markdown docs |
| 🔍 **Web Search** | Integrated DuckDuckGo search for real-time answers |
| 🌓 **Themes** | Per-model color themes + light/dark/system mode |
| 🌍 **9 Languages** | Italian, English, Spanish, French, German, Portuguese, Chinese, Japanese, Korean |
| 🔒 **Incognito Mode** | No history, no storage — private by design |
| 📱 **PWA Ready** | Install to home screen, works offline |

---

## 🔑 Custom API Keys

Helix supports using your own API key for any major AI provider:

- **OpenAI** — GPT-4.1, GPT-4o, o4-mini, o3
- **Anthropic** — Claude Opus 4.6, Sonnet 4.6, Haiku 4.5
- **Groq** — Llama 3.3 70B, DeepSeek R1, Gemma 2
- **Google Gemini** — 2.0 Flash, 2.5 Pro, 2.5 Flash
- **OpenRouter** — Access to 100+ models
- **Mistral** — Large, Small, Codestral

When a custom key is active, the **Model Sheet automatically shows your provider's models** — tap the model pill at the top to switch models from your provider.

> 🔒 **Security**: Your API key is stored **only in your browser's localStorage** and is never sent to any Helix server. It goes directly from your device to the AI provider.

---

## 📲 Installation (PWA)

1. Open Helix in Chrome / Safari / Edge
2. Tap **Share → Add to Home Screen** (iOS) or the install icon in the address bar (desktop/Android)
3. Done! Helix runs as a standalone app

For self-hosting, place `helix_v8.html`, `manifest.json`, and `image0.jpg` in the same folder.

---

## 🛠️ How It Works

```
index.html        ← entire app in one file
manifest.json        ← PWA manifest (link from HTML or use inline blob)
image0.jpg           ← app icon / logo
```

Helix is a **zero-dependency, zero-build** project. No npm, no bundler, no backend. Just open the HTML file.

---

## 🎨 Architecture

```
┌─────────────────────────────────────────────┐
│                  Helix AI                    │
│                                             │
│  ┌──────────┐  ┌──────────┐  ┌───────────┐ │
│  │  Cloud   │  │  Local   │  │  Custom   │ │
│  │Pollinations│ │ WebLLM  │  │  API Key  │ │
│  │ (free)   │  │(WebGPU)  │  │(your key) │ │
│  └──────────┘  └──────────┘  └───────────┘ │
│                                             │
│  ┌──────────────────────────────────────┐  │
│  │     Helix Personas (System Prompts)  │  │
│  │  Azur · Pyre · Quar · Jade          │  │
│  └──────────────────────────────────────┘  │
│                                             │
│  Voice · Artifacts · Search · Memory · TTS  │
└─────────────────────────────────────────────┘
```

---

## 🤝 Support

If Helix has been useful to you, consider showing some love:

- ⭐ **[Star the project on GitHub](https://github.com/HelixAI-4-0/helixai-4-0.github.io)** — it really helps!
- 👤 **[Follow the developer @Marco3113](https://github.com/Marco3113)** — more projects incoming

---

## 📄 License

Open source. Built with ❤️ by [Marco3113](https://github.com/Marco3113).

All AI models are provided by their respective providers (Pollinations, OpenAI, Anthropic, Google, Groq, Meta, Mistral, DeepSeek). Helix itself does not collect any user data.

---

*Helix AI · Single file · No tracking · Privacy first*
