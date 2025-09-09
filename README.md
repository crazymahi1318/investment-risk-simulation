# 💹 Investment Risk Simulation using Monte Carlo | Python

## 📌 Overview
This project demonstrates how to use **Monte Carlo Simulation** to model financial investment risk.  
It predicts possible portfolio outcomes, calculates key risk metrics, and visualizes **single-asset** and **multi-asset portfolios**.  

---

## 🛠️ Tools & Libraries
- **Python** 🐍: Programming language  
- **NumPy** 🔢: Random number generation and calculations  
- **Pandas** 📊: Data handling  
- **Matplotlib & Seaborn** 📈: Visualizations  

---

## 🚀 Project Workflow

1. **Define Investment Parameters**  
   - Initial Investment: ₹10,00,000 💰  
   - Expected Return: 8% (single asset) 📈  
   - Volatility: 20% ⚠️  
   - Simulations: 10,000 🔄  

2. **Run Monte Carlo Simulations**  
   - Generate 10,000 random returns 🎲  
   - Calculate portfolio values 💹  

3. **Analyze Results**  
   - Mean portfolio value ➡️ Average expected return  
   - Median portfolio value ➡️ Middle outcome  
   - Probability of loss ❌  

4. **Visualize Portfolio Outcomes**  
   - Histograms and KDE curves 📊  
   - Break-even line highlighted 🟥  

5. **Value at Risk (VaR)**  
   - Calculate 95% confidence VaR 📉  

6. **Multi-Asset Portfolio**  
   - Stocks + Bonds with 60:40 weights 🏦📈  
   - Compare single vs multi-asset portfolios 🔍  

---

## 💡 Key Learnings
- Monte Carlo simulation provides **risk and return distributions** 📊  
- **Probability of Loss** and **VaR** quantify investment risk ⚠️  
- **Diversification** reduces portfolio risk 🛡️  
- Visualizations improve interpretation and decision-making 🎨  

---

## 📊 Results

### Single Asset Portfolio
![Single Asset Histogram](results/histogram_single.png)

### Multi-Asset Portfolio
![Multi Asset Histogram](results/histogram_multi.png)

---

## 🔗 GitHub Notebook
[View Full Notebook](InvestmentRiskSimulation_MonteCarlo.ipynb)

---

- Developed a Monte Carlo simulation to model **investment risk** and **portfolio returns** 💹  
- Ran 10,000+ simulations using **NumPy** to capture volatility and uncertainty 🔢  
- Visualized outcome distributions and calculated **Value at Risk (VaR)** 📉  
- Compared single-asset vs multi-asset portfolios to demonstrate **diversification benefits** 🏦  
