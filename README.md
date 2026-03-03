# LLM Price Calculator

Compare monthly costs for 30+ AI models across 7 providers.

**[Try it →](https://yurukusa.github.io/llm-price/)**

## What it does

Input your monthly token usage → see costs for every model, sorted cheapest first.

Presets for common workloads: Chat Bot, RAG Pipeline, Coding Agent, Summarizer, Small App, Enterprise.

## Models included

| Provider | Models |
|----------|--------|
| Anthropic | Claude Opus 4.6, Sonnet 4.6, Haiku 4.5/3.5/3 |
| OpenAI | GPT-5.2, 5.1, 5 Mini/Nano, o3, o4-mini, GPT-4.1/4o |
| Google | Gemini 2.5 Pro/Flash/Flash-Lite, 2.0 Flash |
| DeepSeek | V3.2, V3.1 |
| Mistral | Large 3, Medium 3, Nemo |
| xAI | Grok 4, Grok 4.1 Fast |
| Meta | Llama 4 Maverick, Llama 4 Scout (via Groq) |

## Key findings (March 2026)

- **500x price spread** between cheapest (Mistral Nemo $0.02/$0.02) and most expensive (Claude Opus 4.6 $5/$25)
- **DeepSeek V3.2** at $0.25/$0.40 is the value king for most workloads
- **Budget models are getting scary good** — GPT-5 Nano, Gemini Flash Lite, and Mistral Nemo are essentially free at scale
- **Context window ≠ price tier** — Llama 4 Scout offers 10M context at $0.11/$0.34

## Technical

Single HTML file. Zero dependencies. Runs entirely in your browser. No data sent anywhere.

Prices sourced from official pricing pages as of March 2026.
