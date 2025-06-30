# 🧠 Heart Disease Prediction using Decision Trees and Random Forests

This project is focused on learning **tree-based models** for classification using the Heart Disease Dataset.

---

## 📌 Objective

To train, evaluate, and interpret tree-based models such as:
- **Decision Tree Classifier**
- **Random Forest Classifier**

---

## 🛠 Tools Used

- Python 
- Scikit-learn
- Pandas, Numpy
- Matplotlib, Seaborn
- Graphviz (for tree visualization)

---

## 📂 Dataset

- **Heart Disease Dataset**  
  Source: [Kaggle Link](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)

---

## 📊 Steps Performed

### 1. Data Loading & Exploration
- Loaded dataset using `pandas`
- Checked null values, data types, and statistical summary
- Plotted correlation heatmap to understand feature relationships

### 2. Data Splitting
- Divided the dataset into training and test sets using an 80:20 ratio.

### 3. Decision Tree Model
- Trained a base Decision Tree
- Accuracy: **~78%**
- Visualized the tree using `plot_tree`

### 4. Overfitting Analysis
- Trained a pruned Decision Tree with `max_depth=3`
- Accuracy: **Improved generalization** with ~80%

### 5. Random Forest Model
- Trained a Random Forest with 100 estimators
- Accuracy: **~85%**
- Much better performance due to ensemble learning

### 6. Feature Importance
- Extracted feature importances from Random Forest
- Visualized them in a bar chart

### 7. Cross-Validation
- Performed 5-fold cross-validation
- Mean CV Accuracy: **~83.5%**

---

## 📈 Results Summary

| Model             | Accuracy |
|------------------|----------|
| Decision Tree     | ~78%     |
| Pruned Tree       | ~80%     |
| Random Forest     | ~85%     |
| Cross-Validation (RF) | ~83.5%  |

---


## 📚 Concepts Learned

- How Decision Trees split data using **entropy** and **information gain**
- How **overfitting** occurs and can be prevented using tree pruning
- How **Random Forests** improve performance through **bagging**
- How to interpret **feature importance** in ensemble models
- How to use **cross-validation** for model evaluation

