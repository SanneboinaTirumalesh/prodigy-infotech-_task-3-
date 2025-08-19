# prodigy-infotech-_task-3-
#  Task 03 - Decision Tree Classifier on Bank Marketing Dataset

##  Project Overview
This project builds a **Decision Tree Classifier** to predict whether a customer will purchase a product or service based on their **demographic** and **behavioral** data.  
We use the **Bank Marketing dataset** from the UCI Machine Learning Repository.

The goal is to:
- Preprocess the dataset (handle categorical + numerical features)
- Train a Decision Tree classifier
- Evaluate performance using multiple metrics
- Visualize results (Decision Tree, Confusion Matrix, Feature Importance, ROC Curve)

---

##  Dataset
We use the dataset: **`bank-additional-full.csv`**  
This dataset contains information about direct marketing campaigns of a Portuguese banking institution.  

Target column:  
- `y` → Indicates whether the client subscribed to a term deposit (`yes` / `no`).

 Dataset Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)

---

##  Installation & Requirements
Make sure you have Python 3.x installed. Install the required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
