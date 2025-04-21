# REITs Model

A Streamlit app for predicting Iris flower varieties using a logistic regression model.

## Prerequisites

* Python 3.8+
* pip
* virtualenv

## Setup Instructions

### 1. Clone the repository
```bash
git clone <your-repo-url>
cd reits-model
```

### 2. Create and activate a virtual environment
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the app
```bash
streamlit run app.py
```

### 5. Project Structure

* `app.py` - Main Streamlit application
* `pages/main_page.py` - Main prediction page
* `logreg_model.pkl` - Pre-trained model file
* `requirements.txt` - Python dependencies
* `.venv/` - Virtual environment (not committed to version control)

### Troubleshooting

Ensure your virtual environment is activated before installing dependencies or running the app.
If you encounter missing package errors, re-run the install command.