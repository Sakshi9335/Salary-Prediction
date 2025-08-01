
# Salary Prediction 🚀

### Ensemble Learning–Based Salary Estimation Project

**By Sakshi Shukla**

---

## 🔍 Overview  
This project aims to predict salaries based on key inputs such as experience, job role, and location using **Ensemble Learning** techniques. The models used are **Random Forest** and **XGBoost**, combined to improve prediction accuracy.

---

## 🛠 Features  
- Cleaned and preprocessed salary dataset  
- In-depth **Exploratory Data Analysis (EDA)** to identify key salary influencers  
- Model training using **Random Forest** and **XGBoost**  
- Evaluation metrics include **R² Score**, **MAE**, and **RMSE**  
- Implemented **Voting Regressor** for better prediction performance

---

## 🗂 Repository Structure  
```

├── data/                 # Dataset file(s)
├── Salary\_Prediction.ipynb  # Jupyter Notebook with EDA and model training
├── README.md             # Project documentation

````

---

## ⚙️ How to Run  
1. Clone the repo:
   ```bash
   git clone https://github.com/Sakshi9335/Salary-Prediction.git
   cd Salary-Prediction
````

2. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost
   ```

3. Open the notebook:

   * Launch Jupyter Notebook or VS Code
   * Open `Salary_Prediction.ipynb` and run all cells

---

## 🧠 Model Results

| Model           | RMSE      | R² Score |
| --------------- | --------- | -------- |
| Random Forest   | 4,200     | 0.88     |
| XGBoost         | 3,950     | 0.91     |
| Voting Ensemble | **3,800** | **0.93** |

The **Voting Ensemble** showed the highest accuracy by combining both models' strengths.

---

## 🚀 Future Scope

* Add more features: education, skills, industry, company size
* Use **live salary datasets** for real-time insights
* (Optional) Build an interactive web app using Streamlit in the future

---

## 📝 License

This project is open-source and available under the **MIT License**.

---

## 📞 Contact

**Sakshi Shukla**
GitHub: [Sakshi9335](https://github.com/Sakshi9335)

`
