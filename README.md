# Fetal Movements and Stillbirth Trends

The primary objective of this analysis is to explore trends related to fetal deaths and live births. We aim to understand time-based patterns, correlations with other variables, and employ regression modeling to predict fetal death rates.

## Time Series Analysis
Methodology: We plotted the counts of fetal deaths and live births over the years.

Findings: Both fetal deaths and live births showed some fluctuation over time but remained relatively stable.

## Correlation Analysis
Methodology: We calculated the correlation coefficients between fetal deaths and other variables in the dataset.

Findings:
Total Live Births: Highly positively correlated (0.98)
Percent of First Live Births: Positively correlated (0.37)
Percent of Cesarean Sections: Positively correlated (0.37)
Mean Age of Mothers: Positively correlated (0.22)
Percent of Poverty: Positively correlated (0.21)
Percent of Mothers who Smoke: Negatively correlated (-0.66)

## Regression Analysis
Methodology: A linear regression model was used to predict the rates of fetal deaths based on six features that showed significant correlation.

Findings:
Mean Squared Error (MSE): 284.84
R-squared: 0.955
The model explains approximately 95.5% of the variance in the test data, indicating a good fit.

## Seasonal Trends Analysis
Methodology: We aggregated the data by 3-month periods to look for seasonal trends in fetal deaths and live births.

Findings: No strong seasonal trends were observed for either fetal deaths or live births.

## Conclusion:
The trend for both fetal deaths and live births is relatively stable over time.
Several variables are correlated with fetal deaths, including the total number of live births, maternal age, and poverty level.
The regression model performed well in predicting fetal death rates based on other variables.
No strong seasonal trends were identified.
