# 🚢 Titanic Survival Prediction

This project analyzes the Titanic dataset to predict passenger survival based on demographic and travel information using machine learning. It includes data cleaning, exploratory analysis, feature engineering, model training, and evaluation.

![Titanic](https://www.kaggle.com/c/titanic/data)

---

## 📁 Project Structure
📦 Titanic-Survival
├── Titanic.ipynb # Main Jupyter notebook
├── README.md # Project documentation
└── requirements.txt # List of dependencies

---

## 🎯 Objective

Predict which passengers survived the Titanic disaster using supervised learning models trained on key features like age, sex, fare, and passenger class.

---

## 🧰 Libraries & Tools Used

| Category            | Libraries & Tools                                      |
|---------------------|--------------------------------------------------------|
| 📊 Data Handling     | `pandas`, `numpy`                                      |
| 📈 Visualization     | `matplotlib`, `seaborn`                                |
| 🧹 Data Preprocessing| `sklearn.preprocessing`, `SimpleImputer`, `LabelEncoder` |
| 🤖 Modeling          | `scikit-learn` (Logistic Regression, Decision Trees, Random Forest) |
| 🧪 Evaluation        | `sklearn.metrics` (accuracy, confusion matrix, etc.)   |
| 📒 Notebook Runtime  | `Jupyter Notebook`                                     |

---

## 📊 Dataset Features

- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Sex**: Gender
- **Age**: Age in years
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Fare**: Ticket fare
- **Embarked**: Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

---

## 📌 Key Steps in the Notebook

1. **Data Cleaning**: Handling missing values (`Age`, `Embarked`, etc.)
2. **Exploratory Data Analysis (EDA)**: Correlations, survival distributions
3. **Feature Engineering**: Encoding categorical data, scaling, imputing
4. **Model Training**: Logistic Regression, Decision Tree, Random Forest
5. **Evaluation**: Accuracy, Confusion Matrix, Cross-validation

---

## 📈 Sample Results

- Best accuracy: ~`XX%` (update with your actual score)
- Top model: `RandomForestClassifier` with optimized parameters

---

## ⚙️ How to Run

```bash
# Clone the repo
git clone https://github.com/klan86at/titanic-survival.git
cd titanic-survival

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook Titanic.ipynb

