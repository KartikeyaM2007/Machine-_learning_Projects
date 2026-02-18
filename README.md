📊 Height vs Weight – Linear Regression

This project demonstrates a simple Machine Learning regression problem using Linear Regression to model the relationship between a person’s weight and height.

The notebook walks through data loading, visualization, preprocessing, model training, evaluation, and prediction.

🚀 Project Overview

The goal of this project is to:

Explore the relationship between Weight and Height

Visualize the dataset

Apply feature scaling

Train a Linear Regression model

Evaluate model performance

Make predictions

🗂 Dataset

The project uses:

height-weight.csv


Expected columns:

Weight

Height

🛠 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

📈 Steps Performed
1️⃣ Data Loading

Read CSV using Pandas

2️⃣ Data Exploration

Display dataset preview

Compute correlations

3️⃣ Data Visualization

Scatter plot (Weight vs Height)

Pairplot for feature relationships

4️⃣ Feature Selection

Independent variable → Weight

Dependent variable → Height

5️⃣ Train-Test Split

75% Training

25% Testing

6️⃣ Feature Scaling

StandardScaler applied

7️⃣ Model Training

Linear Regression model

8️⃣ Model Evaluation

Metrics calculated:

MSE (Mean Squared Error)

MAE (Mean Absolute Error)

RMSE (Root Mean Squared Error)

R² Score

9️⃣ Prediction

Predict height for new weight values

📊 Model Output

The model learns:

Coefficient (Slope) → Relationship strength

Intercept → Baseline height

Example prediction:

regression.predict(scaler.transform([[72]]))

▶️ How to Run

Clone the repository:

git clone https://github.com/yourusername/Machine-_learning_Projects.git


Install dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn


Open the notebook:

jupyter notebook

🎯 Learning Objective

This project is intended for beginners to understand:

✅ Regression problems
✅ Data preprocessing
✅ Feature scaling
✅ Linear Regression workflow
✅ Model evaluation

📌 Future Improvements

Possible enhancements:

Add more features

Try Polynomial Regression

Compare multiple algorithms

Deploy as a web app

👨‍💻 Author

Kartikeya
Machine Learning & AI Enthusiast
