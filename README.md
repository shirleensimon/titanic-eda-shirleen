# titanic-eda-shirleen
Exploratory Data Analysis on Titanic dataset
# 🛳️ Titanic EDA Project (Shirleen Simon)

This project presents an **Exploratory Data Analysis (EDA)** of the Titanic dataset from Kaggle.  
It explores patterns and relationships in the data to better understand survival rates and identify important features.

🔗 [View the original notebook on Kaggle](https://www.kaggle.com/code/shirleensimon/titanic-eda-shirleen)

📄 [Download the PDF write-up](./Titanic_EDA_Summary_Shirleen.pdf)

---

## 📁 Project Structure

titanic-eda/
├── data/  
│   └── train.csv  
├── notebooks/  
│   └── titanic_eda.ipynb  
├── Titanic_EDA_Summary_Shirleen.pdf  
├── requirements.txt  
└── README.md  

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

## ▶️ How to Run

To run this notebook locally:

1. Clone this repository
2. Install dependencies  
   ```bash
   pip install -r requirements.txt

Open Notebook

jupyter notebook notebooks/titanic_eda.ipynb
