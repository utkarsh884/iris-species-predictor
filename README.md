# Iris Species Predictor

Iris Species Predictor is a Python-based machine learning application demonstrating the complete workflow of training, saving, and deploying a model to classify iris flower species. The project uses scikit-learn for modeling and Streamlit for a simple web interface.

## Overview

This repository provides code and examples for preparing, saving, and deploying a machine learning model for iris species classification. It is ideal for learning how to operationalize ML workflows and deploy models with a user-friendly web interface.

## Features

- Model training and evaluation using Python and scikit-learn
- Model serialization (using pickle)
- Deployment via a Streamlit web app
- Easy-to-use sliders for prediction inputs

## Tools Used

- **Python**: Core programming language for modeling and deployment
- **scikit-learn**: Model building and evaluation
- **Streamlit**: Web UI for predictions
- **pickle**: Model serialization

## Getting Started

### Prerequisites

- Python 3.7+
- pip

### Installation

Clone the repository:
```bash
git clone https://github.com/utkarsh884/iris-species-predictor.git
cd iris-species-predictor
```

Install dependencies:
```bash
pip install -r requirements.txt
```

### Usage

1. Train and save the machine learning model using the provided scripts.
2. Run the Streamlit app to make predictions:
   ```bash
   streamlit run deploy1.py
   ```
3. Use the web interface to input flower measurements and get species predictions.

## Project Structure

- `model/` – Scripts for training and saving ML models
- `deploy1.py` – Main deployment and prediction app (Streamlit)
- `requirements.txt` – Python dependencies

## License

This project does not have an explicit license yet.

## Contact

For questions or suggestions, please open an issue or contact [utkarsh884](https://github.com/utkarsh884).
