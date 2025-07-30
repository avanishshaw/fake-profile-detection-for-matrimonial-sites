# Fake Account Detection

This project is a Flask-based web application that predicts whether an account is fake or real based on user input. It uses a pre-trained machine learning model stored in a pickle file (`avanish.pkl`).

## Features
- Web form for user input
- Predicts account authenticity (Fake/Real)
- Uses a machine learning model for prediction
- Supports various input fields such as caste, degree, employment, income, mother tongue, occupation, and religion

## Project Structure
```
app.py                # Main Flask application
model.py              # Model-related code (if any)
avanish.pkl           # Pre-trained ML model
requirements.txt      # Python dependencies
Procfile              # For deployment (e.g., Heroku)
static/               # Static files (CSS, images)
templates/            # HTML templates
*.csv, *.xlsx         # Data files
sentiment.ipynb       # Jupyter notebook (optional)
```

## Getting Started

### Prerequisites
- Python 3.x
- pip

### Installation
1. Clone the repository or download the source code.
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Ensure `avanish.pkl` is present in the project directory.

### Running the App
```
python app.py
```
The app will be available at `http://127.0.0.1:5000/`.

## Usage
- Open the web app in your browser.
- Fill in the required fields and submit the form.
- The app will display whether the account is predicted as Fake or Real.

## Deployment
- The project includes a `Procfile` for deployment on platforms like Heroku.

## License
This project is for educational purposes.
