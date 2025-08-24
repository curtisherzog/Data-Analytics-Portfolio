## Walmart Sales

**Original Data Sources**:  
[Walmart-Dataset](https://www.kaggle.com/datasets/yasserh/walmart-dataset)

---

### **Summary**

This analysis evaluates which factors drive weekly sales across Walmart stores, using historical weekly sales data, holiday indicators, and external economic conditions. Key insights show that holidays consistently boost weekly sales (~$75k on average), while economic conditions such as higher CPI and unemployment reduce sales. Some factors, like fuel price and temperature, have little to no effect. The low R² of the regression indicates additional store-level or seasonal factors not captured by this model play a large role in explaining sales variation.

---

### **Overview & Business Goal**

Retailers like Walmart generate massive volumes of weekly sales across hundreds of stores, with performance often influenced by promotions, holidays, and local economic conditions. The challenge is to determine which factors drive sales uplift and how to allocate marketing resources most effectively. By analyzing store-level weekly sales data alongside holiday indicators, promotions, and external factors such as unemployment and fuel prices, this project aims to identify which promotions and holiday periods consistently boost sales. The ultimate goal is to provide actionable insights to optimize promotional planning and maximize revenue.

---

### **Methodology**

1. Data Exploration – examined correlations and distributions in the raw dataset.
   
2. Data Wrangling – ensured consistent formatting, handled missing values, and standardized key metrics.

3. SQL Analysis – aggregated sales, and prepared datasets for Python analysis.

4. Python Analysis – computed correlations and ran OLS regression to quantify the effect of holidays, economic conditions, and environmental factors on weekly sales.

5. Tableau Visualization – created interactive dashboards including:

- Box plots for holiday impact

- Dual-axis line charts for economic conditions

- Scatter plots for non-significant factors

- Seasonal heatmaps for exploratory analysis

---

### **Skills Used**

SQL: Aggregate Functions, CTEs

Python: Pandas, Seaborn, Matplotlib, Numpy, Statsmodels.api, Correlations, Regression Analysis

Tableau: Dashboard design, dual-axis charts, scatter plots, box plots, heatmaps, filters, annotations, interactivity (hover tooltips, highlights)

---

### **Results & Business Recommendations**

Key Findings

1. Holidays drive sales uplift: Weekly sales increase by ~$75k on average during holiday weeks.

2. Economic conditions matter: Higher CPI and unemployment are associated with lower sales.

3. Fuel price and temperature have minimal effect: These factors are not significant drivers of weekly sales.

4. Other factors influence sales: The low R² (2.5%) suggests additional store-level trends, promotions, or local events matter.


Business Recommendations

- Prioritize marketing and promotions around key holidays to maximize sales uplift.

- Monitor economic trends (CPI, unemployment) for forecasting and inventory planning.

- Focus less on fuel price fluctuations or minor temperature variations when predicting sales.

- Investigate store-level patterns and promotions to explain remaining sales variability.

---

### **Next Steps**

- Incorporate store-level fixed effects or hierarchical models to capture variation across stores.

- Explore time series forecasting models to better account for seasonality and trends.

- Enhance Tableau dashboards with interactive filters for promotions and store types to support decision-making.

- Consider additional external factors such as local events, competitor promotions, and marketing spend.

