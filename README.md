# Farm-Forecast
🌾 Farm Forecast
A machine learning-based crop recommendation and yield prediction system that helps farmers make data-driven decisions about crop selection and farming practices.

📋 Overview
Farm Forecast is an intelligent agricultural decision support system that analyzes various environmental and soil parameters to provide crop recommendations and yield predictions. By leveraging machine learning algorithms, it helps farmers optimize their crop selection based on local conditions.

✨ Features
Crop Recommendation: Suggests the most suitable crops based on soil and environmental conditions
Yield Prediction: Estimates potential crop yields to help with planning
Data-Driven Insights: Uses historical data and machine learning models for accurate predictions
User-Friendly Interface: Easy-to-use interface for farmers and agricultural professionals
Multiple Parameter Analysis: Considers NPK values, pH, temperature, humidity, and rainfall
🛠️ Technologies Used
Python: Core programming language
Machine Learning Libraries:
scikit-learn for model building
pandas for data manipulation
numpy for numerical computations
Web Framework: Flask/Streamlit (for web interface)
Data Visualization: matplotlib, seaborn
📦 Installation
Prerequisites
Python 3.8 or higher
pip package manager
Setup
Clone the repository:
bash
git clone https://github.com/Aishwarya-Arya05/Farm-Forecast.git
cd Farm-Forecast
Create a virtual environment (recommended):
bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install required dependencies:
bash
pip install -r requirements.txt
🚀 Usage
Start the application:
bash
python app.py
Open your web browser and navigate to:
http://localhost:5000
Enter the required parameters:
Nitrogen (N) content in soil
Phosphorus (P) content in soil
Potassium (K) content in soil
pH value of soil
Temperature (°C)
Humidity (%)
Rainfall (mm)
Click "Predict" to get crop recommendations and yield estimates
📊 Dataset
The model is trained on agricultural datasets containing:

Soil nutrient information (NPK values)
Environmental conditions (temperature, humidity, rainfall)
Historical crop yield data
Crop suitability information
🤖 Models
The system uses multiple machine learning algorithms:

Random Forest Classifier
Decision Trees
Support
