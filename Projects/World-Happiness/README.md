## World-Happiness

**Original Data Sources**:  
- [World Happiness Data](https://worldhappiness.report/ed/2024/#appendices-and-data)

---

### **Goal**

**The goal of this project was to analyze global happiness rankings and identify which factors show the strongest correlations with happiness..**

**Using Python for statistical analysis and Tableau for visualization, I explored relationships between GDP, social support, life expectancy, and other contributing factors to happiness.**

---

### **Description**

**This project uses the World Happiness Report 2024 dataset, which includes:**
- **Country-level happiness rankings and scores**
- **Key contributing metrics such as GDP per capita, social support, healthy life expectancy, freedom, and generosity**

**After loading the data into Python, I calculated correlation coefficients between happiness rank and each factor. Tableau was then used to create interactive visualizations to explore geographic patterns, top/bottom rankings, and variable relationships.**

---

### **Tools Used**

- **Excel** – initial inspection and cleaning  
- **SQL (pgAdmin)** – joins, aggregations, and data cleaning  
- **Python (Pandas, Seaborn, Matplotlib)** – plotting and correlation analysis  
- **Tableau** – dashboards showing club spend vs league performance

---

### **Tableau Visualizations**

- **Map** – Countries by happiness (darker = happier)
- **Scatter Plot** – Happiness vs GDP per capita
- **Bar Charts** – Top 10 happiest countries / Bottom 10 least happy countries
- **Line Chart** – Score vs Healthy Life Expectancy

---

### **Results**
*(Note: Negative results are because because a lower number rank results in a happier country)*  

- **Correlation between Rank and GDP per Capita**: **-0.779976**
- **Correlation between Rank and Social Support**: **-0.772974**
- **Correlation between Rank and Healthy Life Expectancy**: **-0.714517**
- **Correlation between Rank and Freedom**: **-0.603452**
- **Correlation between Rank and Generosity**: **-0.061004**

**These results suggest that GDP per capita, social support, and life expectancy have strong relationships with happiness rankings, while generosity has almost no correlation.**
