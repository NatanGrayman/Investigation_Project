# Twitter Event Signatures


## Overview
This project investigates how real-world events are reflected in social media signals, particularly on Twitter. By analyzing datasets from Kaggle, the Internet Archive, and GDELT, the study focuses on protests, natural disasters, and election cycles. Techniques such as seasonal decomposition and LOESS regression were employed to identify trends and create distinct event archetypes.

The project achieved a distinction (80%) under the auspices of [Prof. Martin Bekker](https://www.linkedin.com/in/martinbekker/)) and was moderated by ECSA.


## Key Findings
- **Event Types Analyzed**: Protests, Natural Disasters, Election Cycles
- **Data Sources**: Kaggle, Internet Archive, GDELT, Google Trends
- **Methods Used**: Seasonal decomposition, LOESS regression
- **Results**: Creation of event archetypes for each event type, offering valuable insights into the relationship between event types and Twitter trends.

## Methodology
1. **Data Collection**: Utilizing open-source data from Kaggle, the Internet Archive, GDELT and Google Trends.
2. **Data Preprocessing**: Cleaning and transforming data for analysis.
3. **Trend Analysis**: Employing seasonal decomposition and LOESS regression to identify trends.
4. **Geolocation Analysis**: Mapping tweet activities to geographical locations.
5. **Trend Validation**: Comparing Twitter trends with news media responses and Google Trends data.

## Tools and Technologies
- **Programming Languages**: Python
- **Data Processing**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **APIs**: Twitter API, Google Trends API, Nominatim API

## Conclusion
The investigation provides a comprehensive framework for understanding how real-world events are mirrored in social media activities. The results highlight the potential for more precise event classification and trend analysis in future research.
