Title:Personal Expense Categorization Assistant

Overview:

An automated system to classify personal finance transactions into expense categories and generate monthly spending summaries using a hybrid rule-based + ML approach.

Dataset:
Kaggle: Personal Budget Transactions Dataset
Transaction details include date, description, amount, and category.
Approach:

* Regex Rules:High-confidence keyword-based tagging
* ML Model:TF-IDF + Logistic Regression / Naive Bayes
* Hybrid Logic:Rules → ML → LangChain (for ambiguous cases)

Tech Stack:
Python, Pandas, scikit-learn, Regex, LangChain

Evaluation:
* Confusion Matrix
* Accuracy, Precision, Recall, F1-score

Outputs:
* Categorized transactions (CSV)
* Monthly expense summary
* Confusion matrix visualization

Use Case:
Automates expense tracking and improves budgeting insights.



