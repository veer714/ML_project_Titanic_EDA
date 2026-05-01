# 🚢 Titanic Survival Prediction - Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project explores the famous **Titanic dataset** to analyze passenger survival patterns.  
The goal is to perform **Exploratory Data Analysis (EDA)**, uncover insights about survival factors, and prepare the dataset for machine learning models.

---

## 📂 Dataset
- **File:** `train_and_test2.csv`
- **Rows:** 1309
- **Features:**
  - `Pclass` – Passenger class (1st, 2nd, 3rd)
  - `Sex` – Gender
  - `Age` – Age in years
  - `SibSp` – Number of siblings/spouses aboard
  - `Parch` – Number of parents/children aboard
  - `Fare` – Ticket fare

---

## 🔍 Workflow
1. **Data Cleaning**
   - Handle missing values (Age, Embarked)
   - Convert categorical variables into numerical form
   - Feature scaling for continuous variables

2. **Exploratory Data Analysis (EDA)**
   - Distribution plots for Age, Fare
   - Survival rates by gender, class, and embarkation port
   - Correlation heatmap to identify key predictors

3. **Feature Engineering**
   - Binning Age and Fare into categories
   - One-hot encoding for categorical variables

---

## 📊 Key Insights
- **Gender:** Females had a much higher survival rate than males.
- **Class:** Passengers in 1st class were more likely to survive than those in 3rd class.
- **Age:** Children had better survival chances compared to adults.
- **Embarkation:** Port of embarkation showed slight differences in survival rates.

---

## ⚙️ Tools & Libraries
- Python (Jupyter Notebook)
- Pandas & NumPy – Data manipulation
- Matplotlib & Seaborn – Visualization

---

## 🚀 Next Steps
- Apply advanced models (Random Forest, Gradient Boosting)
- Perform hyperparameter tuning
- Deploy as a simple web app for interactive predictions

---

## ▶️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/veer714/ML_project_Titanic_EDA.git
   cd ML_project_Titanic_EDA
