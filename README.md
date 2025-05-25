## House Price Comparison: London vs. Istanbul

### Project Overview
This project aims to compare house prices in two distinct locations: **London (United Kingdom)** and **Istanbul (Turkey)**.  
By analyzing various factors influencing real estate prices, I seek to uncover trends and differences between these two markets.

---

### Data Sources
Data was collected from Kaggle. To reduce the effect of global inflation, similar time frames were selected for both datasets.

- **London House Prices**: [Kaggle Dataset](https://www.kaggle.com/datasets/jakewright/house-price-data)  
- **Istanbul House Prices**: [Kaggle Dataset](https://www.kaggle.com/datasets/aselasel/house-price-dataset)

---

### Methods

1. **Data Collection & Preprocessing**
   - Cleaning and handling missing data
   - Standardizing formats for consistency
   - Converting currencies (1 GBP = 20.38 TL for 2022)
2. **Feature Engineering**
   - Creating new attributes (e.g., price per square meter)
   - Potential enrichment with building age or neighborhood info
3. **Exploratory Data Analysis (EDA)**
   - Visualizing price distributions
   - Correlation analysis
   - Comparing features across cities
4. **Statistical Analysis & Modeling**
   - Identifying significant price drivers
   - Regression models: Linear Regression, Random Forest, XGBoost
   - Evaluating with R², MAE, RMSE, MAPE

---

### Expected Outcomes
- A comprehensive comparison of house pricing trends between Istanbul and London
- Key drivers of house prices in each city
- Practical insights for investors and home buyers

---

### Tools & Technologies
- **Python**: Pandas, NumPy, Scikit-learn  
- **Notebook**: Jupyter  
- **Visualization**: Matplotlib, Seaborn  
- **ML Techniques**: Regression models, cross-validation  
- **Statistical Analysis**: Hypothesis testing, correlation coefficients

---

### Findings
- **London**: Strong correlation between house price and square meters  
- **Istanbul**: Weaker correlation, likely due to missing features like location quality  
- **Bathrooms**: Some predictive power, but less than area size  
- Models predict London house prices more accurately due to higher-quality features

---

### Limitations and Future Work

#### Limitations
- Limited or missing data on building age, location, and amenities
- No inclusion of macroeconomic or zoning factors
- Inflation normalization is approximate
- No seasonality or time trend analysis

#### Future Work
- Incorporate regional details (district-level analysis)
- Add new features such as age of the building, number of floors, and parking
- Perform time-series modeling with historical data
- Explore hedonic pricing models

---









