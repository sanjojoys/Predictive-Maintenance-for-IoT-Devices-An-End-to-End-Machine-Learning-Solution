# Predictive-Maintenance-for-IoT-Devices-An-End-to-End-Machine-Learning-Solution
The project aims to develop a predictive maintenance solution using machine learning for IoT-enabled industrial equipment. It will involve data preprocessing, feature engineering, model building, and deployment of the solution as a web app or API. The focus is on creating a real-world solution that integrates multiple ML and software engineering components.

Project Features

	1.	Data Source: Simulated IoT sensor data for machinery with features like temperature, vibration, and operational time.
	2.	Preprocessing: Handle missing values, noise, and imbalanced data.
	3.	Feature Engineering: Extract statistical and frequency-based features.
	4.	Machine Learning Models: Compare algorithms like Random Forest, XGBoost, and LSTMs for time-series analysis.
	5.	Model Optimization: Use hyperparameter tuning (e.g., Grid Search, Bayesian Optimization).
	6.	Explainability: Incorporate tools like SHAP or LIME to interpret predictions.
	7.	Deployment: Deploy the model as a Flask or FastAPI application hosted on a cloud platform (AWS, Azure, GCP).
	8.	Integration: Create a front-end interface for user interaction using React or Streamlit.
	9.	CI/CD Pipeline: Use GitHub Actions to automate testing and deployment.
	10.	Documentation: Provide clear README, installation instructions, and detailed explanations of the pipeline.

## Data Folder

The dataset used in this project is too large to store on GitHub. You can access the data folder via this Google Drive link:

[Access the Data Folder](https://drive.google.com/drive/u/1/folders/11r56m8K_hHvf268HRlbAln1ygg5OAqjW)

----------

Documentation

1. Project Overview

	•	Title: Predictive Maintenance IoT System
	•	Objective: Develop an IoT-based predictive maintenance system to forecast failures using sensor data and machine learning models.
	•	Status: Project halted due to restriction of AWS Free Tier limit.

2. Project Components

	1. Data Acquisition:
	• Collected environmental sensor data.
	• Data contains readings for temperature, humidity, CO, LPG, and other metrics.
	2. Preprocessing:
	• Handled missing values.
	• Normalized and scaled sensor readings.
	3. Exploratory Data Analysis (EDA):
	• Visualized trends in sensor data.
	• Analyzed feature correlations.
	4. Feature Engineering:
	• Extracted rolling averages, variances, FFTs, and other derived features.
	5. Model Development:
	• Models implemented: Logistic Regression, Random Forest, XGBoost, and LSTM.
	• XGBoost achieved the best accuracy: 1.00 AUC-ROC.
	6. API Development:
	• FastAPI-based API to handle predictions.
	• Endpoints developed for health check and prediction.
	7. Deployment:
	• Dockerized application prepared for deployment.
	   eployment halted due to AWS restrictions.

3. Challenges Faced

	•	AWS Free Tier limitations restricted further progress.
	•	Debugging FastAPI deployment issues with Docker.

4. How to Run the Project

	1.	Clone the repository:

git clone https://github.com/your-repository/predictive-maintenance-iot.git


	2.	Install dependencies:

pip install -r requirements.txt


	3.	Run the application locally:

uvicorn API_fastAPI:app --reload



5. Future Enhancements

	•	Deploy the application on a scalable cloud platform.
	•	Add real-time MQTT or Kafka integration.
	•	Integrate with a database for storing historical data and results.
