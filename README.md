# Linear Regression - Housing Exercise

## Description
This project uses the California Housing dataset (derived from the 1990 U.S. Census) to explore the relationship between household characteristics and median income. The main question is whether houses in blocks with fewer households are owned by people with higher incomes. Linear regression models are used to test this hypothesis.

## Dataset
**Number of Instances:** 20,640  
**Number of Attributes:** 10  

**Predictive Attributes:**
- `longitude` – Block group longitude
- `latitude` – Block group latitude
- `housing_median_age` – Median house age in block group
- `total_rooms` – Total number of rooms within a block
- `total_bedrooms` – Total number of bedrooms within a block
- `population` – Block group population
- `households` – Total number of households within a block
- `median_income` – Median income for households within a block
- `ocean_proximity` – Proximity to ocean  

**Target Variable:**
- `median_house_value` – Median house value in USD

Dataset source: [California Housing dataset](https://www.dcc.fc.up.pt/~ltorgo/Regression/cal_housing.html)

## Libraries
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`

## Key Steps
1. **Data Exploration:** Examining missing values, descriptive statistics, and correlations.
2. **Data Cleaning:** Handling missing values and encoding categorical variables.
3. **Visualization:** Boxplots, scatterplots, and heatmaps to explore relationships.
4. **Linear Regression:** Modeling median income based on number of households.
5. **Evaluation:** Using Mean Squared Error (MSE) to assess model performance.
6. **Insights:** The analysis concludes that there is no clear evidence that blocks with fewer households correspond to higher incomes.

## Results
- MSE of the linear regression model: `3.63` (scaled)
- Relationship coefficient between households and median income: `8.34e-05`
- Intercept: `3.83`

Visualization of actual vs predicted median income is included.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
