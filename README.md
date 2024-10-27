# Stock Market Prediction Using Machine Learning

## Project Goals
- To develop a machine learning model that predicts whether the S&P 500 index will go up or down the next day.
- To evaluate the model's performance through backtesting and refine it based on findings.

## Technologies Used
- **Python**: Main programming language for data analysis and modeling.
- **Jupyter Notebook**: Environment for developing and documenting the project.
- **yfinance**: Library for downloading historical stock price data.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib**: Data visualization.
- **Scikit-learn**: Machine learning library for model training and evaluation.

## Data Sources
The project utilizes historical daily data from Yahoo Finance, focusing on:
- Opening, high, low, closing prices, and trading volume of the S&P 500 index.

## Model Development
1. **Data Collection**: Downloaded historical data and cleaned it by removing unnecessary columns.
2. **Feature Engineering**: Created target variables to indicate future price movements and added rolling averages as additional predictors.
3. **Model Training**: Used a Random Forest Classifier to predict price direction, initially achieving 80% accuracy on training data.
4. **Evaluation**: Implemented precision score metrics to assess model performance.

## Backtesting
Conducted backtesting to simulate real-world trading conditions:
- The model's accuracy dropped to 53% during backtesting, revealing overfitting and the need for further refinement.
