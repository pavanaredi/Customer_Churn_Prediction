# Customer Churn Prediction

**EBPL Data Science Internship** | 2026 | By Pavan

## What This Project Does

I built a machine learning model to predict which customers of a telecom company will leave. I also figured out what makes customers want to leave so the company can fix those problems.

### What I Wanted To Accomplish
- Understand why 27% of customers are leaving
- Build a model that can predict which customers will leave
- Find the top reasons customers leave
- Give the company specific ideas to keep customers

## The Data

I used real customer data from a telecom company:
- **7,043 customers** in the dataset
- **20 pieces of info** about each customer
- **26.98% churned** = about 1,900 customers left
- **No missing data** (lucky!)

### What Info I Had About Customers
- Who they are (age, gender, family)
- What services they use (internet, phone, security features)
- Their contract details (1-month or 2-year? How do they pay?)
- How long they've been customers and how much they pay

## 📁 Project Structure

```
Customer-Churn-Prediction/
├── data/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── notebooks/
│   └── Customer_Churn.ipynb
├── models/
│   └── (trained models storage)
├── images/
│   └── (visualization outputs)
├── src/
│   └── (utility functions)
├── reports/
│   ├── PROJECT_PROPOSAL.md
│   ├── METHODOLOGY.md
│   └── FINDINGS.md
├── README.md
├── requirements.txt
├── .gitignore
└── INTERNSHIP_REPORT.md
```

## How I Did It

### Step 1: Clean The Data
- Checked for broken/missing data → None found ✓
- Removed duplicate records → None found ✓
- Converted text data to numbers
- Scaled everything to same range

### Step 2: Explore The Data
- Looked at churn patterns
- Checked which factors matter most
- Made some visualizations

### Step 3: Build 3 Models
I tried 3 different machine learning algorithms:
- **Logistic Regression**: Simple baseline → 73% accuracy
- **Random Forest**: Uses lots of trees → 73% accuracy
- **Gradient Boosting**: Advanced technique → 72.8% accuracy

### Step 4: Find What Matters
**Top 5 reasons customers leave:**
1. Monthly charges they pay
2. Specific customer factors
3. Total amount they've paid
4. How long they've been a customer
5. How they pay their bill

## What I Found

- **27% of customers leave** (about 1 in 4)
- **Best model**: Either Logistic Regression or Random Forest (same accuracy)
- **Main reasons they leave**: What they pay monthly, how long they've been with us, their contract type
- **Important**: Month-to-month customers leave more often than people with longer contracts

## How To Use This

```bash
# Get the code
git clone https://github.com/YOUR_USERNAME/Customer-Churn-Prediction.git
cd Customer-Churn-Prediction

# Install what you need
pip install -r requirements.txt

# Open the notebook
jupyter notebook notebooks/Customer_Churn.ipynb
```

## Tools I Used
- Python 3.12
- Pandas & NumPy (data work)
- Scikit-learn (machine learning)
- Matplotlib & Seaborn (charts)
MIT License
