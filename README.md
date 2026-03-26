# crypto-n8n-agent
An AI agent that fetches real-time data on the top 3 cryptocurrencies from the CoinGecko API via n8n and delivers a daily summary to your Gmail at a scheduled time — eliminating the need for manual tracking.

---

## 🔴 Problem Statement
Checking crypto prices to keep a track of the trends daily across platforms is tedious. This agent 
automates the entire process — fetching, summarizing, and delivering 
insights directly to your inbox.

---

## 🛠 Tech Stack
| Tool           | Purpose |
|----------------|---------|
| n8n            | Workflow automation & scheduling |
| CoinGecko API  | Real-time crypto market data |
| Google Gemini  | LLM Model Used To Summarize |
| Gmail (OAuth2) | Daily email delivery |

---

## ⚙️ Setup
1. Import `crypto-summary-workflow.json` into n8n
2. Add your Gmail OAuth2 and Gemini API credentials in n8n
3. Set your preferred trigger time
4. Activate the workflow ✅

---

## ⚠️ Limitations
- API Rate Limit 
- Requires n8n to be running at trigger time

---

## 🚀 Future Work
- Letting users choose which coins to track and letting the LLM Model choose which API Key to fetch.
- Add price drop/spike alerts
- Support Telegram or WhatsApp delivery
