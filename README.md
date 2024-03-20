# Financial Cointegration Analysis

In financial markets, it's common to observe relationships between time series data that may appear correlated in the short term but lack a meaningful long-term connection. These apparent correlations, known as spurious correlations, can lead to misleading conclusions and ineffective trading strategies. To distinguish between spurious correlations and genuine long-term relationships, we employ the concept of cointegration and the Engle-Granger two-step method.

Cointegration allows us to identify pairs of non-stationary time series that exhibit a stable long-term relationship, even though they may individually drift apart in the short run. The Engle-Granger method provides a framework for testing cointegration, involving regression and residual analysis.

This project explores the concept of cointegration in financial time series data using the Engle-Granger two-step method. Cointegration refers to the long-term equilibrium relationship between non-stationary variables, implying that even though individual series may drift apart in the short run, they exhibit a stable relationship over time.

In this project, we utilize historical price data obtained from Yahoo Finance (via the yfinance library in Python) to analyze the cointegration between pairs of stocks. We aim to identify pairs of stocks that exhibit a stable long-term relationship, which can be exploited in trading strategies such as pairs trading.

## Table of Contents

- [Financial Cointegration Analysis](#financial-cointegration-analysis)
  - [Table of Contents](#table-of-contents)
  - [Dependencies](#dependencies)
  - [Setup](#setup)
  - [Usage](#usage)
  - [Contact](#contact)

## Dependencies

You can find the complete list of dependencies in the `requirements.txt` file.

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/BlcMed/financial-cointegration-analysis.git
   ```

2. Navigate to the project directory:

   ```bash
   cd financial-cointegration-analysis
   ```

3. Create and activate a virtual environment (optional but recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

4. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Open the notebook file in Jupyter Notebook or JupyterLab:

   ```bash
   jupyter notebook cointegration.ipynb
   ```

2. Follow the instructions in the notebook to execute the code and explore the project.

## Contact

For questions, feedback, or collaborations, please contact [BOULAICH Mohamed](mailto:boulaich.mohamed970@gmail.com).
