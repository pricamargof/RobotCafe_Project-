## Project: LA Robot Café Market Analysis

---

### **Objective**

The goal of this project was to conduct a comprehensive market analysis of the Los Angeles food service industry to secure investment for a new **robot-staffed coffee shop**. The deliverable was a strategic conclusion detailing the most appropriate establishment type, ideal seating capacity, and a scalable chain development outlook for the LA market.

---

### **Results**

* **Market Structure:** The LA food service landscape is dominated by **Restaurants ($\text{75.2\%}$)**, followed by **Fast Food ($\text{11.0\%}$)**, and **Cafés ($\text{4.5\%}$)**.
* **Chain Strategy:** **Chains** (representing $\text{3676}$ establishments) overwhelmingly adopt a **high-volume, low-capacity** expansion model. This strategy prioritizes opening a large number of smaller, efficient units to maximize city-wide reach and accessibility.
* **Geographical Trends:** Location type correlates strongly with seating capacity:
    * **Traffic Centers** (e.g., World Way, near the airport) are saturated with **small restaurants** (under $\text{30}$ seats), built for rapid turnover like fast food and quick cafés.
    * **Central/Prestigious Areas** (e.g., Avenue of the Stars) show **higher median seating capacity** and significant variance, featuring both small, high-end spots and larger, more formal dining venues.

---

### **Tools**

* **Python**
* **Pandas** (Data cleaning, validation, and market segmentation)
* **NumPy** (Numerical operations)
* **Matplotlib & Seaborn** (Distribution visualization, including boxplots and bar charts)
* **SciPy** (Statistical analysis)

---

### **Skills Learned**

* **Data Cleaning and Validation:** Loading, cleaning, and validating an open-source dataset, including handling missing values in the chain column and checking data types.
* **Market Segmentation:** Analyzing the distribution and proportion of establishment types (e.g., Café, Fast Food, Restaurant).
* **Chain Analysis:** Characterizing the expansion strategy of chains in the market (volume vs. capacity model).
* **Geographical Analysis:** Identifying high-density commercial areas (top 10 streets) and extracting street names via feature engineering.
* **Capacity Distribution Analysis:** Determining the average and variability of seating capacity by establishment type and by high-density location.

---

### **Next Steps / Recommendations**

* **Optimal Concept:** The chain should be positioned as a **Café** or **Fast Food** concept to align with the successful segments for chain expansion.
* **Ideal Capacity:** Units should have an **ideal capacity between $\text{30}$ and $\text{40}$ seats**. This maintains the efficient, low-footprint model while allowing the innovative robot service to handle moderate flow.
* **Strategic Expansion:** The chain must implement an **efficient, low-capacity, high-volume model**. The focus must be on maximizing the **quantity of units** and **geographical saturation** rather than building large flagship locations.
* **Location Strategy:**
    * **Avoid** highly saturated **High-Density Traffic Centers** (like World Way).
    * **Target Medium-to-High Flow Corridors** that are **not yet saturated** by competitors (e.g., Western Avenue or near state universities).
