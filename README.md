# Market Price Prediction Via LSTM Recurrent Neural Network

## Overview  
This project implements Long Short-Term Memory (LSTM) recurrent neural networks (RNN) to predict Apple Inc. (AAPL) stock closing prices based on historical market data from 1980-2021. The model captures temporal dependencies in stock prices, allowing for more accurate financial forecasting. By leveraging deep learning, this project provides a robust approach to time-series analysis, achieving a Root Mean Squared Error (RMSE) of 4.68. The results offer valuable predictive insights for investors and analysts by visualizing model accuracy over real stock trends.

## Features  
- **Data Preprocessing**: Normalizing and sequencing data for training and testing. Handles missing values, scales data, and sequences it for time-series modeling.  
- **LSTM Architecture**: Implements two LSTM layers with dense layers for optimized forecasting. 
- **Performance Evaluation**: Uses RMSE, MAE, and MSE to assess prediction accuracy. 
- **Prediction Visualization**: Compares predicted vs. actual stock prices for detailed trend analysis.
- **Forecasting Analysis**: Provides insights into 2021 and 2022 stock movement, helping evaluate model reliability.

## Files  
1. `AAPL.csv`  
   - Historical stock data for Apple Inc.  
2. `Market Price Prediction Via LSTM Recurrent Neural Network.ipynb`  
   - Jupyter Notebook with code for data preparation, model training, evaluation, and visualization.  
3. `Recurrent Neural Networks Presentation Info.pptx`  
   - Presentation on RNN architecture and use.  

## Requirements  
- Python 3.8 or higher  
- Required libraries:  
  - `pandas`  
  - `numpy`  
  - `matplotlib`  
  - `scikit-learn`  
  - `keras`  

Install dependencies using:  
pip install pandas numpy matplotlib scikit-learn keras  
  
## Usage
1. Clone the repository and navigate to the project directory:
git clone https://github.com/jovanthompsonmds/Market-Price-Prediction-Via-LSTM-Recurrent-Neural-Network.git

2. Run the Jupyter Notebook:
- Load and preprocess the data.
- Train the LSTM model.
- Evaluate performance metrics.
- Visualize results for 2021 and 2022 predictions.

3. Analyze the plots for 2021 and 2022 predictions to assess model accuracy.

## Insights
- The LSTM model successfully predicts stock prices, demonstrating low error rates (RMSE = 4.68).
- Predicted values closely align with actual stock price trends, proving deep learning’s viability in finance.
- Graphical comparisons provide actionable insights into market fluctuations.
- The project highlights key challenges in financial forecasting, including market volatility and data sensitivity.

## Contributing
Contributions are welcome! If you'd like to improve the project, add features, or provide feedback, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Author
Developed by Jovan Thompson as part of a data science portfolio project.
