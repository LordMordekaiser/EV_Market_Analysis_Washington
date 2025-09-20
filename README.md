
### **EV Data Analysis and Market Insights**

This project is a data analyst portfolio piece aimed at conducting an in-depth analysis of the electric vehicle (EV) market in Washington State. The project focuses on developing strategic solutions for data quality issues, exploring market trends, and presenting key findings through interactive visualizations. This work demonstrates the ability to derive meaningful insights from raw data, solve analytical problems, and present results in a clear and professional manner.

---

### **Project Objectives**

- To identify the most popular EV models and their market share in Washington.
- To analyze the average electric range trend for Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs) over time.
- To statistically examine the relationship between a vehicle’s price (`Base MSRP`) and its electric range (`Electric Range`).
- To identify significant data quality issues within the dataset, develop robust strategies to address them, and document this process.

---

### **Tools Used**

- **Python:** The primary tool for data manipulation, cleaning, and statistical analysis.
  - `Pandas`: For data frame operations and data cleaning.
  - `Matplotlib` & `Seaborn`: For data exploration and creating professional visualizations.
- **Power BI:** To create an interactive and dynamic dashboard for presenting the project's findings.
- **Git & GitHub:** For version control and project collaboration.

---

### **Data Source**

The analysis for this project is based on the following public dataset:
- **[Electric Vehicle Population Data](https://catalog.data.gov/dataset/electric-vehicle-population-data)**

---

### **Analysis Process and Key Findings**

This project follows a comprehensive analytical methodology that prioritizes **data quality**.

1.  **Data Quality Discovery:**
    - The initial analysis revealed that over **72% of the data** in the `Base MSRP` (manufacturer's suggested retail price) and `Electric Range` columns was either missing or contained illogical values (e.g., zeros). This critical data gap severely impacted the reliability of any price analysis.

2.  **Strategic Solution:**
    - A strategic decision was made to address this data gap in Power BI, rather than simply discarding the problematic data in Python. A new column was created in Power BI and populated with estimated data sourced from the internet. The small, clean dataset from the Python analysis was then used as a **benchmark** to validate the accuracy of these new estimates. This approach demonstrates a flexible and robust problem-solving skill.

3.  **Trend Analysis and Correlation:**
    - **Range Trend:** The analysis shows a consistent increase in the average range of BEVs over the years, while PHEV ranges have remained more stable. This finding validates the rapid advancement in battery technology.
    - **Price-Range Relationship:** A Pearson correlation analysis (`r = 0.61`) between `Base MSRP` and `Electric Range` indicated a **moderate positive relationship**. This suggests that while price and range are linked, other factors such as brand, luxury features, and technology also play a significant role in a vehicle's pricing.

4.  **Market Distribution:**
    - The top 20 most popular EV models in Washington account for a large portion of the total market. This confirms that the market is concentrated around specific models and manufacturers. Specifically, vehicles from the Tesla brand were found to make up **41% of all vehicles** in the clean dataset.

---

### **Future Work**

This project provides a solid foundation for further analysis. Potential future work could include:
- Analyzing how the popularity of models changes over time.
- Geographically mapping market distribution at the city or county level.
- Building predictive models (e.g., Regression Analysis) to forecast vehicle prices.

---


### **Power BI Dashboard**

The findings of this analysis have been visualized in an interactive Power BI dashboard. You can review the full report by downloading the `.pbix` file from the project's root directory or by viewing the screenshots in the `screenshots` folder.
