# Analyzing Airlines Delays: Insights into Flight Performance

## a. Goals of the Project
The goal of this project is to analyze flight delay patterns to uncover trends, identify root causes, and provide actionable recommendations for mitigating delays. Key questions include:
- Which airlines and airports have the highest delay rates?
- What are the main causes of flight delays?

## b. Data Sources Used
The dataset used in this project was obtained from Kaggle (Airport Flight on Time Dataset: https://www.kaggle.com/datasets/eugeniyosetrov/airline-delays). It contains detailed flight data, including delay metrics, airport and airline information, and causes of delays.

## c. Data Overview
**Dataset Summary:**
- **Number of rows**: 3351.
- **Number of columns**: 21.
- **Key metrics**: carriers, airports, arrival flights, delayed flights, and delay reasons.

**Structure**:
**year**: Year data collected
**month**: Numeric representation of the month
**carrier**: Airline IATA code
**carrier_name**: Airline name
**airport**: Airport IATA code
**airport_name**: Name of airport
**arr_flights**: Number of flights arriving at airport
**arr_del15**: Number of flights more than 15 minutes late
**carrier_ct**: Number of flights delayed due to air carrier. (e.g. no crew)
**weather_ct**: Number of flights delayed due to weather
**nas_ct**: Number of flights delayed due to National Aviation System (e.g. heavy air traffic).
**security_ct**: Number of flights delayed due to a security breach.
**late_aircraft_ct**: Number of flights delayed as a result of another flight on the same aircraft delayed
**arr_cancelled**: Number of cancelled flights
**arr_diverted**: Number of flights that were diverted
**arr_delay**: Number of delayed flights
**carrier_delay**: Total time (minutes) of delay due to air carrier
**weather_delay**: Total time (minutes) of delay due to inclement weather
**nas_delay**: Total time (minutes) of delay due to National Aviation System
**security_delay**: Total time (minutes) of delay as a result of a security issue
**late_aircraft_delay**: Total time (minutes) of delay flights as a result of a previous flight on the same airplane being late

## d. Tools and Technologies Applied
- **Data Analysis**: Python (Pandas, Numpy, Matplotlib, Seaborn, Statsmodels.api, train_test_split from sklearn.model): EDA, Correlation, Multiple Linear Regression and Logistic Regression.
- **Visualization**: Python and Power BI
- **Version Control**: GitHub
- **Data Cleaning and Transformation**: Pandas and Matplotlib in Python.

## e. Key Insights Discovered
1. **Trends**:
   - Total number of flights and delays in December 2019 is more than in 2020.
2. **Airlines and Airports**:
   - Identified top 10 airlines and airports with the highest delay rates.
3. **Delay causes**:
   - Most causes: carrier, NAS and late aircraft. These are also 3 reasons affected by the system or human factors,... and can be controlled to minimize.
   - Other causes: weather and security. These are two objective reasons and are very difficult to control.

## f. Hypotheses Based on the Insights
1. Certain airports and airlines have operational inefficiencies contributing to high delay rates.
2. Carrier, National Aviation System and late aircraft significantly impact delay rates.

## g. Recommendations Based on Analysis Results
1. **For Airlines**:
   - Optimize flight schedules, allocate flight times and on-duty crew time reasonably to reduce carrier-related delays.
2. **For Airports**:
   - Invest in infrastructure and traffic management.
3. **Collaborative Efforts**:
   - Foster coordination among aviation stakeholders.

---

Feel free to clone this repository and explore the analysis. Contributions and suggestions are welcome!
