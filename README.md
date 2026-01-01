📊 Energy Consumption Prediction Project

This project focuses on analyzing and predicting energy consumption using historical energy and weather data.
Machine Learning models are applied to understand patterns and forecast future energy usage.

📁 Project Structure
.
├── 3rdTry.ipynb            # Main Jupyter Notebook (model training & visualization)
├── 2020.xlsx               # Dataset (energy )
├── 2021.xlsx
├── 2022.xlsx
├── 2023.xlsx
├── 2024.xlsx
├── README.md               # Project documentation

🧠 Project Overview

The goal of this project is to:

Load and clean energy consumption data.

Merge it with corresponding weather information.

Train multiple regression models.

Compare their performance.

Visualize results and predictions.

The project uses machine learning regression techniques to predict energy consumption based on historical patterns and weather conditions.

🛠️ Technologies & Libraries Used

Python 3.x

Pandas

NumPy

Matplotlib

Scikit-learn

Install all required libraries using:

pip install pandas numpy matplotlib scikit-learn

📂 Dataset Description
2020.xlsx

Contains:

Monthly energy consumption data

Weather-related features (temperature, humidity, etc.)

The dataset is automatically loaded and processed inside the notebook.

🚀 How to Run the Project

Clone or download the repository

git clone <your-repository-link>
cd your-repo-folder


Open the Jupyter Notebook

jupyter notebook


Open:

3rdTry.ipynb


Run all cells in order from top to bottom.

⚙️ Workflow Summary
1️⃣ Data Loading

Reads the Excel dataset and prepares it for processing.

2️⃣ Data Cleaning & Preparation

Removes unnecessary columns

Handles missing values

Merges energy and weather datasets

3️⃣ Feature Engineering

Selects relevant input features

Prepares target variable (energy consumption)

4️⃣ Model Training

The following models are trained and evaluated:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

5️⃣ Model Evaluation

Performance comparison using metrics such as:

R² Score

Mean Squared Error (MSE)

Visualization of predictions vs actual values

6️⃣ Visualization

The notebook generates graphs such as:

Energy consumption trends

Actual vs predicted values

Model comparison charts

📈 Output & Results

After running the notebook, you will obtain:

Trained regression models

Performance metrics printed in the notebook

Visual plots showing prediction accuracy

These results help determine which model performs best for energy consumption forecasting.

📌 Notes

Make sure the Excel file remains in the same directory as the notebook.

The code is modular and can be extended with:

More features

Different ML models

Larger datasets

👨‍💻 Author

Dia Arar
first Machine Learning Project
