# Algerian Forest Fires Prediction

A Flask web application that predicts the Fire Weather Index (FWI) using a Ridge Regression model trained on the Algerian Forest Fires dataset.

## Project structure

- `application.py` - Flask app
- `models/` - saved Ridge model and scaler (`ridge.pkl`, `scaler.pkl`)
- `notebooks/` - EDA, feature engineering and model training
- `templates/` - HTML pages (`index.html`, `home.html`)
- `requirements.txt` - Python dependencies

## How to run

pip install -r requirements.txt
python application.py

Then open the local address shown in the terminal in your browser.