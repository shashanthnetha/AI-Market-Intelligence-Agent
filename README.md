# AI-Market-Intelligence-Agent
"An automated n8n agent that tracks stock portfolios, researches news with Gemini AI, and logs data to Google Sheets."

This is a production-ready automation built with **n8n** that monitors stock market volatility and uses **Google Gemini AI** to provide context on price movements.

## 🚀 Features
- **Multi-Stock Tracking**: Loops through a custom portfolio using JavaScript.
- **Smart News Scraper**: Pulls relevant Google News headlines only when volatility is detected.
- **AI Sentiment Analysis**: Uses Gemini 1.5 Flash to generate structured JSON reports.
- **Dual-Destination Logging**: Sends detailed reports to Gmail and short snippets to Google Sheets.

## 🛠️ Setup
1. Download the `My workflow.json` file from this repo.
2. Import it into your **n8n** instance.
3. Configure your credentials for **Google Gemini**, **Gmail**, and **Google Sheets**.
4. Set your tickers in the **Code Node** and you're good to go!
