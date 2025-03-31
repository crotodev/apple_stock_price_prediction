# Apple Stock Price Prediction

This project predicts Apple Inc.'s (AAPL) stock price one day in advance using historical data and a **Linear Regression** model. It leverages the `yfinance` API for stock data collection and includes a Jupyter Notebook for visualization and model evaluation.

## Key Features
- Pulls real-time historical AAPL stock data using `yfinance`
- Applies a simple machine learning pipeline using **scikit-learn**
- Trains a linear regression model to forecast the next day's closing price
- Includes data visualization using **matplotlib**
- Executable as a Jupyter notebook (`prediction.ipynb`)

## Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/apple-stock-prediction.git
   cd apple-stock-prediction
   ```
   (Optional) Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
   Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
Open the Jupyter notebook:
```bash
jupyter notebook
```
Navigate to `prediction.ipynb` and run all cells.

The notebook will:
- Load Apple stock data
- Visualize trends
- Train a model
- Predict the next day's closing price
- Output model metrics (e.g., R² score)

## Requirements
Main dependencies:
- `yfinance` for fetching stock data
- `pandas` and `numpy` for data processing
- `matplotlib` for charting
- `scikit-learn` for model training and evaluation

For full details, see `requirements.txt`.

##  Project Structure
```bash
.
├── prediction.ipynb      # Jupyter notebook for training and prediction
├── requirements.txt      # Python package requirements
├── README.md             # Project overview and instructions
```

## Sample Output
After running the notebook, you’ll see:
- Stock price history plot
- Regression line comparison
- Predicted vs actual closing prices
- R² score of model performance

## Resources
- [Yahoo Finance API via `yfinance`](https://pypi.org/project/yfinance/)
- [Linear Regression (scikit-learn)](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html)