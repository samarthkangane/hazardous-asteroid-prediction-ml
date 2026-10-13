✨ Key Features

* Processes and analyzes 90,836 Near-Earth Object (NEO) records.
* Performs data cleaning and exploratory data analysis (EDA).
* Uses a Random Forest Classifier with balanced class weights.
* Evaluates model performance using classification metrics and ROC-AUC.
* Analyzes feature importance to understand which asteroid characteristics influence predictions.
* Saves the trained model and feature scaler using Joblib.
* Provides an interactive notebook interface for exploring asteroid classifications.

📈 Model Performance

Metric	Result
Accuracy	91.66%
ROC-AUC Score	0.9335

Note: These results reflect the evaluation described in the project report. Performance on new or unseen data may differ.

🧠 Feature Importance

The model’s feature-importance analysis identified the following leading features:

Feature	Importance
Absolute Magnitude	29.29%
Estimated Minimum Diameter	22.63%
Estimated Maximum Diameter	17.60%

These features accounted for approximately 69.5% of the model’s total feature importance in the reported analysis. Feature importance indicates the model’s reliance on features; it does not establish causation.

🛠️ Technologies Used

* Python — programming language
* Pandas & NumPy — data manipulation and numerical analysis
* Matplotlib & Seaborn — data visualization
* Scikit-learn — preprocessing, model training, and evaluation
* Joblib — saving the trained model and scaler
* Jupyter Notebook & ipywidgets — interactive exploration

🚀 Getting Started

Prerequisites

Install Python and Jupyter Notebook, then install the required libraries:

pip install pandas numpy matplotlib seaborn scikit-learn joblib ipywidgets jupyter

Run the Project

1. Clone or download this repository.
2. Open the project notebook in Jupyter Notebook.
3. Make sure the dataset is available at the path expected by the notebook.
4. Run the notebook cells in order.

Note: Update these instructions if your notebook requires additional dependencies or a specific dataset download step.

📄 Project Report

The detailed project report is available in the repository as Hazardous_Asteroid_Prediction_Report.pdf, if included in the public repository.

👨‍💻 Author

Samarth Narayan Kangane

Machine Learning Internship Project — Internship Studio

GitHub: https://github.com/samarthkangane

⸻

This project was developed for learning and educational purposes. Its predictions should not be treated as official asteroid-hazard assessments or a substitute for professional planetary-defense analysis.