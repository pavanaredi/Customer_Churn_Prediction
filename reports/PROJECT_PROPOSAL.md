# My Project Plan: Customer Churn Prediction

**Who**: Pavan | EBPL Data Science Internship | June 2026

---

## The Problem

A telecom company is losing customers. About 1 in 4 customers leave each year. Nobody really knows why or how to stop it.

**Why This Matters**:
- Getting new customers is really expensive
- Keeping an existing customer costs way less
- If we can figure out who's about to leave, we can do something about it
- Every customer we save = more money for the company

## What I Want To Do

1. **Build a predictor** - Create a model that's at least 70% accurate at spotting who's about to leave
2. **Find the reasons** - Figure out the top 10 things that make customers leave
3. **Give solutions** - Suggest specific things the company can do to keep more customers
4. **Show my work** - Document everything so anyone can understand and use it

---

## The Data I'll Use

**Dataset Name**: Telco Customer Churn (from Kaggle)

**Size**: 7,043 real customers, 20 pieces of info about each

**What Info I'll Have**:
- Basic stuff: Customer ID, gender, family status
- Services: Internet, phone, security, streaming
- Account info: Contract type, how they pay, how long they've been there
- Money: How much they pay monthly, total they've paid
- Target: Whether they left or stayed (27% left)

**Good News**: Clean data, no missing values

---

## My Plan (5 Days)

**Day 1: Get To Know The Data**
- Load it up and look around
- Check if anything's broken
- Understand the data (graphs, numbers, patterns)
- See how many customers left vs stayed

**Day 2: Clean & Prepare**
- Fix any problems
- Convert text to numbers
- Make sure all numbers are on the same scale
- Split into training (80%) and testing (20%)

**Day 3: Explore Patterns**
- Make visualizations
- Check which factors matter
- Look for correlations
- Find interesting patterns

**Day 4: Build 3 Models**
- Model 1: Logistic Regression (simple)
- Model 2: Random Forest (medium complexity)
- Model 3: Gradient Boosting (advanced)
- Train all three and make predictions

**Day 5: Compare & Analyze**
- Which model is best?
- What are the most important factors?
- What should the company do?
- Create charts and documents

---

## The Models I'll Use

**Model 1: Logistic Regression**
- How it works: Draws a line to separate customers
- Good for: Easy to understand, fast
- Bad for: Can't handle complicated patterns
- Why use it: Shows if simple math works

**Model 2: Random Forest**
- How it works: Makes 100 decision trees
- Good for: Can find complicated patterns, shows what matters
- Bad for: Might memorize the training data too much
- Why use it: Better than simple model, tells us what's important

**Model 3: Gradient Boosting**
- How it works: Builds trees one by one, learning from mistakes
- Good for: Usually gets best results, finds complex patterns
- Bad for: Takes longer to train
- Why use it: Try to get the best possible accuracy

## How I'll Know If They Work

- **Accuracy**: Out of 100 predictions, how many are right?
- **Precision**: When I predict someone will leave, am I usually correct?
- **Recall**: Do I catch most of the people who actually leave?
- **F1-Score**: Overall how good is the balance?
- **ROC-AUC**: How well does the model distinguish between the two groups?

---

## What I'll Deliver

**Code Stuff**:
- ✓ One Jupyter notebook with all my work
- ✓ Clean code with comments
- ✓ 8 steps from data to results

**Pictures & Charts**:
- ✓ Churn graphs
- ✓ Heatmap showing what matters
- ✓ Feature importance bar chart
- ✓ Model comparison

**Documents**:
- ✓ This proposal
- ✓ How I did it (technical doc)
- ✓ What I found (findings doc)
- ✓ What they should do (recommendations)
- ✓ Final internship report

**GitHub**:
- ✓ Everything on GitHub
- ✓ Instructions how to use it
- ✓ List of what packages needed
- ✓ Ready to share

## My Goals
- **Model Accuracy**: At least 70%, hopefully 70-75%
- **Understanding**: Clearly identify top 10 reasons for churn
- **Business Impact**: Actionable retention strategies

---

## 6. Technical Stack

### Languages & Frameworks
- **Python 3.12**: Primary language
- **Jupyter Notebook**: Development environment

### Libraries
- **Data**: Pandas, NumPy
- **ML**: Scikit-learn
- **Visualization**: Matplotlib, Seaborn

### Tools
- **Version Control**: Git, GitHub
- **Environment**: Virtual environment (venv)

---

## 7. Project Timeline

```
Week 1: Setup & Exploration
├── Environment setup
├── Data loading & exploration
└── Initial EDA

Week 2: Preprocessing & Analysis
├── Data cleaning
├── Feature engineering
└── Statistical analysis

Week 3: Modeling
├── Model development
├── Hyperparameter tuning
└── Model comparison

Week 4: Documentation & Submission
├── Report writing
├── Code finalization
├── GitHub push
└── Presentation
```

---

## 8. Success Criteria

### Technical Criteria
- ✅ Models built and trained successfully
- ✅ Accuracy achieved: >70%
- ✅ Feature importance extracted
- ✅ Code well-documented

### Documentation Criteria
- ✅ README.md complete
- ✅ Internship report finished
- ✅ Methodology documented
- ✅ Findings summarized

### Repository Criteria
- ✅ Code pushed to GitHub
- ✅ Proper folder structure
- ✅ .gitignore configured
- ✅ requirements.txt included

---

## 9. Learning Objectives

### Technical Skills
- Master data preprocessing techniques
- Understand ML model selection
- Learn feature importance analysis
- Practice model evaluation
- Develop data visualization skills

### Professional Skills
- Write technical documentation
- Present findings clearly
- Organize code professionally
- Collaborate using version control
- Think about business impact

---

## 10. Risks & Mitigations

| Risk | Probability | Mitigation |
|------|-------------|-----------|
| Data quality issues | Low | Use public dataset, validate early |
| Model overfitting | Medium | Use cross-validation, test set |
| Low accuracy | Low | Try multiple algorithms |
| Time constraints | Low | Plan tasks in phases |

---

## 11. Approval & Sign-Off

**Project Lead**: Data Science Internship Program  
**Date**: June 2026  
**Status**: ✅ APPROVED

---

## 12. Next Steps

1. ✅ Finalize project scope
2. ✅ Set up development environment
3. ✅ Load and explore data
4. ✅ Begin preprocessing
5. ✅ Build models
6. ✅ Generate reports
7. ✅ Push to GitHub
8. ✅ Present findings

---

**Proposal Status**: READY FOR IMPLEMENTATION ✅
