# AI Financial Advisor 📈🤖

An intelligent, interactive AI-powered financial advisor notebook that integrates probabilistic reasoning, optimization strategies, rule-based systems, and natural language understanding (NLU) to help users make informed decisions regarding budgeting, debt management, investment planning, and retirement.

## 🚀 Features

- **Semantic Intent Detection (`FinancialNLP`)**: Uses a lightweight SentenceTransformer (`paraphrase-MiniLM-L6-v2`) to detect search intent (e.g., debt management, investment, budgeting, retirement) using cosine similarity.
- **Probabilistic Risk Assessment (`BayesianFinancialModel`)**: Calculates debt and investment risks based on demographic info, income, expenses, and market conditions using Bayesian-style Conditional Probability Tables (CPTs).
- **Optimization Engines (`FinancialSearchSpace`)**:
  - **Debt Repayment**: Recommends the optimal strategy (Snowball vs. Avalanche method) based on balance, interest rate, and total interest saved.
  - **Asset Allocation**: Recommends optimal splits (Stocks, Bonds, Cash) tailored to age and risk tolerance.
- **Forward-Chaining Rule Engine (`EnhancedInferenceEngine`)**: Fires logical rules to make concrete recommendations, generating an explanation trace to ensure transparency.
- **Interactive UI**: Powered by **Gradio** for a seamless, web-based interaction.

---

## 🛠️ Tech Stack & Dependencies

- **Python 3.x**
- **Jupyter Notebook**
- **Libraries**:
  - `gradio` (Interactive GUI)
  - `plotly` (Visualizations & charts)
  - `sentence-transformers` (NLU / Intent detection)
  - `scikit-learn` (Cosine similarity computations)
  - `numpy` (Mathematical utilities)

---

## 💻 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/Shaheeryy/AI_Financial_Advisor.git
cd AI_Financial_Advisor
```

### 2. Install Dependencies
Make sure you have python installed, then run:
```bash
pip install -r requirements.txt
```
*(Alternatively, simply run the notebook cells which contain installation commands like `!pip install gradio`)*

### 3. Run the Advisor
Open the notebook in your Jupyter environment or Google Colab and run all cells:
```bash
jupyter notebook finance_advisor.ipynb
```
Once executed, a local/public Gradio sharing link will be generated where you can interact with the app.

---

## 👤 Author
- **Shaheer Khan Marwat**
- **Email**: [shaheerkhanmarwat921545@gmail.com](mailto:shaheerkhanmarwat921545@gmail.com)
- **GitHub**: [@Shaheeryy](https://github.com/Shaheeryy)
