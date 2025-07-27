
# 📈 Portfolio Optimization Techniques in Python

This repository presents two robust approaches to portfolio optimization—**Factor-Based Modeling** and **Monte Carlo Simulation**—implemented in Python using real financial data. The goal is to identify optimal asset allocations that maximize return and minimize risk, applying core quantitative finance concepts such as the efficient frontier, Sharpe ratio, and factor exposures.

---

## 🔍 Project Overview

### 1. **Factor-Based Portfolio Optimization**
Implements a four-factor model (Market, Size, Value, Momentum) to estimate expected returns based on historical factor exposures and solve a **mean-variance optimization** problem. The strategy supports monthly rebalancing and compares performance against equal-weighted benchmarks.

> 📂 Notebook: `Factor_Based_Portfolio_Optimization.ipynb`

**Key Features:**
- Rolling factor regressions (Fama-French 3 + Momentum)
- Estimation of expected returns using factor premiums
- Long-only quadratic optimization (CVXPY)
- Monthly rebalancing strategy
- Visual comparison with equal-weighted portfolio
- Educational annotations for explainability

---

### 2. **Monte Carlo Portfolio Optimization**
Uses simulated portfolios to explore the **efficient frontier**, identify the **maximum Sharpe ratio portfolio**, and visualize portfolio distributions. A backtest is included for the optimal and minimum variance portfolios versus SPY and equal-weighted benchmarks.

> 📂 Notebook: `Monte_Carlo_Portfolio_Optimization.ipynb`

**Key Features:**
- Random generation of 10,000+ portfolios
- Sharpe ratio maximization and volatility minimization
- Efficient frontier with annotated optimal portfolios
- Backtest over 6 months of out-of-sample data (2025 H1)
- Detailed breakdown of calculations and visuals

---

## ⚙️ Setup Instructions

```bash
git clone https://github.com/MohammedReza9/Portfolio-Optimization.git
cd Portfolio-Optimization
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

---

## 📊 Example Visuals

| Efficient Frontier | Monthly Rebalanced Cumulative Return |
|--------------------|---------------------------------------|
| (<img width="1088" height="583" alt="image" src="https://github.com/user-attachments/assets/21bac234-12f0-4b08-bcab-125e21e06ab6" />) | (<img width="1184" height="582" alt="image" src="https://github.com/user-attachments/assets/d7d44d84-5eb8-488c-b9b8-2e54a2dea042" />) |

---

## 🧠 Techniques Used

- **Fama-French Factor Regression**
- **Mean-Variance Optimization (CVXPY)**
- **Monte Carlo Simulation**
- **Backtesting and Benchmarking**
- **Matplotlib Visualizations**
- **Sharpe Ratio & Risk Analysis**

---

## 📂 File Structure

```bash
├── Factor_Based_Portfolio_Optimization.ipynb
├── Monte_Carlo_Portfolio_Optimization.ipynb
├── README.md
├── requirements.txt
```

---

## 📌 Notes for Recruiters & Hiring Managers

This repository is designed to demonstrate:
- Strong foundational knowledge of portfolio theory and financial modeling
- Ability to implement quantitative research in Python
- Attention to performance evaluation and reproducibility
- Clear documentation and explainability of complex concepts

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo, open issues, or submit pull requests with suggestions or improvements.
