**Diabetes Detection using Machine Learning**
Overview
This project implements a Diabetes Detection System using machine learning models. The system analyzes medical parameters to determine whether a person has diabetes or not. It trains five different machine learning models and selects the best-performing one for predictions.

🔹 Key Features:
✅ Five machine learning models for classification
✅ Automatic selection of the best performing model
✅ Exploratory Data Analysis (EDA) for statistical insights
✅ Support for multiple environments using requirements.txt

Project Structure
📂 diabetes.csv – Contains the dataset used for training and evaluation.
📂 eda.py – Performs exploratory data analysis (EDA) using Matplotlib and Seaborn.
📂 model.py – Implements five machine learning models and selects the best one for prediction.
📂 requirements.txt – Lists all the necessary libraries for the project.
📂 readme.txt – Provides steps to set up and activate the environment and install dependencies.

**Installation and Setup**
1️⃣ Create a Virtual Environment (Recommended)
python -m venv env

2️⃣ Activate the Virtual Environment
On Windows:
.\env\Scripts\activate
On macOS/Linux:
source env/bin/activate

3️⃣ Install Dependencies
pip install -r requirements.txt


Usage
1️⃣ Running Exploratory Data Analysis (EDA)
To visualize the dataset and analyze feature distributions, run:
python eda.py

2️⃣ Training and Selecting the Best Model
To train the models and identify the best-performing one, run:
python model.py
The script will train Logistic Regression, Random Forest, XGBoost, Support Vector Machine (SVM), and K-Nearest Neighbors (KNN), selecting the best-performing model based on evaluation metrics.

Example Usage
🔹 Example User Input (CSV Format):
Pregnancies	Glucose	Blood Pressure	Skin Thickness	Insulin	BMI	  Diabetes Pedigree	Age
     3	      120	       80	             25	         100	  28.5	  0.5	             35

  ![Screenshot 2025-03-13 152208](https://github.com/user-attachments/assets/fd29a3ff-686b-4ec5-a99c-f928dcb66f66)

🔹 Predicted Output:
"Based on the input values, the system predicts: Positive for Diabetes."
