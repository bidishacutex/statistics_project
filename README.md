# statistics_project

1. Data Preparation:
- The dataset was loaded, inspected, and cleaned.
- Missing values and duplicates were removed.
- Data-types were adjusted, and key variables like trip duration (in minutes) were calculated.

2. Exploratory Data Analysis (EDA):
- The data was filtered to exclude outliers and retain meaningful values for variables like fare_amount, trip_distance, and duration.
- Payment types were categorized into "Card" and "Cash."

3. Distribution Analysis:
- Histograms were plotted to compare fare amounts and trip distances between payment types.
- Fare amount and trip distance showed variation based on payment methods.
- A pie chart highlighted that a larger percentage of customers used cards over cash.

4. Passenger Count Insights:
- Passenger count distributions were analyzed by payment type.
- A horizontal stacked bar chart revealed the percentage distribution of passenger counts across payment methods.

5. Hypothesis Testing:
* Hypotheses:

    Null (H₀): No difference in average fare between card and cash payments.
    Alternative (H₁): A difference exists in average fares.

Using a t-test:

- T-statistic and p-value were calculated.
- Results showed whether average fares significantly differ between payment types.

6. Regression Analysis:
- A simple linear regression model was created to analyze the relationship between trip duration and fare amount.

Key findings:

- Positive correlation between trip duration and fare amount.
- R-squared indicated the model's explanatory power.
- A scatter plot with a regression line illustrated the fit of the model.

# Key Insights:

* Card payments are more frequent than cash payments.
* Passenger count distributions and trip characteristics vary between payment methods.
* Duration and fare amount are positively correlated, with a linear relationship.