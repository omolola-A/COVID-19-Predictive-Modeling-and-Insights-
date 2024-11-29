# Introduction

![](https://github.com/omolola-A/COVID-19-Predictive-Modeling-and-Insights-/blob/main/Microbes-2-800x450.png)

## Background
The SARS-CoV-2 virus that triggered the COVID-19 pandemic has caused major disruptions to people's lives worldwide, posing problems for social structures, the economy, and public health. Data analysis and forecasting models are essential to comprehend pandemic trends and inform policy decisions. To predict future instances, this paper uses forecasting techniques, emphasizing the ARIMA model, to analyze trends in COVID-19 data and provide important insights.
Problem Statement
The absence of precise prediction tools has frequently led to ineffective public health tactics, insufficient resource allocation, and delayed outbreak responses, even with the availability of large datasets. Preparation for upcoming pandemics could be greatly enhanced by creating a predictive system based on COVID-19 trends.
Aim and Objectives
The primary aim of this project is to develop a predictive modeling system for COVID-19 to support HealthGuard Analytics in addressing these challenges. The objectives include:
Cleaning and preprocessing COVID-19 datasets.
Conducting Exploratory Data Analysis (EDA) to uncover critical trends.
Developing and validating a time-series forecasting model.
Integrating additional datasets to enhance insights.
Building an interactive Power BI dashboard for easy visualization and communication of findings.


# Methodology

## Data Collection
The dataset was sourced from the COVID-19 Open Research Dataset (CORD-19) on Kaggle.

## Data Preprocessing
Missing values were input, and duplicate records were removed.
Features like daily growth rates and mortality ratios were engineered for deeper insights.
Date columns were standardized, and datasets were normalized for machine learning.

## Exploratory Data Analysis (EDA)

### Trends Analysis: Visualized confirmed, death, and recovery cases over time.
Top 10 Affected Countries: Created a histogram highlighting case disparities among countries.

### Correlation Analysis: Identified significant relationships between variables, such as confirmed cases and mortality rates.

## Model Development and Validation
An ARIMA model was developed for time-series forecasting.

## Accuracy Metrics:
Mean Absolute Error (MAE): 0.0971
Root Mean Squared Error (RMSE): 0.1306
Mean Absolute Percentage Error (MAPE): 2.84%
R-squared (R²): 91.42%
These metrics indicate strong model performance, enabling reliable forecasting of COVID-19 trends.


## Power BI Dashboard
Further analysis was conducted by integrating population data. Relationships were established between datasets to derive richer insights. Key metrics include:
Total Population: 6 billion
Total Cases: 829 million
Total Deaths: 43 million
Deaths per Population: 0.01
Recovery to Death Ratio: 8.95


# Results and Findings
## Key Observations
### Time-Series Trends:
From March to July, confirmed cases rose steadily, accompanied by increasing recoveries.
Recovery rates overtook death rates in July.

![](https://github.com/omolola-A/COVID-19-Predictive-Modeling-and-Insights-/blob/main/Monthly%20Trends.png)

Figure 1: Global COVID-19 Case Trends

### Country-Level Analysis:
The US had the highest confirmed cases, with more deaths than recoveries.
Brazil showed a high recovery rate, while the UK reported no recoveries.
Europe and Asia dominated the case count, while Australia and Africa recorded fewer cases.

![](https://github.com/omolola-A/COVID-19-Predictive-Modeling-and-Insights-/blob/main/Top%2010%20Countries%20with%20cases%20of%20COVID-19.png)

Figure 2: Top 10 Countries by COVID-19 Cases

### Monthly Analysis:
July witnessed the highest confirmed and recovered cases, with minimal deaths due to a low deaths-to-recovery ratio.
June recorded fewer cases but a slightly higher deaths-to-recovery ratio.

## Power BI Insights:
Europe had the highest number of confirmed cases, followed by Asia and South America.
Australia and Africa recorded the lowest confirmed cases.
Deaths per population and recovery-to-death ratios provided actionable benchmarks for public health strategies.
![](https://github.com/omolola-A/COVID-19-Predictive-Modeling-and-Insights-/blob/main/Dashboard.png)

Figure 3: Dashboard Summary

## Forecasting Model:
The ARIMA model was built and evaluated using Python. The model parameters (p, d, q) were optimized using the auto_arima function, ensuring the best fit for the dataset.

![](https://github.com/omolola-A/COVID-19-Predictive-Modeling-and-Insights-/blob/main/Forecast.png)
Figure 4: ARIMA Forecast Results


# Conclusion and Recommendations

## Conclusion
This project successfully developed a predictive system to forecast COVID-19 trends and analyze public health metrics. Integrating population data and the Power BI dashboard enriched the analysis, providing comprehensive insights into COVID-19’s global impact.

## Recommendations
Public health policies should focus on improving recovery rates and reducing deaths-to-recovery ratios.
Resource allocation strategies must prioritize regions with high death rates relative to confirmed cases.
Future pandemic preparedness should include predictive systems leveraging integrated datasets for real-time insights.
Expand data collection to include vaccine distribution and efficacy metrics for enhanced modeling.

## To access this report in pdf format, which includes a Literature Review: Go to [COVID-19 Predictive Modeling and Insights for Public Health](https://drive.google.com/file/d/1K9r4wHWgmIQR5rfq5ohBUAuyyNbJZS8d/view?usp=drive_link)

## To also access this report in presentation format: Go to [Presentation Slides](https://drive.google.com/file/d/1Kc037PhGM8OFJm2Q0l_q5d7YiV3RhvWk/view?usp=sharing)
