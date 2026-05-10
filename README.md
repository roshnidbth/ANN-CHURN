# ANN-CHURN




This project predicts whether a bank customer is likely to churn using an Artificial Neural Network model.

## Live Deployment

[View the Deployed App](https://ann-churn-ros.streamlit.app/)

## Project Description

The application takes customer details such as credit score, geography, gender, age, balance, tenure, number of products, credit card status, active membership status, and estimated salary.

The trained ANN model uses these inputs to predict the churn probability and displays whether the customer is likely to churn or not.

## Technologies Used

- Python
- TensorFlow / Keras
- Streamlit
- Pandas
- NumPy
- Scikit-learn

## Files Included

- `app.py` - Streamlit web application
- `model.keras` - Trained ANN model
- `encode_hot.pkl` - One-hot encoder for Geography
- `encode_label.pkl` - Label encoder for Gender
- `scaled.pkl` - Standard scaler
- `requirements.txt` - Required dependencies
- `Churn_Modelling.csv` - Dataset

## How to Run Locally
Install the required libraries:
pip install -r requirements.txt

Run the Streamlit app:
streamlit run app.py

## Output
The app displays the churn probability and predicts whether the customer is likely to churn or not.
