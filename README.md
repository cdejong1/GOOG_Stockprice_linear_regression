# GOOGL Stock Price Model Project

## Overview
The "GOOGL Stock Price Model Project" uses a linear regression approach to predict Alphabet Inc.'s stock price dynamics, incorporating various financial data points from 2004 to 2022. The model aims to provide a streamlined and efficient method for financial forecasting, enhancing consistency and reducing the time required for analysis.

## Data
The model includes the following variables:
- **Market Return Measure**: Utilizes the S&P 500 index as a benchmark.
- **Revenue and Operating Cash Flows**: Indicators of Alphabet Inc.'s performance.
- **Inflation Rate**: Included as a measure of economic context affecting company finance.
- **Unemployment Rate**: Reflects broader economic conditions.

## Model Equation
Chng_in_price = MktReturn + Revenue + OCF + EmployRate + InflationRate

# Installation and Running the Model

Ensure R and RStudio are installed on your machine, and install required packages using the following commands:

install.packages(c("tidyverse", "forecast", "lmtest", "sandwich"))

To run the model, open the GOOG_Model_Project.Rmd file in RStudio, follow the detailed steps in the GOOG_Model_Instruction_Manual.Rmd to execute the model, and view results.

## Usage

This model can be used to predict future price changes of GOOGL stocks by updating the input data with the latest financial figures from Alphabet Inc. Follow the instructions in the provided manual for detailed steps on how to use the model effectively.
Contributing

Contributions to this project are welcome. Please fork the repository, make your changes, and submit a pull request.

## Authors

    Christian B. DeJong

License

This project is licensed under the MIT License - see the LICENSE file for details.
References

    Corporate Finance Institute
    SEC filings for Alphabet Inc.
    U.S. Inflation Calculator
    U.S. Bureau of Labor Statistics
    MacroTrends

## Predictions

The model's predictions based on Q1 2023 financial reports estimate a significant change in GOOGL's stock price by the end of 2023.
Results

The regression model has an R-squared of 0.679, indicating it explains approximately 67.9% of the variance in price changes.
