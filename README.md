# Singapore Resale Flat Price Prediction

## Introduction

The Singapore Resale Flat Price Prediction project aims to develop a machine learning model to predict resale prices of Housing and Development Board (HDB) flats in Singapore. By analyzing historical transaction data and leveraging machine learning techniques, the project seeks to provide accurate price estimates for potential buyers and sellers, as well as insights into factors influencing property prices.
Problem Statement:
The objective of this project is to develop a machine learning model and deploy it as a user-friendly web application that predicts the resale prices of flats in Singapore. This predictive model will be based on historical data of resale flat transactions, and it aims to assist both potential buyers and sellers in estimating the resale value of a flat.

## Project Structure

- `data/`: Directory containing the dataset.
- `notebooks/`: Jupyter notebooks used for data exploration, feature engineering, model development, and evaluation.
- `src/`: Source code for data preprocessing, feature engineering, model training, and prediction.
- `models/`: Trained machine learning models.
- `results/`: Directory for storing evaluation results, predictions, and visualizations.
- `README.md`: This file.
- `requirements.txt`: List of dependencies needed to run the project.

## Data

The dataset contains historical transaction records of resale HDB flats in Singapore, including:

- Flat type and model
- Floor area (in square meters)
- Lease commencement date and remaining lease tenure
- Storey range and block number
- Town and flat type (e.g., 3-room, 4-room)
- Resale price
- Proximity to amenities (e.g., schools, parks, MRT stations)

## Setup

### Prerequisites

Ensure you have the following installed:

- Python 3.8+
- Jupyter Notebook
- Git

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/singapore-resale-flat-price-prediction.git
    cd singapore-resale-flat-price-prediction
    ```

2. Create a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

### Data Preprocessing

Run scripts to clean and preprocess the data for modeling:
```bash
python src/preprocess_data.py
```

### Model Training

Train machine learning models using preprocessed data:
```bash
python src/train_model.py
```

### Prediction

Make predictions using the trained models:
```bash
python src/predict.py
```
### Conclusion

The Singapore Resale Flat Price Prediction project successfully developed a machine learning model to forecast resale prices of Housing and Development Board (HDB) flats in Singapore. By leveraging historical transaction data and applying advanced machine learning techniques, the project aimed to provide accurate price predictions and insights into factors influencing property values.
