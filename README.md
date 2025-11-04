#Surface Roughness Prediction using Machine Learning

📘 An industrial analytics project predicting surface roughness (Ra) using CNC machining parameters.

🎯 Objective

To develop a regression-based model that predicts the surface finish quality of machined parts based on process parameters like cutting speed, feed rate, and depth of cut.

⚙️ Workflow

Collected and generated realistic machining data (150 samples)

Conducted Exploratory Data Analysis (EDA)

Implemented Multiple Linear Regression (MLR) and compared results

Analyzed multicollinearity using Variance Inflation Factor (VIF)

Visualized relationships using Seaborn and Matplotlib

📈 Results

Identified feed rate as the most significant factor affecting Ra

Demonstrated strong correlation between model predictions and actual Ra values

Insights can be used for tool path optimization in manufacturing

🧰 Tech Stack

Python, pandas, numpy, matplotlib, seaborn, statsmodels, scikit-learn

📂 Dataset

Included in the repository: Industry_Surface_Roughness_Data.xlsx

🧠 Future Scope

Compare with non-linear models (Random Forest, SVR)

Deploy as a simple Streamlit dashboard for real-time prediction
