
# Portfolio-Optimization

This repository contains an implementation of portfolio optimization techniques, focusing on **Monte Carlo simulations** and **Factor Modeling**. The goal is to optimize investment portfolios using a combination of simulations and factor-driven insights to assess the risk-return profile.

## Features

- **Monte Carlo Simulation**: Simulates various portfolio allocations across numerous market scenarios to evaluate potential risks and returns.
- **Factor Modeling**: Utilizes financial factors (such as market, value, size, momentum) to model asset returns and optimize portfolio allocations.
- **Optimization Techniques**: Combines Monte Carlo simulations and factor modeling to find the optimal portfolio allocation that balances risk and return.
- **Visualization**: Includes various visualizations for portfolio performance, risk metrics, and simulated outcomes.

## Installation

### Prerequisites

To use this repository, you'll need Python and Jupyter Notebook installed, along with some key dependencies.

1. **Clone the repository**:
   ```bash
   git clone https://github.com/MohammedReza9/Portfolio-Optimization.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd Portfolio-Optimization
   ```

3. **Create a virtual environment and install the dependencies**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use 'venv\Scriptsctivate'
   pip install -r requirements.txt
   ```

4. **Install Jupyter Notebook**:
   ```bash
   pip install jupyter
   ```

## Usage

### Jupyter Notebooks

This repository includes two Jupyter notebooks for portfolio optimization:

1. **Factor-Based Portfolio Optimization**:
   - The `Factor_Based_Portfolio_Optimization.ipynb` notebook applies factor models to optimize portfolios based on key financial factors like market, value, size, and momentum.
   - **How to run**:
     - Open the notebook: `Factor_Based_Portfolio_Optimization.ipynb`
     - Execute the cells sequentially to perform factor modeling and analyze the optimized portfolio.

2. **Monte Carlo Portfolio Optimization**:
   - The `Monte_Carlo_Portfolio_Optimization.ipynb` notebook runs Monte Carlo simulations to generate different portfolio allocations and visualizes risk-return trade-offs and Sharpe ratios.
   - **How to run**:
     - Open the notebook: `Monte_Carlo_Portfolio_Optimization.ipynb`
     - Execute the cells sequentially to simulate portfolios and visualize results.

### How to Start Jupyter Notebook:

Once you've installed the required dependencies and activated the virtual environment, run the following command to launch Jupyter Notebook:

```bash
jupyter notebook
```

This will open Jupyter in your browser, and you can open the notebooks from there.


### Visualizations

Both notebooks contain visualizations, including:
- Portfolio efficiency frontier
- Risk-return tradeoff
- Distribution of simulated portfolios
- Optimal asset allocation chart

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Feel free to fork the repository, open issues, and submit pull requests.

---

For any questions or suggestions, feel free to open an issue or contact me directly via GitHub.
