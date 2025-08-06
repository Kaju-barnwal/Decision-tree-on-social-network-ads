# 🎯 Predicting Purchase Behaviour Using Decision Trees

This project applies a **Decision Tree Classifier** on social network advertisement data to predict whether a user will purchase a product based on their **age** and **estimated salary**. The model is evaluated using both a validation set and a **10-fold cross-validation** approach.

---

## 📌 Problem Statement

> “Consider multivariate data for the classification of your choice and apply the decision tree algorithm for predicting class labels.  
> Test the accuracy of the model using a validation set and cross-validation approach.”

In this project, we aim to **classify users** based on their likelihood of purchasing a product after seeing a social media advertisement.

---

## 👥 Target Audience / Industry

**Domain**: Digital Marketing / E-commerce  
**Use case**: Targeted ad delivery, budget optimisation

---

## 📊 Dataset Information
> Dataset Source

My mentor provided this dataset [@ameenmanna8824](https://github.com/ameenmanna8824) on GitHub as part of my machine learning learning path.

- 📁 Link to dataset: [Social_Network_Ads.csv](https://raw.githubusercontent.com/ameenmanna8824/DATASETS/main/Social_Network_Ads.csv)
- 📌 Source repo: [DATASETS by ameenmanna8824](https://github.com/ameenmanna8824/DATASETS)


- **Source**: [Social Network Ads Dataset](https://raw.githubusercontent.com/ameenmanna8824/DATASETS/main/Social_Network_Ads.csv)
- **Total records**: 400
- **Input Features (X)**:
  - `Age` (Numerical)
  - `EstimatedSalary` (Numerical)
- **Target (y)**:
  - `Purchased` → Binary (0 = Not Purchased, 1 = Purchased)

---

## 🧰 Tools & Technologies

- Language: Python
- Libraries: `pandas`, `scikit-learn`, `matplotlib`, `seaborn`
- IDE: Google Colab / Jupyter Notebook
- Algorithms: Decision Tree Classifier
- Evaluation: Accuracy, Confusion Matrix, Cross-Validation

---

## 🔄 Project Workflow

1. ✅ Data Loading and Preprocessing  
2. 📊 Exploratory Data Analysis (EDA)  
3. 🧪 Feature Selection (Age and EstimatedSalary)  
4. 🌳 Decision Tree Classifier  
5. 🎯 Evaluation using:
   - Validation Set Accuracy
   - 10-Fold Cross-Validation  
6. 📈 Visualization (Tree structure & decision boundaries)

---

## 📈 Model Performance

- ✅ **Validation Set Accuracy**: `0.85` 
- ✅ **Mean Cross-Validation Accuracy**: `0.84` 
- Confusion matrix and classification report were used for deeper insight into model performance.

---

## 📊 Key Insights

- Users with **higher salary and age above 40** are more likely to purchase.
- The Decision Tree effectively splits based on **salary thresholds**.
- No major class imbalance was found.

---

## 🌳 Visualizations

- [ ] Decision Tree Plot (`plot_tree`)
- [ ] Scatter Plot for decision boundary (Age vs Salary)
- [ ] EDA Plots (Distribution of age, salary, etc.)

*You can save plots in a `/images` folder in your GitHub repo.*

---

## 🧾 How to Run

### Prerequisites:
- Python ≥ 3.8
- Jupyter Notebook / Google Colab

### Install packages:
```bash
pip install pandas scikit-learn matplotlib seaborn
