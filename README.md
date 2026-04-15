# 🇮🇳 AI Indian Market Intelligence Bot

An automated daily market briefing bot that fetches 
real-time NSE news, analyzes it with Gemini AI, and 
delivers clean insights to Telegram every morning at 9am.

## 🔧 Built With
- n8n (workflow automation)
- Google Gemini AI (market analysis)
- Economic Times RSS Feed (real-time news)
- Telegram Bot API (delivery)

## 🔄 Workflow
Schedule Trigger → HTTP Request → Gemini AI → Telegram

## ⚙️ Setup
1. Import workflow.json into n8n
2. Add your Gemini API key
3. Add your Telegram bot token and Chat ID
4. Activate workflow
