**CryptoBuddy 🤖💰**
*A Python-based cryptocurrency advisory chatbot using rule-based AI*

![Chatbot Demo](https://github.com/Vosty17/ScreenshotDemo.jpeg/blob/main/IMG_20250527_132805.jpg )
## Demo video 
![Bot video](https://github.com/BerniceJewel/AI-Powered-Financial-Sidekick/blob/main/demo%20video.mp4)
## 📌 Overview
CryptoBuddy is a **command-line chatbot** that helps users get quick insights on cryptocurrency investments based on:
- **Price trends** 📈
- **Market capitalization** 💰
- **Sustainability scores** ♻️

Built with **Python** and designed with **OOP principles**, it mimics basic AI decision-making using predefined rules.

---

## ✨ Features
- ✅ **Personalized crypto recommendations**
- ✅ **Three query modes**: Trends, Sustainability, Investment Advice
- ✅ **Simple keyword-based NLP**
- ✅ **Expandable cryptocurrency database**
- ✅ **User-friendly interface with emojis**

---

## 🛠️ Installation
1. Clone the repository
   ```bash
    https://github.com/BerniceJewel/AI-Powered-Financial-Sidekick
   cd AI-Powered-Financial-Sidekick
   ```

2. Run the chatbot (Python 3.6+ required)
   ```bash
   python cryptoBuddy.py
   ```

---

## 💡 How It Works
The chatbot uses rule-based logic to analyze a predefined dataset:
```python
crypto_db = {
    "Bitcoin": {"price_trend": "rising", "sustainability_score": 3/10},
    "Cardano": {"price_trend": "rising", "sustainability_score": 8/10},
    # ... more coins
}
```
### Decision-Making Logic
- For sustainability queries→ Recommends coins with highest `sustainability_score`
- For trending queries→ Filters coins with `price_trend = "rising"`
- For investments→ Prioritizes high `market_cap` + rising trends

---

## 📝 Example Queries
Try asking:
1. *"Which crypto is most sustainable?"*
2. *"What’s trending in the market?"*
3. *"What should I invest in for long-term growth?"*

---

## ⚠️ Disclaimer
>"This is an educational project. Cryptocurrency investments are risky—always DYOR (Do Your Own Research)."

---
