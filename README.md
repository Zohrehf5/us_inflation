  

# Forecasting GDP and inflation affects 

Gross Domestic Product (GDP) and Consumer Price Index (CPI) inflation are critical indicators of the economic health and stability of the United States. GDP measures the total value of goods and services produced, representing overall economic growth. In contrast, the CPI inflation rate reflects changes in consumer prices over time, indicating shifts in cost of living and purchasing power.
Historically, the U.S. economy has experienced robust growth, with occasional recessions—such as the 2008 financial crisis and the COVID-19 pandemic—that temporarily disrupted GDP growth. Nonetheless, recoveries followed these downturns, showcasing the economy’s resilience. Conversely, inflation has fluctuated, with high inflation in the 1970s and 1980s due to oil crises, followed by more stable rates in subsequent decades. Recently, the country has seen a resurgence of inflation due to supply chain disruptions, heightened demand, and pandemic-related factors, leading to inflation levels unseen in decades.
Given the impact of inflation on purchasing power and production costs, accurately forecasting inflation is essential for policymaking and business planning. Understanding the interplay between GDP and inflation can help maintain economic stability and prosperity.

## Repository structure

├── data<br/>
│   ├── Inflation.xlsx: https://www.worldbank.org/en/research/brief/inflation-database<br/>
│   ├── GDP.csv: https://fred.stlouisfed.org/series/GDP<br/>
│   <br/>
├── inflation1.ipynb- This file shows the inflation trend in 5 major countries: United States, Germany, Russia, India and China<br/> 
├── inflation2.ipynb- This file shows the GDP trend in United States, forecasts the GDP Trend for next 10 years. <br/>
│       Different models are used for training and evaluated. An ARIMA model was used to forecast GDP trends.<br/>
├── image<br/>
│   ├── pic1.png<br/>
│   └── pic2.png<br/>
│   ├── pic3.png<br/>
│   └── pic4.png<br/>
│   ├── pic5.png<br/>
│   └── pic6.png<br/>
│   ├── pic7.png<br/>
│   └── pic8.png<br/>
│   ├── pic9.png<br/>
│   └── pic10.png<br/>
│   ├── pic11.png<br/>
│   └── pic12.png<br/>
│   ├── pic13.png<br/>
│   └── pic14.png<br/>
├── README.md<br/>
├── Capstone Inflation.docx- Detail report for this project.<br/>
└── .gitignore<br/>

## Results and evaluation
•	The analysis reveals that the long-term upward trend in GDP is the most dominant feature, indicating sustained economic growth over time. Despite periods of volatility, such as the 2008 financial crisis and the 2020 pandemic, the GDP trend demonstrates resilience, consistently returning to an upward trajectory.
•	The seasonal component is relatively stable, suggesting that GDP experiences regular and predictable fluctuations throughout the year. These fluctuations, while present, do not significantly alter the overall trend, indicating that seasonality is a smaller but consistent factor in GDP variations.
Future work
1.	Enhance Model Accuracy with Additional Data:
o	To improve the robustness and accuracy of the GDP forecasting model, it’s crucial to gather more comprehensive datasets. Including exogenous variables such as interest rates, unemployment rates, inflation rates, trade balances, and other macroeconomic indicators could provide a more holistic view of the factors influencing GDP changes, especially during periods of economic uncertainty.
2.	Compare Forecasts with Alternative Models:
o	To ensure the reliability of the GDP forecasts, it's essential to compare the results with other forecasting models .This comparison can help validate the accuracy and robustness of the SARIMA model's predictions and identify if any alternative methods perform better in capturing the underlying patterns.
3.	Optimize Model with Hyperparameter Tuning:
o	To achieve better predictive performance, fine-tune the model’s hyperparameters (e.g., ARIMA order (p, d, q), seasonal parameters) using grid search or other optimization techniques. Proper hyperparameter tuning can significantly enhance the model’s ability to capture the complexities of the GDP time series data, leading to more accurate forecasts.
4.	Transition from Classification to Regression Analysis:
o	The current analysis might involve a binary classification task with GDP Trend as a Boolean variable (growth/no growth). However, for a more nuanced understanding and prediction, switching the target variable from a Boolean (GDP Trend) to a continuous regression target (actual GDP values) can allow for more detailed and precise forecasts. This change will enable the model to predict the exact GDP value rather than just identifying whether it’s increasing or decreasing, providing more actionable insights for policymakers and analysts.

