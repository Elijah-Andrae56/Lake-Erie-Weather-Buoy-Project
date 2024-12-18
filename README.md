# Lake Erie Weather Buoy Project

## Overview
This project investigates weather patterns in Lake Erie with a focus on improving boating safety. By analyzing data from buoy and airport weather stations, we explore the relationships between meteorological variables and dangerous boating conditions.

## Objectives
- Understand weather patterns to predict unsafe boating conditions.
- Develop predictive models for wave height using meteorological data.
- Identify key factors contributing to dangerous conditions.

## Features
1. **Data Exploration:**
   - Analysis of buoy and airport weather data.
   - Seasonal trends and distributions.
   - Relationships between meteorological variables (e.g., wind speed, wave height).

2. **Data Cleaning:**
   - Addressing missing values and outliers.
   - Mapping numerical data (e.g., wind direction) to qualitative insights.

3. **Inference:**
   - Identifying predictors of dangerous conditions.
   - Statistical testing to confirm relationships between variables.

4. **Prediction Models:**
   - Linear and Ridge regression models to predict wave height.
   - PCA for dimensionality reduction.
   - Clustering dangerous conditions based on key predictors.

## Data Sources
- **Buoy Weather Data:** Provides measurements of wind speed, wave height, and more.
- **Airport Weather Data:** Offers additional variables like precipitation and temperature.

## Key Insights
- Wave height is strongly influenced by wind speed and direction.
- Dangerous conditions (e.g., high wave height) correlate with specific wind patterns.
- PCA reveals significant collinearity among predictors.

## Technologies Used
- **Programming Languages:** Python
- **Libraries:**
  - Data Manipulation: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Modeling: `sklearn`, `statsmodels`

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/Elijah-Andrae56/Lake-Erie-Weather-Buoy-Project.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook for an in-depth exploration and modeling process.

## Results
- Prediction models achieve reasonable accuracy in forecasting wave height.
- Clear identification of high-risk boating conditions.
- Insights into the impact of weather on lake safety.

## Future Work
- Incorporate real-time data for live predictions.
- Improve model accuracy using advanced techniques like neural networks.
- Extend analysis to other Great Lakes.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License.

---

### Acknowledgements
Thank you to my mentors, peers, and data providers for their support and resources.

