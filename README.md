# Portfolio
Portfolio of academic data analytics projects developed with Python, SQL, Power BI, and Excel.

# Projects

  # 1) Urban Mobility & Economic Productivity Analysis (Python)
  # 🧾 Executive Summary

  **Context & Objective:**  
  - **What is the relationship between urban mobility (traffic congestion and travel times) and economic productivity (GDP per capita)?**
  
      The analysis indicates that the relationship between urban mobility and economic productivity is weak. Although some cities with higher GDP per capita experience            significant traffic congestion and longer travel times, no consistent trend suggests that greater economic development necessarily leads to better urban mobility.
  
  - **Key Variables and Their Relevance**

     The analysis used urban mobility indicators such as jams_delay, traffic_index_live, and travel_time_live_per_10kms_mins, together with city_gdp_capita as an indicator       of economic productivity. These variables help identify cities where traffic congestion may reduce transportation efficiency and support urban planning, prioritization      of infrastructure investments, and mobility policy development.

  **Data Coverage**  
  - **Analysis period:** 2024
  
  - **Geographic scope:** 15 cities across 7 Latin American countries.

  **Methodology:**  
  - **Data Preparation**
      Data formats were standardized, data types were corrected, and column consistency was verified before conducting the analysis.
  - **Data Integration**
      Traffic and economic datasets were aggregated by city and year to calculate average values, then merged using an **INNER JOIN** to create a unified analytical dataset.
  - **Data Validation**
      Histograms, box plots, and comparative visualizations were used to examine data distributions, detect outliers, and identify overall trends.

  **Key Findings:**
  - **Relationship Between Traffic and GDP per Capita**
       The results reveal a weak relationship between traffic congestion indicators and GDP per capita, with no clear linear association between urban mobility and economic        productivity.
  - **Outliers**
      Several cities displayed significantly higher congestion levels than the rest of the dataset, suggesting the need for further investigation to better understand the         factors driving their performance.
  
  **Recommendations**  
  
  - **Bogotá** stands out as the city that best represents the combination of high traffic congestion (**jams_delay ≈ 1,142**) and **relatively low GDP per capita                 (city_gdp_capita ≈ 11,442)**, making it a strong candidate for transportation infrastructure investments.
  - **Lima** also experiences very high congestion (**jams_delay ≈ 1,052**), although its **GDP per capita is slightly higher (≈ 13,472)**.
  - **Buenos Aires** records considerably lower congestion (**jams_delay ≈ 571**) while having a substantially higher **GDP per capita (≈ 18,117)**, making it less                representative of the high-congestion, low-productivity profile.
    
    Although **Mexico City** and **São Paulo** exhibit the highest congestion levels in the dataset, their **GDP per capita** values are not among the lowest. Therefore,        they do not reflect the same combination of severe congestion and lower economic productivity.
    
    Based on the available 2024 data, **Bogotá should be prioritized for transportation infrastructure investments**, as it combines very high congestion with comparatively     lower economic productivity. However, this conclusion should be interpreted as a **descriptive comparison rather than a statistical correlation**, since the analysis is     based solely on data from **2024**.



 
  
