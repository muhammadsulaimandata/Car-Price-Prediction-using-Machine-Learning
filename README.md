# Car Price Prediction using Machine Learning

This project predicts used-car selling prices from vehicle attributes. It includes cleaned training data, a serialized regression model, a preprocessing component, and a web interface for entering a car's details and receiving a prediction.

## Contents

- `main.ipynb` — exploratory analysis, preprocessing, model training, and evaluation
- `LinearRegressionModel.pkl` — serialized trained model
- `application.py` — web application entry point
- `templates/index.html` — prediction form and result page
- `static/CSS/style.css` — application styling
- `Data/` — raw and cleaned car datasets

## Running the application

1. Create and activate a Python environment.
2. Install the dependencies required by the application.
3. Start the application:

   ```bash
   python application.py
   ```

4. Open the local URL printed by the application and submit the vehicle details.

The model artifact and preprocessing assumptions must remain compatible with the input fields used by the form. Retrain and replace the model when the feature schema changes.

## Data workflow

The `Data/` directory contains the original scraped dataset and cleaned versions used for analysis. The notebook is the source of truth for data preparation and model experimentation.
