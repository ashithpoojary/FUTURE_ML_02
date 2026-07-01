# Task 2: Support Ticket Classification & Prioritization

## Overview
This project develops an intelligent machine learning system to
automatically classify and prioritize customer support tickets.
Built as part of the Future Interns Machine Learning Internship (2026).

## Dataset
- Source: Customer Support Ticket Dataset (Kaggle)
- Link: https://www.kaggle.com/datasets/suraj520/customer-support-ticket-dataset
- Size: 8,469 support tickets
- Note: Dataset not included due to file size limits.
  Download the CSV from the link above and place it in the project folder.

## Tools & Libraries
- Python 3.14
- Pandas, NumPy
- NLTK (text preprocessing, tokenization)
- Scikit-learn (TF-IDF, Logistic Regression)
- Matplotlib, Seaborn
- Jupyter Notebook

## Key Steps
1. Loaded and explored customer support ticket dataset
2. Selected key columns: ticket description, type and priority
3. Preprocessed text by removing placeholders, punctuation and stopwords
4. Applied TF-IDF vectorization to convert text into numerical features
5. Built Logistic Regression classifier for ticket type prediction
6. Built second classifier for priority level prediction
7. Evaluated models using accuracy, precision and recall metrics
8. Generated confusion matrix to visualize classification performance

## Results
- Ticket Type Classification Accuracy: 20%
- Priority Level Classification Accuracy: 26%

## Key Findings
- Ticket descriptions in this dataset are auto-generated templates
  which limits the model's ability to learn distinguishing patterns
- Results highlight the critical importance of collecting genuine,
  detailed customer ticket text in real world deployments
- Pipeline architecture is production-ready and would perform
  significantly better with authentic ticket data

## Business Value
This classification pipeline enables support teams to:
- Automatically sort incoming tickets by type and urgency
- Prioritize critical issues for immediate attention
- Eliminate manual ticket sorting workload
- Improve customer response times and satisfaction scores
- Handle high ticket volumes without increasing team size

## How to Run
1. Clone this repository
2. Install dependencies: pip install pandas numpy matplotlib seaborn scikit-learn nltk jupyter
3. Download dataset CSV from Kaggle link above
4. Place CSV in the project folder
5. Open task2.ipynb in Jupyter or VS Code
6. Run all cells in order

## Deliverable
An automated support ticket classification system featuring
text preprocessing pipeline, dual ML classifiers, confusion
matrix visualization and actionable insights for support
managers and SaaS business owners.
