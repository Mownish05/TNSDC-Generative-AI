# House Price Prediction with Deep Learning

This repository contains code for predicting house prices using a deep learning model implemented with TensorFlow and Keras.

## Overview

The code generates a synthetic dataset for house price prediction, trains a deep learning model on this dataset, evaluates the model's performance, and visualizes the dataset and model results.

## Dependencies

- Python 3.x
- pandas
- numpy
- scikit-learn
- TensorFlow
- seaborn
- matplotlib

Install the dependencies using pip:

```bash
pip install pandas numpy scikit-learn tensorflow seaborn matplotlib
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/your_username/house-price-prediction.git
cd house-price-prediction
```

2. Generate the dataset and save it as an Excel file:

```bash
python generate_dataset.py
```

3. Train the deep learning model and visualize the results:

```bash
python train_model.py
```

## Files

- `generate_dataset.py`: Generates a synthetic dataset for house price prediction and saves it as an Excel file.
- `train_model.py`: Loads the dataset, trains a deep learning model, evaluates the model's performance, and visualizes the dataset and model results.
- `generated_dataset.xlsx`: The generated dataset saved as an Excel file.
- `README.md`: This README file.
