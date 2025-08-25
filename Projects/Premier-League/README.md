## Premier League Spending vs Performance

**Original Data Sources**:  
- [Premier League Transfer Activity](https://github.com/ewenme/transfers/blob/master/data/premier-league.csv)
- [Premier League Match Results](https://jaseziv.github.io/worldfootballR/articles/extract-understat-data.html?utm_source=chatgpt.com)  

---

### **Summary**

This project explores the relationship between financial investment and on-field success in the English Premier League. By combining match results with transfer market activity, the analysis examines how strongly spending on players correlates with performance outcomes.

Correlation analysis suggests that spending is moderately associated with higher points, stronger goal differentials, and better league finishes—though money alone does not guarantee success.

---

### **Overview & Objective**

Understanding the impact of transfer spending is central to debates among fans, analysts, and club executives. This project aims to uncover how investment in players translates into performance on the pitch, helping to quantify whether “money buys success” in the Premier League.

---

### **Methodology**

Data Cleaning & Preparation
- Standardized transfer fees (e.g., converting “£3.5m” → 3,500,000).
- Removed incomplete/loan records and handled missing values.
- Linked clubs consistently across transfers and results.

SQL Analysis
- Aggregated club spending by season.
- Calculated seasonal points, league position, and goal differential.
- Joined transfer and results tables for combined analysis.

Python Analysis
- Scatter plots of spend vs performance metrics.
- Correlation coefficients to measure statistical relationships.
- Distribution analysis of spending across clubs/seasons.

Tableau Visualization
- Dashboards highlighting spending vs. league finish.
- Club-by-club comparisons of spend vs points.
- Trend lines showing how top clubs’ investments evolved.

---

### **Skills Used**
- SQL (pgAdmin): Joins, aggregations, and transformations
- Python: Pandas, Matplotlib, Seaborn for scatter plots & correlations
- Tableau: Interactive dashboards for spend vs performance trends
- Excel: Data inspection and early cleaning

---

### **Results & Insights**

Key Findings:
- Spending vs League Position: -0.472 correlation (negative because rank = lower number is better).
- Spending vs Points: 0.503 correlation.
- Spending vs Goal Differential: 0.514 correlation.

Takeaways:
- More spending generally improves performance, but the effect is moderate.
- Some clubs consistently outperform their spend (efficient spenders).
- Others spend heavily without proportional success (inefficient spenders).
- Suggests additional factors—coaching, tactics, youth academies—also matter.

- ---

### **Next Steps**
- Run a fixed-effects regression model to control for club-specific advantages.
- Examine net spend (in vs out) rather than gross spend.
- Expand analysis to include Champions League qualification and trophy wins.
