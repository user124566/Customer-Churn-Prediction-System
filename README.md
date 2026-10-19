# 📊 Customer Churn Prediction System

### Turning Telecom Data into Smarter Customer Retention Decisions 🚀

An end-to-end data analytics and machine learning project that combines **SQL Server, Python, and Power BI** to analyse customer churn, predict customers at risk of leaving, and present actionable insights through interactive dashboards.

> 💡 **The Goal:** Understand why customers leave, identify potential churners, and help businesses make better data-driven retention decisions.

---

## 🌟 Project at a Glance

| 🔹 Component | 🔹 What It Does |
|---|---|
| 🗄️ SQL Server | Cleans, validates, and prepares customer data |
| 🐍 Python | Analyses customer behaviour and builds ML models |
| 🤖 Machine Learning | Predicts which customers may be at risk of churning |
| 📊 Power BI | Visualises churn trends, KPIs, and prediction results |

---

## 🔄 How It Works

```text
   📁 CUSTOMER DATA
          │
          ▼
   🗄️ SQL SERVER
   Clean & Prepare Data
          │
          ▼
   🐍 PYTHON + ML
   Train & Test Models
          │
          ▼
   🎯 CHURN PREDICTIONS
   Identify At-Risk Customers
          │
          ▼
   📊 POWER BI DASHBOARD
   Explore Insights & Trends
          │
          ▼
   💡 SMARTER RETENTION DECISIONS
```

---

## 🎯 Why This Project Matters

Customer churn is a major challenge for telecom businesses. When customers leave, companies can lose recurring revenue and spend more on acquiring replacements.

This project explores customer data to answer important business questions:

- 📉 **Churn Trends:** How many customers have left?
- 👥 **Customer Behaviour:** Which customer groups have higher churn rates?
- 📄 **Contract Analysis:** How are contract types related to churn?
- 💰 **Revenue Insights:** How do monthly charges and customer tenure relate to churn?
- 🎯 **Risk Prediction:** Which customers may be more likely to leave?
- 📊 **Business Reporting:** How can these findings support retention planning?

---

## 🛠️ Tech Stack

<details>
<summary><strong>View technologies and their purpose</strong></summary>

| Technology | Purpose |
|---|---|
| Microsoft SQL Server | Data storage and preparation |
| SQL / T-SQL | Data cleaning, exploration, and queries |
| Python | Data processing and analysis |
| Pandas & NumPy | Data manipulation |
| Scikit-learn | Machine learning and model evaluation |
| XGBoost | Gradient-boosted classification |
| Power BI | Interactive dashboards |
| Power Query | Data transformation |
| DAX | KPIs and analytical measures |
| Jupyter Notebook | Model development and experimentation |
| Git & GitHub | Version control and project documentation |

</details>

---

## 🤖 Machine Learning Models

Three classification algorithms are explored to compare their ability to predict customer churn.

| Model | Why It Is Used |
|---|---|
| Logistic Regression | Establishes a baseline for churn prediction |
| Random Forest | Learns complex patterns in customer data |
| XGBoost | Uses gradient boosting to improve predictive performance |

**Model workflow:**

1. Load and explore the dataset.
2. Clean the data and prepare features.
3. Encode categorical variables where required.
4. Split the data into training and testing sets (80/20).
5. Train and evaluate the models.
6. Generate customer-level predictions.
7. Prepare prediction outputs for Power BI.

**Evaluation metrics:** Accuracy, Precision, Recall, F1-score, ROC-AUC, and Confusion Matrix.

*The best-performing model will be determined by actual test results, not assumed in advance.*

---

## 📊 Power BI Dashboard

Explore customer churn through two reporting pages.

### 1. 📈 Churn Overview

Understand overall churn performance, customer status, and important business trends.

![Churn Summary Dashboard](assets/images/Summary.PNG)

### 2. 🎯 Churn Prediction

Explore customer-level predictions and identify customers who may need further attention.

![Churn Prediction Dashboard](assets/images/Prediction.PNG)

*Dashboard previews will appear once the corresponding screenshots are added to the repository.*

---

## 📂 Project Structure

```text
Customer-Churn-Prediction-System/
│
├── 📁 data/
│   └── Customer_Data.csv
│
├── 📁 notebooks/
│   └── churn_prediction_model.ipynb
│
├── 📁 sql/
│   └── churn_queries.sql
│
├── 📁 powerbi/
│   └── ChurnAnalysis.pbix
│
├── 📁 docs/
│   └── Power_Query_and_DAX.md
│
├── 📁 assets/
│   └── images/
│       ├── Summary.PNG
│       └── Prediction.PNG
│
├── requirements.txt
├── .gitignore
└── README.md
```

---

## 🚀 Getting Started

Follow these steps to run the project on your computer.

### Step 1 — Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/Customer-Churn-Prediction-System.git
cd Customer-Churn-Prediction-System
```

Replace `YOUR-USERNAME` with your GitHub username.

### Step 2 — Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 3 — Prepare the Data

- Import the customer dataset into SQL Server.
- Run the queries in `sql/churn_queries.sql`.
- Review the cleaned data and analytical views.

### Step 4 — Run the Machine Learning Notebook

```bash
jupyter notebook
```

Open `notebooks/churn_prediction_model.ipynb` and run the cells in order.

### Step 5 — Open the Dashboard

Open `powerbi/ChurnAnalysis.pbix` in Power BI Desktop, configure your data sources, and refresh the data.

---

## 📁 Dataset Overview

The dataset contains telecom customer information, including demographics, subscribed services, contract details, billing information, and customer status.

**Key columns include:**

- `Customer_ID` — Customer identifier
- `Gender` — Recorded gender category
- `Age` — Customer age
- `Tenure_in_Months` — Customer tenure
- `Internet_Service` — Internet service type
- `Contract` — Contract category
- `Monthly_Charge` — Monthly charges
- `Total_Revenue` — Recorded customer revenue
- `Customer_Status` — Customer status

---

## 💼 Business Benefits

This project demonstrates how data can support:

- 🎯 More focused customer retention campaigns
- 📉 Better understanding of churn patterns
- 👥 Identification of potentially high-risk customer segments
- 💰 Analysis of customer tenure and revenue
- 📊 Clearer reporting for business stakeholders
- 🧠 Evidence-based decision-making

*Predictions indicate potential risk, not certainty. Retention decisions should consider business context and model limitations.*

---

## 🔮 Future Improvements

- [ ] Add automated data quality checks.
- [ ] Tune model hyperparameters.
- [ ] Add SHAP-based model explanations.
- [ ] Create customer churn risk categories.
- [ ] Automate prediction exports.
- [ ] Improve dashboard interactivity.
- [ ] Track model performance over time.

---

## 👩‍💻 Skills Demonstrated

`SQL` · `Python` · `Machine Learning` · `Data Cleaning` · `Exploratory Data Analysis` · `Power BI` · `DAX` · `Data Visualisation` · `Business Intelligence` · `Git`

---

### ⭐ If you find this project interesting, consider starring the repository!

*Built to demonstrate an end-to-end approach to customer analytics, machine learning, and business intelligence.*

