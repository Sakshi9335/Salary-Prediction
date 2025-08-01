
# Salary Prediction using Ensemble Learning

This project aims to predict employee salaries using ensemble learning techniques. It leverages multiple machine learning models to improve prediction accuracy based on key features like age, gender, education level, job title, and experience.

## 📁 Files in This Repository
 **`Salary_Prediction_Model.ipynb`**  
  Contains all the code for data preprocessing, model training, evaluation, and visualization.

- **`salary_data.csv`**  
  Dataset containing employee attributes and corresponding salaries.

## 📊 Dataset Overview

The dataset includes the following columns:

| Column               | Description                              |
|----------------------|------------------------------------------|
| Age                  | Age of the employee                      |
| Gender               | Gender (Male/Female)                     |
| Education Level      | Highest qualification                    |
| Job Title            | Current role or designation              |
| Years of Experience  | Work experience in years                 |
| Salary               | Annual salary (Target variable)          |

## 🛠️ Technologies & Libraries Used

- **Python**
- **pandas, numpy** – Data handling and manipulation
- **matplotlib, seaborn** – Data visualization
- **sklearn** – Machine learning models and evaluation

## 🤖 Machine Learning Models Used

This project uses the following **ensemble regression models** from `scikit-learn`:

1. **Random Forest Regressor**
2. **Gradient Boosting Regressor**
3. **AdaBoost Regressor**
4. **Voting Regressor** (combination of the above)

## ⚙️ Model Evaluation Metrics

Each model was evaluated using:

- **R² Score** (Coefficient of Determination)
- **MSE** (Mean Squared Error)
- **RMSE** (Root Mean Squared Error)


\---Random Forest---
R2 Score: 0.91
MSE: 1200.45
RMSE: 34.64

\---Gradient Boosting---
R2 Score: 0.89
...

\---Voting Regressor---
R2 Score: 0.93
...

````

## 🚀 How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/Sakshi9335/Salary-Prediction.git
````

2. Navigate to the project folder:

   ```bash
   cd Salary-Prediction
   ```
3. Open the Jupyter Notebook:

jupyter notebook Salary_Prediction_Model.ipynb
   ```

## 📈 Results Summary

The **Voting Regressor** provided the best overall performance in terms of R² Score and RMSE, combining the strengths of all base models.

## 🔮 Future Scope

* Feature engineering for better model accuracy
* Deployment as a web app using Flask or Streamlit
* Real-time salary prediction with new data

## 📝 Acknowledgements

* Dataset curated for educational purposes
* Inspired by practical applications in HR analytics and data science

---
 by [Sakshi9335](https://github.com/Sakshi9335)


