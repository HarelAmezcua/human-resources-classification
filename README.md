# Employee Attrition Prediction

## 📌 Project Overview
This project aims to predict employee attrition using machine learning techniques. The dataset consists of various HR-related features, including demographic details, job roles, compensation, and performance indicators. The goal is to develop and compare multiple classifiers to determine which model best predicts whether an employee is likely to resign.

## 🏆 Objectives
- **Perform Data Cleaning**: Handle missing values, standardize formats, and preprocess categorical data.
- **Conduct Exploratory Data Analysis (EDA)**: Identify trends, correlations, and insights related to employee attrition.
- **Implement Machine Learning Models**:
  - Logistic Regression
  - Random Forest Classifier
  - Deep Neural Network (DNN)
- **Evaluate Model Performance**: Compare models based on accuracy, precision, recall, and F1-score.
- **Derive Business Insights**: Identify key factors influencing employee resignations.

## 📂 Dataset Information
The dataset includes the following features:

| Feature Name | Description |
|-------------|-------------|
| Age | Employee's age |
| Attrition | Whether the employee has left (Yes/No) |
| BusinessTravel | Frequency of travel for business purposes |
| DailyRate | Daily pay rate of the employee |
| Department | Department where the employee works |
| DistanceFromHome | Distance from the employee's home to the office |
| Education | Education level (numerical) |
| EducationField | Field of education |
| EmployeeCount | Number of employees (constant in dataset) |
| EmployeeNumber | Unique identifier for each employee |
| EnvironmentSatisfaction | Employee's satisfaction with the work environment (1-4) |
| Gender | Employee's gender |
| HourlyRate | Hourly pay rate |
| JobInvolvement | Level of job involvement (1-4) |
| JobLevel | Employee's job level in the company |
| JobRole | Specific job role within the company |
| JobSatisfaction | Satisfaction level with the job (1-4) |
| MaritalStatus | Marital status of the employee |
| MonthlyIncome | Monthly salary |
| MonthlyRate | Monthly rate of payment |
| NumCompaniesWorked | Number of companies the employee has worked for |
| Over18 | Whether the employee is over 18 years old (constant) |
| OverTime | Whether the employee works overtime (Yes/No) |
| PercentSalaryHike | Percentage increase in salary |
| PerformanceRating | Performance rating of the employee (1-4) |
| RelationshipSatisfaction | Employee's satisfaction with relationships at work (1-4) |
| StandardHours | Standard working hours (constant) |
| StockOptionLevel | Level of stock options granted (0-3) |
| TotalWorkingYears | Total years of work experience |
| TrainingTimesLastYear | Number of training sessions attended last year |
| WorkLifeBalance | Work-life balance rating (1-4) |
| YearsAtCompany | Number of years at the company |
| YearsInCurrentRole | Number of years in the current role |
| YearsSinceLastPromotion | Years since the last promotion |
| YearsWithCurrManager | Years working with the current manager |

## 🔧 Technologies & Tools
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-Learn, TensorFlow/Keras, Matplotlib, Seaborn
- **Machine Learning Algorithms**: Logistic Regression, Random Forest, Deep Neural Network (DNN)
- **Visualization Tools**: Matplotlib, Seaborn

## 📊 Exploratory Data Analysis (EDA)
- Analyzed attrition rates across different demographic and job-related factors.
- Explored correlations between job satisfaction, salary, overtime, and attrition.
- Visualized distributions, box plots, and heatmaps to uncover insights.

## 🏗️ Model Development
- **Logistic Regression**: Baseline classification model.
- **Random Forest**: Captures complex patterns and interactions between features.
- **Deep Neural Network (DNN)**: Used to capture deeper relationships and non-linear dependencies.

## 🎯 Model Evaluation
Each model was evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC Curve

## 🔍 Key Findings & Insights
- Employees working **overtime** are more likely to resign.
- **Job satisfaction** and **work-life balance** strongly correlate with attrition.
- Employees with **longer tenure** are less likely to leave.
- **Lower salary increases** contribute to higher attrition rates.

## 🚀 How to Run the Project
### Prerequisites
Ensure you have Python installed and the required libraries:
```bash
pip install pandas numpy scikit-learn tensorflow matplotlib seaborn
```
### Steps to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/hr-attrition-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd hr-attrition-prediction
   ```
3. Run the Jupyter Notebook or Python script:
   ```bash
   jupyter notebook
   ```
4. Execute the scripts step by step to preprocess data, explore features, and train models.

## 📌 Future Improvements
- Implement advanced feature engineering.
- Experiment with other models like XGBoost and SVM.
- Use hyperparameter tuning (GridSearchCV, RandomizedSearchCV).
- Deploy the best model as an API.

## 🤝 Contributions
Feel free to contribute by opening issues and submitting pull requests!

## 📩 Contact
For any questions, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/yourprofile) or email at your.email@example.com.

---
**⭐ If you found this project useful, give it a star on GitHub!**

