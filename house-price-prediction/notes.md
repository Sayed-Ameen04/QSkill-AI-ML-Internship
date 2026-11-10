🏠 House Price Prediction using Machine Learning
A machine learning project that predicts house prices using the California Housing dataset and Linear Regression.

This project was completed as part of my QSkill Artificial Intelligence & Machine Learning Internship.

📌 Project Overview
House prices depend on multiple factors such as location, income levels, number of rooms, population, and other housing-related characteristics.

In this project, a Linear Regression model is trained to learn the relationship between these features and median house values.

The project covers the complete machine learning workflow:

Dataset
   ↓
Exploratory Data Analysis
   ↓
Train/Test Split
   ↓
Feature Scaling
   ↓
Linear Regression
   ↓
Predictions
   ↓
Model Evaluation
📊 Dataset
The project uses the California Housing dataset available through scikit-learn.

The dataset contains information about California districts, including features such as:

Median income
House age
Average number of rooms
Average number of bedrooms
Population
Average occupancy
Latitude
Longitude
The target variable is:

MedHouseVal — median house value, represented in units of $100,000.

🛠️ Technologies & Libraries
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook
🔍 Project Workflow
1. Data Loading
The California Housing dataset is loaded using scikit-learn and converted into a Pandas DataFrame.

2. Exploratory Data Analysis
The dataset is explored using:

Dataset shape
Data types
Summary statistics
Missing-value checks
Target-value distribution
3. Train/Test Split
The dataset is divided into:

80% training data
20% testing data
A fixed random state is used to make the results reproducible.

4. Feature Scaling
StandardScaler is used to standardize the numerical features.

The scaler is fitted only on the training data and then applied to both training and testing data to avoid data leakage.

5. Model Training
A Linear Regression model from Scikit-learn is trained on the scaled training data.

6. Prediction
The trained model predicts house values for previously unseen test data.

7. Model Evaluation
The model is evaluated using:

MAE (Mean Absolute Error)
RMSE (Root Mean Squared Error)
R² Score
An actual-vs-predicted plot is also used to visually evaluate the predictions.

📈 Model
Algorithm: Linear Regression

Linear Regression learns a relationship between the input features and the target value and uses that relationship to make predictions on unseen data.

📁 Project Structure
house-price-prediction/
│
├── house-price-prediction.ipynb
└── README.md
▶️ How to Run
1. Clone the repository
git clone https://github.com/Sayed-Ameen04/house-price-prediction.git
2. Navigate to the project
cd house-price-prediction
3. Install dependencies
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
4. Open the notebook
jupyter notebook
Then open:

house-price-prediction.ipynb
Run the cells from top to bottom.

💡 Key Learnings
Through this project, I practiced:

Loading and exploring a real-world dataset
Performing basic exploratory data analysis
Separating features and target variables
Splitting data into training and testing sets
Feature scaling using StandardScaler
Training a Linear Regression model
Making predictions on unseen data
Evaluating regression models using MAE, RMSE, and R²
Understanding the importance of avoiding data leakage
🎯 Internship
QSkill — Artificial Intelligence & Machine Learning Internship

This project was completed as one of the machine learning tasks assigned during the internship.

👤 Author
Sayed Ameen

GitHub: Sayed-Ameen04
LinkedIn: md-ameen-syed
