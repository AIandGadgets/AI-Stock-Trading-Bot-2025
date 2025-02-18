# AI-Stock-Trading-Bot-2025
Simple AI-powered Trading Bot


## ⚡ Overview
The **Robinhood AI Trading Bot** is a simple Python script
that combines **OpenAI's intelligence** with **Robinhood's trading capabilities**
to help automate and optimize stock trading decisions.
By analyzing **Relative Strength Index (RSI)**, **Volume-Weighted Average Price (VWAP)**,
**Moving Averages**, and **Robinhood analyst ratings**, the bot generates buy, sell,
and hold recommendations — executing trades automatically based on your selected mode.

## 🤔 Why This Bot?
This project is an experiment
to explore how AI can enhance stock trading decisions — potentially outperforming human traders
(or at least me, The Bot Father).

## ⚠️ Important Considerations
- **Start in Demo or Manual Mode** before enabling Auto Mode.
- **Test thoroughly** to fine-tune AI decision-making.
- **Monitor trade logs** to understand AI-driven actions.

## 🛠 Features
✅ **AI-Driven Trading** – Smart, data-backed buy/sell decisions.  
✅ **Portfolio & Watchlist Integration** – Trade directly from your Robinhood stocks.  
✅ **Configurable Strategy** – Set trading parameters to fit your risk profile.  
✅ **Exclusion List** – Prevent trading specific stocks.  
✅ **Logging & Analytics** – Track bot activity and trading history.  
✅ **Workday Scheduling** – Align trading activity with market hours.

## 🚀 Getting Started
1. **Connect Your Accounts**: Add your OpenAI API Key and Robinhood credentials.
2. **Choose a Mode**:
   - **Demo Mode**: Simulates trades without execution.
   - **Manual Mode**: Requires confirmation before executing trades.
   - **Auto Mode**: Executes trades automatically (recommended only after testing).
3. **Monitor and Adjust**: Review trade logs and fine-tune settings for optimal performance.

## 📊 How It Works
1. **Authenticate**: Logs into OpenAI and Robinhood.
2. **Fetch Data**: Retrieves stocks from your **portfolio** and **watchlist**.
3. **Analyze Market Conditions**:
   - **RSI**: Determines overbought/oversold conditions.
   - **VWAP**: Identifies undervalued/overvalued stocks.
   - **Moving Averages**: Evaluates price trends (50-day and 200-day).
   - **Analyst Ratings**: Incorporates Robinhood’s expert opinions.
4. **AI-Driven Decisions**: Uses OpenAI to generate trading recommendations.
5. **Trade Execution**: Buys, sells, or holds stocks based on AI insights.
6. **Continuous Monitoring**: Repeats analysis and trades as the market evolves.

## 📈 Analytical System
### **Relative Strength Index (RSI)**
- Measures momentum on a **0-100 scale**.
- **Above 70**: Overbought (potential sell signal).
- **Below 30**: Oversold (potential buy signal).

### **Volume-Weighted Average Price (VWAP)**
- Calculates the **average price** adjusted for volume.
- **Above VWAP**: Overvalued (potential sell signal).
- **Below VWAP**: Undervalued (potential buy signal).

### **Moving Averages**
- **50-day & 200-day moving averages** help detect trends.
- **Golden Cross (50-day crosses above 200-day)**: Bullish signal.
- **Death Cross (50-day crosses below 200-day)**: Bearish signal.

### **Robinhood Analyst Ratings**
- Aggregates **buy, hold, and sell** recommendations.
- Provides sentiment analysis based on expert insights.

## 🤖 AI-Powered Decision Making
The bot formulates decisions using OpenAI based on:
- RSI, VWAP, moving averages, and analyst ratings.
- User-defined constraints (e.g., budget, stock exclusions, portfolio size).
