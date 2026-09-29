# 📊 Telco Customer Churn Analysis

## 📌 Project Overview

This project focuses on analyzing **telecom customer churn** to understand customer behavior, identify churn patterns, and generate actionable business insights.

The analysis was performed using **Python, Pandas, Matplotlib, Seaborn, and Jupyter Notebook**.

The project covers the complete data analysis process, starting from data understanding and cleaning to exploratory data analysis, customer segmentation, advanced churn analysis, and business recommendations.

---

## 🎯 Project Objective

The main objective of this project is to:

* Understand the telecom customer dataset.
* Clean and validate the data.
* Perform Exploratory Data Analysis (EDA).
* Segment customers based on their tenure.
* Analyze churn patterns across different customer groups.
* Identify factors associated with customer churn.
* Create visualizations to communicate insights.
* Provide business recommendations to improve customer retention.

### Business Question

> **Which types of customers are more likely to churn, and what factors are associated with customer churn?**

---

## 📂 Dataset

The dataset contains information about **7,043 telecom customers** and **21 columns**.

### Important Columns

| Column             | Description                              |
| ------------------ | ---------------------------------------- |
| `customerID`       | Unique customer identifier               |
| `gender`           | Customer gender                          |
| `SeniorCitizen`    | Senior citizen indicator                 |
| `Partner`          | Whether the customer has a partner       |
| `Dependents`       | Whether the customer has dependents      |
| `tenure`           | Number of months the customer has stayed |
| `PhoneService`     | Phone service subscription               |
| `MultipleLines`    | Multiple line subscription               |
| `InternetService`  | Internet service type                    |
| `OnlineSecurity`   | Online security subscription             |
| `OnlineBackup`     | Online backup subscription               |
| `DeviceProtection` | Device protection subscription           |
| `TechSupport`      | Technical support subscription           |
| `StreamingTV`      | Streaming TV subscription                |
| `StreamingMovies`  | Streaming movies subscription            |
| `Contract`         | Customer contract type                   |
| `PaperlessBilling` | Paperless billing status                 |
| `PaymentMethod`    | Customer payment method                  |
| `MonthlyCharges`   | Monthly customer charges                 |
| `TotalCharges`     | Total customer charges                   |
| `Churn`            | Whether the customer churned             |

---

## 🛠️ Tools & Technologies

* 🐍 Python
* 🐼 Pandas
* 📊 Matplotlib
* 📈 Seaborn
* 📓 Jupyter Notebook
* 🔧 Git & GitHub

---

# 🔄 Project Workflow

```text
Telco Customer Churn Dataset
            │
            ▼
   1. Data Understanding
            │
            ▼
   2. Data Cleaning
            │
            ▼
   3. Exploratory Data Analysis
            │
            ▼
   4. Customer Segmentation
            │
            ▼
   5. Advanced Churn Analysis
            │
            ▼
   6. Key Insights
            │
            ▼
   7. Business Recommendations
            │
            ▼
       Final Report
```

---

# 📌 Project Steps

## Step 1 — Data Understanding

The first step was to understand the structure and characteristics of the dataset.

### Activities

* Loaded the dataset using Pandas.
* Checked the number of rows and columns.
* Displayed the first 10 records.
* Checked column names and data types.
* Checked missing values.
* Reviewed descriptive statistics.
* Examined the churn distribution.

### Dataset Size

```text
Rows: 7,043
Columns: 21
```

---

## Step 2 — Data Cleaning

The dataset was cleaned before performing analysis.

### Cleaning Activities

* Checked missing values.
* Identified blank values in `TotalCharges`.
* Converted `TotalCharges` from object/string to numeric.
* Handled missing values.
* Checked duplicate records.
* Checked duplicate customer IDs.
* Standardized column names to lowercase.
* Replaced spaces with underscores where applicable.

### Final Data Quality

```text
Rows: 7,043
Columns: 21
Missing Values: 0
Duplicate Rows: 0
Duplicate Customer IDs: 0
```

---

## Step 3 — Exploratory Data Analysis

EDA was performed to understand customer behavior and identify important patterns.

### Statistical Analysis

Calculated:

* Mean
* Median
* Mode

For important numerical variables:

* `tenure`
* `monthlycharges`
* `totalcharges`

### Visualizations

Created:

* Histograms
* Box plots
* Churn distribution chart
* Average comparison charts

The analysis also compared:

* Tenure by churn status
* Monthly charges by churn status
* Total charges by churn status

---

## Step 4 — Customer Segmentation

Customers were segmented based on their tenure.

### Tenure Groups

| Tenure Group |              Months |
| ------------ | ------------------: |
| 0–12 Months  |             0 to 12 |
| 13–36 Months |            13 to 36 |
| 37+ Months   | 37 months and above |

### Analysis Performed

* Customer count by tenure group
* Customer percentage by tenure group
* Average monthly charges by tenure group
* Churn rate by tenure group

### Visualizations

