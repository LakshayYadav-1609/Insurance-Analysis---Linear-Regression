📊 Insurance Charges Analysis — Linear Regression Model
This project analyzes an insurance dataset and builds a Multiple Linear Regression model to predict medical insurance charges based on customer attributes such as age, BMI, number of children, salary, hospital history, and lifestyle factors.

GitHub sometimes fails to render large Jupyter notebooks.  
Click the link below to view the fully rendered notebook on **nbviewer**:
👉 **[Open Notebook in nbviewer](https://nbviewer.org/github/LakshayYadav-1609/Insurance-Analysis---Linear-Regression/blob/main/LR%20code/Linear_Regression_Final.ipynb)**

🚀 Project Objectives
Understand relationships between customer features and insurance charges

Build a regression model using scikit‑learn
Evaluate model performance using MAE, MSE, RMSE, and R²
Visualize predictions vs actual values
Identify the most influential features

📁 Dataset Description
The dataset contains the following columns:

Column Name	Description
age	Age of the person
sex	Male/Female
bmi	Body Mass Index
children	Number of dependents
smoker	Yes/No
region	Residential region
Claim_Amount	Previous claim amount
past_consultations	Number of doctor visits
num_of_steps	Daily steps
Hospital_expenditure	Past hospital expenses
NUmber_of_past_hospitalizations	Count of hospitalizations
Anual_Salary	Annual income
charges	Insurance charges (target variable)

🧠 Model Used
Multiple Linear Regression  
Implemented using:
python
from sklearn.linear_model import LinearRegression
📈 Model Evaluation Metrics
MAE — Mean Absolute Error
MSE — Mean Squared Error
RMSE — Root Mean Squared Error
R² Score — Goodness of fit

📉 Visualizations
Scatter plot: Actual vs Predicted charges

Residual analysis
Feature importance (coefficients)

🛠️ Technologies Used
Python

Pandas
NumPy
Matplotlib
Seaborn
Scikit‑learn

📦 How to Run
bash
pip install -r requirements.txt
python Linear_Regression.py

✨ Author
Lalit Yadav  
GitHub: https://github.com/LakshayYadav-1609
