# Iris Species Predictor

A Python app that trains and deploys a machine learning model to classify iris flower species. The project uses scikit-learn for modeling and Streamlit for a simple web interface.

## Contents

- `deploy1.py` — Main deployment script; loads a trained model and serves a user-friendly prediction interface using Streamlit.
- `classifier.pkl` — Pickled (serialized) machine learning model trained on iris dataset.
- `iris_data.csv` — Dataset used for training the iris species classifier.
- `README.md` — Project documentation.

## Features

- Trains a classifier to predict iris species from flower measurements.
- Saves the trained model for fast, repeated predictions.
- Provides a web-based UI for users to input measurements and get instant predictions.

## Getting Started

### Prerequisites

- Python 3.7 or newer
- pip

### Installation

Clone the repository and install dependencies:
```bash
git clone https://github.com/utkarsh884/iris-species-predictor.git
cd iris-species-predictor
pip install -r requirements.txt
```

### Usage

1. If `classifier.pkl` is not present, train and export the model using your own script or notebook.
2. Launch the web app:
    ```bash
    streamlit run deploy1.py
    ```
3. Enter flower measurements in the web interface to get species predictions.

## License

This project does not have an explicit license yet.

## Contact

For questions or suggestions, please open an issue or contact [utkarsh884](https://github.com/utkarsh884).
