# Demo
# **CryptoBuddy 🤖💰**
*A Python-based cryptocurrency advisory chatbot using rule-based AI*

![Chatbot Demo](https://github.com/Vosty17/Sreen.jpeg/blob/main/Screenshot_20250526-195400.png ) *(Optional: Add a screenshot or GIF here)*

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
   git clone https://github.com/yourusername/cryptobuddy.git
   cd cryptobuddy
   ```

2. Run the chatbot (Python 3.6+ required)
   ```bash
   python cryptobuddy.py
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

## 🔄 Extending the Project
Want to improve CryptoBuddy? Here’s how:
1. Add real-time data*→ Integrate the [CoinGecko API](https://www.coingecko.com/en/api)
2. Enhance NLP → Use libraries like `NLTK` or `spaCy`
3. Add more cryptos → Expand `crypto_db` with new coins

---

## ⚠️ Disclaimer
>"This is an educational project. Cryptocurrency investments are risky—always DYOR (Do Your Own Research)."

---

## License
MIT © 2025 [Stephen Wafula ]

---

### 🔗 Connect
[GitHub](https://github.com/Vosty@17)
