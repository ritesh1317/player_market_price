Football Player Market Value Prediction
📌 Project Overview
This project aims to predict the market value (value_eur) of professional football players based on their physical attributes and performance metrics. By utilizing historical data from 2016 to 2020, the model provides a data-driven approach to player valuation, which is highly useful for sports analytics, scouting, and recruitment.

📊 Key Results
Best Model: XGBoost Regressor

Accuracy: 92.4% R² Score

Data Scope: 5 years of historical player records (2016–2020)

🛠️ Technical Workflow
1. Data Processing
Aggregation: Merged multiple datasets representing player statistics over five seasons.

Cleaning: Handled missing values and outliers to ensure data quality.

Feature Engineering: Selected 21 critical features, including Age, Potential, Overall Rating, and specific skill sets (Passing, Shooting, Dribbling, etc.).

Preprocessing: * Scaled numerical features using StandardScaler.

Encoded categorical variables (e.g., body_type) using OneHotEncoder.

2. Modeling & Evaluation
Evaluated multiple regression algorithms:

Linear Regression

Random Forest

CatBoost

XGBoost (Top Performer)

Achieved high predictive power with an R² score of 0.924, indicating the model captures over 92% of the variance in player market values.

🚀 Installation & Usage
Prerequisites
Python 3.x

Libraries: pandas, numpy, scikit-learn, xgboost, catboost, matplotlib

Running the Project
Clone the repository:

Bash
git clone https://github.com/[Your-Username]/player-market-value-prediction.git
Install dependencies:

Bash
pip install -r requirements.txt
Execute the notebook: Open player_value_prediction.ipynb in Jupyter Notebook or Google Colab to see the analysis and model training steps.

📂 Repository Structure
data/: (Optional) Directory for CSV files (if not ignored).

player_value_prediction.ipynb: Main Jupyter Notebook with code and visualizations.

.gitignore: Configured to exclude large datasets and temporary files.

Author: Ritesh Soni

Education: IIT BHU

Field: Data Analytics / Machine Learning
