# Signal AI

**The Autonomous Market Intelligence Suite for E-Commerce.**

TrendScout is a multi-agent system designed to automate the work of market analysts, strategists, and content creators. It unifies trend discovery, competitor monitoring, and content generation into a single pipeline.

## Architecture
The system is composed of three specialized AI agents feeding into a central dashboard:

1.  **Trend Discovery Agent:** Scans RSS & Google Search for emerging signals.
2.  **Competitor Monitor:** Tracks pricing, listings, and reviews.
3.  **Content & Insights:** Generates marketing copy based on real-time data.

---

## Roadmap & Progress

### Phase 1: Core Foundation & Intent
- [x] **Smart Routing:** LLM-based intent detection (Chat vs. Research).
- [x] **Visuals:** Moodboard Generator integration (Gemini Vision).

### Phase 2: Trend Discovery Agent (Current Focus)
- [x] **Signal Capture:** Aggregating data from design blogs via RSS feeds.
- [x] **Data Filtering:** JavaScript logic to isolate recent (Last 7 Days) trends.
- [ ] **Web Intelligence:** Surfacing fresh trends via Google Search integration.
- [ ] **Data Extraction:** Web scraping product-level insights.
- [ ] **Synthesis:** Merging all streams into a unified Trend Discovery Agent.

### Phase 3: Competitor Monitoring Agent
- [ ] **Strategy:** Defining competitive intelligence parameters.
- [ ] **Scraping:** Extracting competitor listings, pricing, and reviews.
- [ ] **Analysis:** Benchmarking and whitespace identification.

### Phase 4: Content & Insights Agent
- [ ] **Creative Logic:** Teaching the agent brand voice and creative thinking.
- [ ] **Generation:** Producing blogs, captions, and campaign ideas based on data.

### Phase 5: Market Intelligence Dashboard
- [ ] **Pipeline Merge:** Unifying Trend, Competitor, and Insight streams.
- [ ] **Visualization:** Google Sheets/Slides dashboard for actionable business intel.

---

## Demos (Completed Modules)

| Module | Function | Watch |
| :--- | :--- | :--- |
| **Market Trend Agent** | Detects user intent (Chat vs. Research) and routes accordingly. | [![Watch](https://img.shields.io/badge/▶-Watch_Demo-red?style=for-the-badge&logo=youtube)](https://www.youtube.com/watch?v=bhZeDg5qZcg) |
| **Moodboard Agent** | Generates visual prompts and creates moodboards using Gemini. | [![Watch](https://img.shields.io/badge/▶-Watch_Demo-red?style=for-the-badge&logo=youtube)](https://www.youtube.com/watch?v=tossaxBcPFM) |

---

## Setup
This project runs on **Docker**.

1. Clone the repo.
2. Run `docker-compose up -d`.
3. Access n8n at `localhost:5678`.

---
*Created by GodfreyPonce*
