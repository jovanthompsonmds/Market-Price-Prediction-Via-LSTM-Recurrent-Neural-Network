# Apple Stock Price Prediction Using LSTM  

## Overview  
This project leverages Long Short-Term Memory (LSTM) networks to predict Apple Inc. (AAPL) stock closing prices. Trained on historical data, the model achieved a Root Mean Squared Error (RMSE) of 4.68, demonstrating the effectiveness of deep learning in financial forecasting.  

## Features  
- **Data Preprocessing**: Normalizing and sequencing data for training and testing.  
- **LSTM Architecture**: Two LSTM layers followed by dense layers for regression tasks.  
- **Performance Evaluation**: Metrics like RMSE and visual comparisons of predicted vs. actual prices.  
- **Prediction Visualization**: Insights for 2021 and 2022 with detailed plots.  

## Files  
1. `AAPL.csv`  
   - Historical stock data for Apple Inc.  
2. `Stock_Price_Prediction.ipynb`  
   - Jupyter Notebook with code for data preparation, model training, evaluation, and visualization.  
3. `model_predictions.csv`  
   - Predicted stock prices for 2021 and 2022.  

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
git clone https://github.com/jovanthompsonmds/Market-Price-Prediction-Via-Recurrent-Neural-Network.git

2. Run the Jupyter Notebook:
- Load and preprocess the data.
- Train the LSTM model.
- Evaluate performance metrics and visualize results.

3. Analyze the plots for 2021 and 2022 predictions to assess model accuracy.

## Insights
The model effectively predicts stock prices, with an RMSE of 4.68. Predicted prices closely align with actual prices, highlighting the potential of LSTM in time-series forecasting. Visual comparisons provide actionable insights for investors and analysts.

## Contributing
Contributions are welcome! If you'd like to improve the project, add features, or provide feedback, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Author
Developed by Jovan Thompson as part of a data science portfolio project.
