# Project Title

**Crop Yield Analysis and Data Cleaning Using Python**

## 📊 Project Overview and objective

This project focuses on analyzing agricultural crop production data to identify patterns and factors affecting crop yield. The analysis was performed using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn to clean, process, analyze, and visualize the dataset.

The main objective of this project is to understand crop production trends, compare yield across different crops and regions, and generate insights that can help improve agricultural decision-making.


## 🛠️ Tools & Technologies

The following tools and libraries are required to run this project:

* Python 3.x
* colab notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

Install required libraries using:

pip install pandas numpy matplotlib seaborn


### Dashboard

<img width="1191" height="669" alt="Screenshot 2026-06-16 134445" src="https://github.com/user-attachments/assets/0a9d98bd-565d-4d5e-977f-5667d845b03f" />



### Project Insights

The analysis provides insights such as:

* Crop Production: Maize is the dominant volume contributor with a peak average yield of 2,776.74 MT, whereas Cotton registers the lowest footprint at 844.56 MT.

* Regional Contribution: Total agricultural production is highly concentrated in three zones: the North (27.9%), followed closely by the East (22.5%) and West (22.1%), while the Southwest lags significantly behind as the lowest producer at 12.8%.

* Resource Impact: Farm plots treated with fertilizer achieve a substantially higher average output of ~2,025 MT, compared to unfertilized plots which stop at ~1,275 MT (a clear 750 MT production gap).

* Scale Driven Growth: The strongest mathematical driver of harvest volume is physical land scale, proved by a strong positive correlation of 0.63 between Farm_Size_Acres and Crop_Yield_MT.

* Environmental & Soil Preferences: Specific crop yields are highly sensitive to their soil mediums. Soybeans (1,804.27 MT) and Wheat (1,489.16 MT) thrive optimally in Loamy soil; Maize (3,015.58 MT) and Cotton (963.00 MT) adapt best to Sandy soil; while Rice (2,504.86 MT) maximizes its performance strictly in Silt soil.

* The Rainfall Sweet-Spot: Yields do not scale infinitely with water. There is an optimal climate zone where crop yields peak dynamically between 1,000 mm and 1,600 mm of annual rainfall. Beyond this window, extreme drought or flooding conditions act as stressors that suppress overall growth.


## 💡 Recommendations

* Implement Precise Soil-to-Crop Mapping: Mandate regional crop distribution strategies that align crops with their top-performing soil environments (e.g., dedicate Sandy soils entirely to Maize/Cotton and Silt basins exclusively to Rice).

* Scale Fertilizer Deployment: Prioritize fertilizer distribution frameworks to unfertilized or underperforming farm plots, as this single management practice guarantees an average yield lift of roughly 750 MT per plot.

* Target Regional Infrastructure in the Southwest: Investigate the structural bottlenecks causing the Southwest region to produce a mere 12.8% of total output. Deploy irrigation systems or land consolidation efforts there to build resilience against its lower yields.

* Develop Climate-Resilient Water Management: For regions experiencing rainfall outside the optimal 1,000 mm – 1,600 mm boundary, install smart drainage systems to handle flooding and water-retention basins/reservoirs to safeguard against droughts.


## Conclusion

From the analysis, we identified meaningful relationships and patterns in the agricultural dataset. The visualizations and multi-variable insights highlight that physical land scale, strategic fertilizer deployment, the optimal rainfall spot and precise crop-to-soil mapping are the dominant factors influencing crop yields and this analysis provides a strong, data-driven foundation for maximizing future harvest volumes and making smarter, evidence-based farming decisions.





