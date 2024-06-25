# Twitter Event Signatures

## Overview
This project investigates how real-world events are reflected in social media signals, particularly on Twitter. The focus is on understanding the patterns of interest and trends associated with various event types such as protests, natural disasters, and election cycles. Multidomain Datasets from platforms like Kaggle, the Internet Archive, and GDELT, the project analyzes events like protests, natural disasters, and elections. Over a Terabyte of Data was explored thorughout the project, utlising techniques such as seasonal decomposition and LOESS regression are employed to approximate and evaluate the trends, resulting in a framework for classifying each event with a distinct event archetype.

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

## Authors
- Natan Grayman and Liad Peretz 

## References
1. Saleem, H. M., Xu, Y., & Ruths, D. (2014). Effects of disaster characteristics on Twitter event signature. ScienceDirect.
2. Jaewon, J. L. Yang (2011). Patterns of temporal variation in online media. ACM Digital Library.
3. GDELT Project. [Link](https://www.gdeltproject.org/about.html)
4. Internet Archive. [Link](https://archive.org/about/)
5. Kaggle Datasets. [Link](https://www.kaggle.com/datasets)
