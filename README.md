# Project Title : ALGORITHMIC TRADING STRATEGIES

## Preface
The purpose of this project is to compare different trading strategies using multiple indicators, specifically the Moving Average Convergence Divergence (MACD) and Bollinger Bands (B-Bands). The project includes three strategies: two strategies using MACD and B-Bands on a standalone basis, and one strategy that combines both indicators. The generated returns from these strategies have been analyzed in detail.

## Indicators
The two indicators used in this project are:

1. MACD (Moving Average Convergence Divergence): It is calculated by subtracting the longer-term exponential moving average (EMA) from the shorter-term EMA. The MACD line is often accompanied by a signal line, which is a 9-day EMA of the MACD line. The MACD histogram represents the difference between the MACD line and the signal line.

2. Bollinger Bands: These consist of a middle band (usually a 20-day simple moving average) and an upper and lower band that are placed at two standard deviations away from the middle band. The upper band is calculated by adding two standard deviations to the middle band, while the lower band is calculated by subtracting two standard deviations.

## Strategies
The project includes the following three trading strategies:

1. Strategy 1 - MACD Standalone: This strategy utilizes only the MACD indicator to generate trading signals. The specific rules for entering and exiting trades are implemented in the code.

2. Strategy 2 - B-Bands Standalone: This strategy relies solely on Bollinger Bands to generate trading signals. The code includes the exact criteria for entering and exiting trades.

3. Strategy 3 - MACD and B-Bands Combination: This strategy combines both MACD and Bollinger Bands to generate trading signals. The code defines the criteria for entering and exiting trades based on the combined signals from both indicators.

## Results
The results of the analysis indicate that Strategy 3, which combines both MACD and Bollinger Bands, produces higher returns compared to the other two standalone strategies. This suggests that the combined signals from both indicators can provide more accurate trading signals.

Furthermore, it was observed that the strategies discussed in this project perform differently in Chinese markets compared to global markets. Chinese markets often do not follow global trends, which may impact the effectiveness of these strategies in such markets.

Additionally, the strategies demonstrated in this project tend to perform better over long time periods, preferably 2 years or more.

## Repository Structure
The repository includes the following files:

- `MACD_and_B_Bands.ipynb`: A Colab notebook containing all the code for implementing the trading strategies and performing the analysis. The data was retrieved from YahooFinance
- `README.md`: This readme file provides an overview of the project.

## Getting Started
To run the project and replicate the results, follow these steps:

1. Open the `MACD_and_B_Bands.ipynb` notebook in Colab or Jupyter.
2. Execute the cells in the notebook to retrieve required data from YahooFinanace then run the strategies and analyze the results.
4. Modify the strategies or indicators as needed for further experimentation.

## Conclusion
This project demonstrates the comparison of different trading strategies using MACD and Bollinger Bands indicators. By analyzing the generated returns and evaluating the performance of each strategy, valuable insights can be gained for making informed trading decisions.


