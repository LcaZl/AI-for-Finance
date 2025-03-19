# **AI for Finance Assignments and Project**

## **Overview**
This repository consists of four assignments and a final project, focusing on financial analysis and AI applications in finance. The work includes mainly **portfolio analysis, recession forecasting, bank failure prediction and loan default risk assessment**. 

## **Data Sources**
- **Eikon Database**
- **Fama-French Dataset** (Risk-free rates, market factors)
- **Federal Reserve Bank of St. Louis** (NBER Recessions, Treasury TERM spread)
- **Investing.com & Yahoo Finance** (Stock and market data)
- **Other Macroeconomic Indicators** (GDP, Federal Funds Rate, Corporate Bond Spreads)

## **Project Structure**
- **Assignment 1: Portfolio Risk & Return Estimation**
  - Estimate **CAPM Beta & Alpha** for individual stocks.
  - Construct and analyze a **diversified portfolio**.
  - Evaluate portfolio performance during crises and the impact of adding **risk-free assets**.
  - Implement **Fama-French three-factor models**.

- **Assignment 2: Recession Prediction**
  - Analyze the predictive power of the **Treasury TERM spread** for US recessions.
  - Implement **Probit, Logit, Probabilistic Neural Network (PNN) and Multilayer Perceptron (MLP)** models.
  - Compute **AUROC scores** for in-sample and pseudo-out-of-sample evaluations.

- **Assignment 3: Systematic Bank Failure Prediction**
  - Identify leading indicators of **bank failures**.
  - Perform **multicollinearity analysis** to select relevant variables.
  - Implement **Probit, Logit, PNN, MLP, Random Forest, SVM and Tree Ensemble** models.
  - Compare performance using **AUROC scores**.

- **Assignment 4: Loan Default Risk Prediction**
  - Analyze **loan default probabilities** using a mix of financial indicators.
  - Assess missing data, standardize variables and evaluate multicollinearity.
  - Implement **Logit, KNN, Gradient Boosting, Random Forest and Neural Networks**.
  - Deploy a **web-based prediction tool using Voila**.

- **Final Project: Stock Price Movement Prediction**
  - Predict the probability of **stock price increase or decrease**.
  - Use **historical stock data from Eikon**.
  - Implement and Econometric analysis and one tha leverage a Neural Network
  - Evaluate performance using **classification metrics (AUROC, Accuracy, Precision, Recall)**.

## **Usage**
### **1. Set Up a Virtual Environment**
It is recommended to run this project in a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On macOS/Linux
pip install -r requirements.txt
```

### **2. Running the Jupyter Notebooks**
Use notebooks, each corresponds to an assignment.

### **3. Running the Web App for Loan Default Prediction**
The fourth assignment includes a **web interface** for predicting stock price movements that need Voila application. To run it use:
```bash
voila WebApp.ipynb
```
This will launch the interactive **Voila-based dashboard**.

