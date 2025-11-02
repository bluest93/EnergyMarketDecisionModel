# ⚡ Energy Market Trading Decision Model

This project builds a simple model to decide whether to **BUY**, **SELL**, or **HOLD** in the Nordic balancing (regulation) market.  
The decision is made using **expected settlement prices** predicted from historical market data.


## 🎯 Goal

The goal is to **maximize expected profit** by choosing the best action (Buy, Sell, or Hold) before the delivery hour (17:00–18:00).  
The decision is based on the probability that the **total regulation energy** will be **positive** — meaning the market needs more electricity (system short).



## 📦 Files

- `EnergyMarketModel.ipynb` — full notebook with feature creation, training, and decision logic  
- `TASK.pdf` — original assignment description  



## 🧩 Tools

- Python (pandas, scikit-learn, matplotlib)  
- Logistic Regression classifier
- XGBoost (`XGBClassifier`)



## 🏁 Summary

This model:
- Uses probabilities to predict market imbalance  
- Computes expected settlement prices  
- Makes trading decisions that **maximize expected profit**  
- Is simple, interpretable, and directly based on the market rules in `TASK.pdf`
