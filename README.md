# 📊 LLM-Driven Blockchain Analytics with The Graph

This project demonstrates how to integrate structured blockchain data indexed via **The Graph Protocol** with **Large Language Models (LLMs)** such as GPT-4 for intelligent data analysis, trend prediction, and behavioral insights.

---

## 🚀 Project Goal

To automate the extraction, processing, and interpretation of blockchain metadata from a subgraph using LLMs — enabling natural language analytics over decentralized data.

---

## 📁 Features

- 🔗 **GraphQL Data Retrieval** from a subgraph API endpoint  
- 🧹 **Data Preprocessing** using Python and Pandas  
- 🧠 **LLM Integration** (e.g., GPT-4 via OpenAI API) for:
  - Descriptive summaries
  - Trend forecasting
  - Anomaly detection  
- 📄 **CSV Export** for seamless model input
- 🗂️ Example: Analysis of `graphNetworks` and `graphAccounts` entities

---

## 📌 Subgraph Details

- **Subgraph ID**: `DZz4kDTdmzWLWsV373w2bSmoar3umKKH9y82SUKr5qmp`  
- **Data Retrieved**:
  - `graphNetworks`: Network configurations (controller, token, epoch manager)
  - `graphAccounts`: Blockchain accounts with names and timestamps

---

## 🧪 Technologies Used

- Python (requests, pandas)
- GraphQL
- OpenAI API (GPT-3.5 / GPT-4)
- Jupyter Notebooks
- Markdown + LaTeX for documentation

---

## 🧰 Installation & Usage

```bash
# Clone the repo
git clone https://github.com/your-repo/blockchain-llm-analytics.git
cd blockchain-llm-analytics

# Install dependencies
pip install -r requirements.txt

# Run the notebook or script
jupyter notebook analysis.ipynb