* Customer distribution donut/pie chart
* Average monthly charges bar chart
* Churn rate comparison

---

## Step 5 — Advanced Churn Analysis

The project further analyzed churn across different customer characteristics.

### Areas Analyzed

#### 👥 Gender

Compared churn rates between different gender groups.

#### 👴 Senior Citizen

Analyzed churn differences between:

* Senior Citizens
* Non-Senior Citizens

#### 💳 Payment Method

Compared churn rates across different payment methods.

#### 📄 Contract Type

Analyzed churn across:

* Month-to-month
* One year
* Two year

#### 🔄 Contract × Payment Method

A heatmap was created to understand the relationship between contract type and payment method.

#### 📅 Customer Lifecycle

Tenure categories were used to understand customer churn throughout different lifecycle stages.

---

# 📊 Key Findings

The analysis identified several important customer churn patterns.

### Overall Churn

```text
Total Customers: 7,043
Churned Customers: 1,869
Overall Churn Rate: 26.54%
```

### Key Areas

The project analyzed:

* Overall churn rate
* Churn by tenure group
* Churn by gender
* Churn by senior citizen status
* Churn by payment method
* Churn by contract type
* Monthly charges and churn
* Customer lifecycle and churn

> Specific group-level findings are based on the calculations and visualizations generated in the project notebook.

---

# 💡 Business Recommendations

Based on the analysis, the following areas can be considered for customer retention:

### 1. Improve New Customer Onboarding

Customers in the early stage of their lifecycle can be monitored closely and provided with better onboarding and support.

### 2. Encourage Long-Term Contracts

Customers can be encouraged to move toward longer-term contracts through suitable offers and benefits.

### 3. Monitor High-Risk Payment Methods

Payment methods associated with higher churn rates should be investigated to understand possible payment or customer-experience issues.

### 4. Develop Customer Retention Strategies

Customer behavior can be analyzed to identify high-risk customers and provide targeted retention offers.

### 5. Improve Customer Support

Additional support and personalized communication can be considered for customer groups showing higher churn rates.

---

# 📈 Project Visualizations

The project includes visualizations such as:

* Churn Distribution
* Tenure Distribution
* Monthly Charges Histogram
* Monthly Charges Box Plot
* Customer Tenure Segmentation
* Tenure Category Donut Chart
* Average Monthly Charges by Tenure
* Churn by Gender
* Churn by Senior Citizen
* Churn by Payment Method
* Churn by Contract Type
* Contract × Payment Method Heatmap

---

# 📁 Project Structure

```text
Telco-Customer-Churn-Analysis/
│
├── Dataset/
│   └── Telco_Customer_Churn_Dataset.csv
│
├── Notebook/
│   └── Telco_Customer_Churn_Analysis.ipynb
│
├── Charts/
│   ├── Churn_Distribution.png
│   ├── Tenure_Distribution.png
│   ├── Monthly_Charges_Histogram.png
│   ├── Monthly_Charges_Boxplot.png
│   ├── Tenure_Category_Donut.png
│   ├── Average_Monthly_Charges.png
│   ├── Churn_by_Gender.png
│   ├── Churn_by_Senior_Citizen.png
│   ├── Churn_by_Payment_Method.png
│   ├── Churn_by_Contract.png
│   └── Contract_Payment_Heatmap.png
│
├── Report/
│   └── Customer_Churn_Analysis_Report.pdf
│
└── README.md
```

---

# 🚀 How to Run the Project

### Step 1 — Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2 — Open the Project

Open the project folder in:

* Jupyter Notebook
* JupyterLab
* VS Code
* Google Colab

### Step 3 — Install Required Libraries

```bash
pip install pandas matplotlib seaborn jupyter
```

### Step 4 — Open the Notebook

```text
Notebook/
└── Telco_Customer_Churn_Analysis.ipynb
```

### Step 5 — Run the Notebook

Run the cells sequentially from **Step 1 to Step 5** and review the generated analysis and visualizations.

---

# 📌 Skills Demonstrated

Through this project, I practiced:

* Data Understanding
* Data Cleaning
* Data Validation
* Exploratory Data Analysis
* Statistical Analysis
* Customer Segmentation
* Data Visualization
* Business Analysis
* Insight Generation
* Business Recommendations
* Python Data Analysis
* GitHub Project Documentation

---

# 🎓 Learning Outcome

This project helped me develop practical experience in converting a raw telecom dataset into meaningful business insights.

I learned how to:

> **Understand → Clean → Analyze → Visualize → Segment → Interpret → Recommend**

The project also improved my practical knowledge of **Python, Pandas, Matplotlib, Seaborn, EDA, and business-oriented data analysis**.

---

# 👨‍💻 Author

**Vikash Rao**

Aspiring Data Analyst

### Skills

`Excel` · `SQL` · `Python` · `Pandas` · `Power BI` · `Data Analysis`

---

## ⭐ Project Status

```text
Completed ✅
```

If you found this project useful, feel free to ⭐ the repository.
