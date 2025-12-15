# TrendScout AI 🚀

**An intelligent market research agent powered by n8n and LLMs.**

TrendScout helps automate the discovery of product trends. Instead of manually searching, you can chat with this agent. It intelligently distinguishes between casual conversation and specific market research requests, routing them to the appropriate tools.

## 🚧 Current Status: Phase 1 (Intent Detection)

I am currently building the "Brain" of the agent.
- **Goal:** Accurately classify user messages.
- **Tech:** n8n, Docker, JSON Parsing.

### Features
- **Smart Routing:** Uses an LLM to analyze user input.
- **Strict JSON Output:** Ensures the AI replies in a machine-readable format for n8n to process.
- **Fallback Logic:** Robust error handling if the AI response is malformed.

## 🎥 Demo
*(Insert your GIF/Clip here later)*

## 🛠️ Setup
This project runs on **Docker**.

1. Clone the repo.
2. Run `docker-compose up -d`.
3. Access n8n at `localhost:5678`.

---
*Created by Geovponce*
