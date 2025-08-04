## Premier League Spending vs Performance

**Original Data Sources**:  
- [Premier League Transfer Activity](https://github.com/ewenme/transfers/blob/master/data/premier-league.csv)
- [Premier League Match Results](https://jaseziv.github.io/worldfootballR/articles/extract-understat-data.html?utm_source=chatgpt.com)  

---

### **Goal**

**The goal of this project was to write more advanced SQL queries to join two datasets together and determine the correlation between financial investment and success in the Premier League.**

**I created visualizations of teams’ transfer activity and league performance, and used Python to calculate statistical correlations between spending and success.**

---

### **Description**

**This project combines two main datasets:**
- **Premier League match results from 1990 onward, including goals for and against**
- **Transfer activity (inbound and outbound) among Premier League clubs since 2010**

**After cleaning the data, I used SQL to examine club performance and transfer market behavior. I then joined the tables to analyze how spending relates to success. Tableau was used to visualize key patterns, and Python was used for statistical correlation analysis and scatter plots.**

---

### **Tools Used**

- **Excel** – initial inspection and cleaning  
- **SQL (pgAdmin)** – joins, aggregations, and data cleaning  
- **Python (Pandas, Seaborn, Matplotlib)** – plotting and correlation analysis  
- **Tableau** – dashboards showing club spend vs league performance

---

### **Results**

- **Correlation between previous year’s total spend and league position**: **-0.472**  
  *(Note: Negative because higher league position = lower number)*  
- **Correlation between spend and total points**: **0.503**  
- **Correlation between spend and goal differential**: **0.514**

**These results suggest a moderate positive correlation between financial investment and on-field success in the Premier League.**
