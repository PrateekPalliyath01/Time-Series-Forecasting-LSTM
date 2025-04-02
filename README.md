# Time-Series-Forecasting-LSTM
## Overview
This project implements a Long Short-Term Memory (LSTM) model to predict Microsoft stock prices based on historical data. It includes data preprocessing, visualization, model training, and prediction.

## Dataset
- The dataset used is `MicrosoftStock.csv`, which contains historical stock price data including date, open, close, and volume.
- The data is preprocessed, including date conversion, filtering, and feature scaling.

## Technologies Used
- Python
- TensorFlow/Keras
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## Project Structure
```
├── MicrosoftStock.csv  # Dataset
├── main.py             # Code for data processing, model training, and prediction
├── README.md           # Project documentation
```

## Installation
### Prerequisites
Ensure you have Python installed along with the required libraries:
```bash
pip install tensorflow pandas numpy scikit-learn matplotlib seaborn
```

## Model Architecture
The LSTM model consists of:
- Two LSTM layers (64 units each)
- One Dense layer (128 neurons, ReLU activation)
- Dropout layer (0.5)
- Final Dense output layer

## Visualization
The project includes various plots such as:
- Stock Open & Close price trends
- Stock Volume analysis
- Feature correlation heatmap
- Actual vs. Predicted stock prices

## Results
The trained model makes predictions on unseen data and plots them against actual stock prices for comparison.

## Future Enhancements
- Hyperparameter tuning for improved accuracy
- Experimenting with different neural network architectures
- Incorporating additional stock-related features



