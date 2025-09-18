## Solar Power Prediction with Machine Learning ##

## Project Overview ##
This project implements a complete machine learning pipeline to predict solar power production based on various meteorological and environmental factors. The goal is to develop and evaluate several regression models to identify the most accurate one for forecasting solar energy output.

## Features ## 
Data Preprocessing: Handles missing values and prepares the dataset for analysis.

Exploratory Data Analysis (EDA): Uses visualizations (histograms, pairplots, and heatmaps) to understand data distributions and relationships between variables.

Feature Engineering: Creates a new, more informative feature (Effective_Solar_Hours) to enhance model performance.

Model Comparison: Trains and evaluates five different machine learning models to determine the best fit for the prediction task.

Performance Evaluation: Utilizes key metrics like Mean Squared Error (MSE) and R-squared (R2) to assess model accuracy.

🛠️## Tools and Technologies ##
The project is built using Python and several popular data science libraries:

Python: The core programming language.

pandas: For data manipulation and analysis.

numpy: For numerical operations.

scikit-learn: The primary machine learning framework for building, training, and evaluating models.

matplotlib & seaborn: For creating visualizations to aid in data exploration.

## Methodology ##
The machine learning pipeline is executed in the following steps, which are detailed in the solar_prediction.ipynb notebook:

Data Loading: The project starts by loading a CSV dataset containing solar power and weather data.

Data Preprocessing: Columns like Date and Time are dropped, and any missing values are handled to ensure a clean dataset.

Exploratory Data Analysis: The data is visualized to identify patterns, distributions, and correlations among features.

Feature Engineering: A new feature is engineered from existing columns to provide more predictive power to the models.

Model Training: The data is split into training and testing sets, and five different regression models are trained.

Model Evaluation: Each model's performance is measured using MSE and R2 scores on the test data.

Result Analysis: The results are compared, and the best-performing model is identified.

## Getting Started ##
To run this project, follow these steps:

Clone the repository:

git clone [https://github.com/Siddhartha9182/Solar-Power-Prediction.git](https://github.com/Siddhartha9182/Solar-Power-Prediction.git)
cd Solar-Power-Prediction

Install dependencies:

pip install pandas numpy scikit-learn matplotlib seaborn

Place your dataset:
Ensure your CSV dataset file named solar_power_prediction.csv is in the project's root directory.

Run the Jupyter Notebook:
Start a Jupyter environment and open the solar_prediction.ipynb file to run the code cells sequentially.

## Results  ##
The model comparison demonstrated that the Random Forest Regressor was the best-performing model, achieving a high R-squared score and the lowest Mean Squared Error. This indicates its strong ability to accurately predict solar power production from the given features.

Best Model: Random Forest Regressor

R-squared (R2): 0.99

Mean Squared Error (MSE): 670.78

📸## Screenshots of outputs ##
-> <img width="1212" height="905" alt="Screenshot 2025-09-14 171942" src="https://github.com/user-attachments/assets/1f22d896-bfed-45ad-b2a8-e08a9ec9cc5b" />

-> <img width="1352" height="674" alt="Screenshot 2025-09-18 235814" src="https://github.com/user-attachments/assets/73b27ff0-d5fa-4bd8-8b0f-3c276fab8328" />

-> <img width="1536" height="754" alt="Figure_1" src="https://github.com/user-attachments/assets/7a42dac4-c2f6-4fc0-ae7e-6bafb78ae4d8" />

-> <img width="1536" height="754" alt="Figure_2" src="https://github.com/user-attachments/assets/a0294470-3d8a-47a0-987f-970f96488ba3" />

-> <img width="1536" height="825" alt="Figure_3" src="https://github.com/user-attachments/assets/3bbe1f3f-0737-4e07-a1f4-2b3260f48da5" />









License
This project is licensed under the MIT License.
