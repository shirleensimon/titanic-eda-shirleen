# titanic-eda-shirleen
Exploratory Data Analysis on Titanic dataset
# 🛳️ Titanic Dataset Exploratory Data Analysis (EDA)

This project involves a comprehensive exploratory data analysis (EDA) of the Titanic dataset. The objective was to uncover hidden patterns, identify factors affecting passenger survival, and prepare the dataset for future modeling.

🔗 [View Full Notebook on Kaggle](https://www.kaggle.com/code/shirleensimon/titanic-dataset-eda-project-shirleen)  
📄 [Download EDA Report (PDF)](./Shirleen_Simon_EDA.pdf)

---






## 📁 Project Structure

Titanic-EDA-Shirleen/
├── data/
│ └── titanic.csv # Raw dataset
├── notebooks/
│ └── titanic-eda-shirleen.ipynb # Jupyter notebook with EDA
├── Shirleen_Simon_EDA.pdf # PDF write-up of the EDA process
├── requirements.txt # List of dependencies
└── README.md # Project overview 

---

## 📊 Key Analysis Performed

- Handled missing values in `Age`, `Cabin`, and `Embarked` columns  
- Univariate analysis (distribution of age, fare, survival rate)  
- Bivariate analysis (survival rate by sex, class, age group, etc.)  
- Multivariate analysis and correlation heatmaps  
- Visualization with Seaborn and Matplotlib  
- Feature engineering (e.g., creating age groups)

---

## 💡 Key Lessons Learned

- **Data Cleaning**: Handling missing values can significantly affect analysis outcomes.
- **Visualization**: Charts like bar plots and heatmaps reveal relationships not obvious in raw data.
- **Feature Importance**: Gender and passenger class were strong indicators of survival.
- **Practical EDA Workflow**: Learned to approach data analysis systematically — from loading data to drawing insights.

---

## 🛠️ Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- Kaggle

---

## 🔚 Conclusion

The Titanic EDA project provided valuable insights into the factors influencing passenger survival, revealing strong correlations with gender, passenger class, and age. Through systematic analysis and visualization, this project demonstrated the importance of clean data and thoughtful feature exploration in uncovering meaningful patterns for future predictive modeling.

---

## ▶️ How to Run

To run this notebook locally:

1. Clone this repository
2. Install dependencies  
   ```bash
   pip install -r requirements.txt

Open Notebook

jupyter notebook notebooks/titanic_eda.ipynb
