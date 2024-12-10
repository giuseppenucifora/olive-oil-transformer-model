# Olive Oil Transformer Model

This repository contains transformer-based models for various predictions, including olive oil production forecasting. Here's a guide to the key components of the project:

## Project Structure

### Model Notebooks Location
The model notebooks are located in the `/models` directory, organized by different prediction tasks:

- **Olive Oil Model**: `/models/olive_oli/olive_oil-v2.ipynb`
    - Contains the implementation of the transformer model for olive oil production forecasting
    - Includes model training, evaluation, and visualization components

- **Solar Energy Model**: `/models/solarenergy/solarenergy_model_v1.ipynb`
    - Transformer model for solar energy prediction

- **Solar Radiation Model**: `/models/solarradiation/solarradiation_model.ipynb`
    - Implementation for solar radiation forecasting

- **UV Index Model**: `/models/uv_index/uv_index_model.ipynb`
    - Model for UV index prediction

### Synthetic Data Generation
The script for generating synthetic training data is located at: ```/olive_oil_train_dataset/create_train_dataset.py```

This script is responsible for creating synthetic data used in training the olive oil production model.

### Utility Functions
Common utility functions and helper methods are stored in: ```/utils/helpers.py```

## Model Artifacts
Each model directory contains its associated artifacts, including:
- Trained model weights
- Scalers for data normalization
- Training logs
- Model architecture visualizations
- Performance analysis plots

For example, the olive oil model directory contains:
- Model weights in the `weights` subdirectory
- Scalers for static and temporal features
- Training logs in the `logs` subdirectory
- Model architecture and performance visualization plots

## Getting Started
To work with the models:
1. Start with the respective notebook in the `/models` directory
2. For olive oil prediction, first generate synthetic data using the script in `/olive_oil_train_dataset`
3. Utilize the utility functions from `/utils/helpers.py` as needed