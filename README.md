# NIFTY AI Market Bias Predictor

A notebook-based machine learning system that estimates the **next-day directional bias**
(**Bullish / Bearish / No Trade**) for the NIFTY index using historical OHLC price action.

---
## 🔍 What this project does
- Trains a statistical model on historical NIFTY data
- Uses **yesterday’s OHLC** as input
- Produces a **directional bias**, not a price target
- Adds **price-action overrides** for realism
- Optionally explains the result using an AI assistant (Hugging Face)
---
## 🧠 Why “Bias” and not “Prediction”?
Markets are probabilistic.  
This project intentionally avoids over-promising and focuses on **directional edge**, the way real trading desks think.
---
## ⚙️ Requirements
Install dependencies using:
```bash
pip install -r requirements.txt
```
---
## ▶️ How to run
1. Open the notebook:
   `nifty_ai_market_bias_predictor.ipynb`
2. Run all cells
3. When prompted, enter **yesterday’s OHLC values**
4. Review the output:
   - Probability
   - Signal (Bullish / Bearish / No Trade)
   - Reasoning
---
## 🔐 Optional: AI Explanation
If you want natural-language explanations, set the environment variable:
```
HF_TOKEN=your_huggingface_token
```
(Recommended to store this in Colab Secrets or a `.env` file)
---
## ⚠️ Disclaimer
This project is for **educational purposes only**.  
It is **not financial advice** and should not be used for live trading decisions.
