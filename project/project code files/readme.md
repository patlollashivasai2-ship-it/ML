# Esports Match Outcome Prediction Using Deep Learning

A Flask web application that predicts esports match outcomes using a PyTorch neural network trained on the supplied CSV dataset.

## Features
- Dashboard with dataset statistics
- Deep-learning Win/Loss prediction
- Prediction confidence and probabilities
- Dataset preview
- REST-style `/api/stats` endpoint
- Model training script

## Run on Windows
1. Install Python 3.10+.
2. Open Command Prompt in this folder.
3. Run:
   `python -m pip install -r requirements.txt`
4. Train the model:
   `python train_model.py`
5. Start the website:
   `python app.py`
6. Open `http://127.0.0.1:5000`

Or double-click `run.bat`.

## Project structure
- `app.py` - Flask web server and prediction logic
- `train_model.py` - preprocessing and PyTorch training
- `data/` - CSV dataset
- `models/` - generated model artifacts
- `templates/` - HTML pages
- `static/` - CSS
