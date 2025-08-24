### Austin Housing  
**Original Data Source:**  
[Austin Housing Prices Dataset on Kaggle](https://www.kaggle.com/datasets/ericpierce/austinhousingprices?utm_source=chatgpt.com)

---

### **Summary**

This project analyzes over 15,000 home listings in the Austin, Texas housing market to determine which property features most influence home prices. Correlation analysis shows that bathrooms and bedrooms are the strongest predictors of price, while year built has little effect. The results highlight that buyer preferences lean heavily toward functional home features (bathrooms, bedrooms, and school quality) over age of the property.
---

### **Overview & Goals**

Understanding what drives home prices is critical for buyers, sellers, and real estate professionals. This project seeks to uncover the features that most impact price, helping stakeholders make informed decisions in negotiations, appraisals, and market positioning.

### **Methodology**

1. Data Cleaning & Exploration – Inspected missing values, standardized features, and ensured consistent price metrics.

2. SQL Analysis – Queried and aggregated housing attributes (e.g., bedrooms, bathrooms, garages, school ratings).

3. Python Analysis –

- Scatter plots and correlation coefficients to measure linear relationships.

- Comparison of different housing features against price.

- Distribution analysis of price per square foot by zip code.

4. Tableau Visualization – Built interactive dashboards, including:

- Home type vs. price

- Average home price by zip code

- Price trends over time

- Top 10 most expensive zip codes

---

### **Skills Used**

SQL: Data querying, and aggregations 

Python: Pandas, Seaborn, Matplotlib for scatter plots, correlation coefficients, and exploratory analysis

Tableau: Interactive dashboards with maps, filters, and trend visualizations

Excel: Data inspection and cleaning

---

### **Results & Insights**

Key Findings

- Bathrooms had the strongest correlation with price (0.504)

- Bedrooms also influenced price (0.299)

- Average school rating had a moderate positive effect (0.293)

- Garage spaces showed weak influence (0.157)

- Year built had almost no correlation (0.060)


Business Recommendations

- Listings should emphasize bathrooms and bedrooms in marketing, as they drive value perception.

- School ratings are important but secondary compared to in-home features.

- Home age is less relevant in Austin, where newer and older homes coexist with less effect on price.

---

### **Next Steps**

- Run a multiple regression model to control for overlapping effects.

- Incorporate zip code fixed effects to better capture location influence.

- Perform outlier analysis to remove ultra-luxury listings and check robustness of results.

- Enhance Tableau dashboards with interactive filters for home features, year built, and school ratings.
