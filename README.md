# Aging Finland: Cost & Healthcare Capacity Analysis

**Author:** Israel Adesokan  
**Tools:** Power BI, Power Query, DAX, Excel  
**Data Sources:**  
- THL (Finnish Institute for Health and Welfare)  
- Statistics Finland  
- OECD Health Data  
- Eurostat  

## Executive Summary
This Power BI project analyzes the dual threat posed by Finland's aging demographics: escalating Social Protection (SP) costs and critical Healthcare Workforce capacity risk through 2035.

## Key Insights
The analysis reviews the current available data and projects significant strain on public resources.
Age 65+ Population Projection:
- Finland’s 65+ population will reach 25% by 2035.

Financial Burden: 
- Elderly care expenditure grew by +116% in 20 years (CAGR 3.9%).
- Social Protection expenditure on Old Age is projected to increase to approximately €5.4 Billion by 2035 (using a conservative growth model).

Capacity Gap: 
- 21% of doctors and nurses are aged 55+.  
- The Elderly-to-Doctor ratio is forecasted to rise from 82:1 (Current) to 94:1 (Projected), and Elderly-to-Nurse ratio from 19:1 (current) to 21:1 (2035 projection), due to demographic growth and anticipated workforce retirements.
- Hospital beds per 1,000 inhabitants = 2.6 (OECD avg = 4.5).  

Regional Hotspots: 
- Visualization highlights critical regional burdens (e.g., South Savo at 33.9% elderly population).


## Files Included
- `Aging_Finland - Cost & Healthcare.pbix` 
- `Aging_Finland_Report.pdf` 
- `/data` → Raw datasets  
- `/visuals` → dashboard screenshots  

## Technical Skills Demonstrated
-	Power Query (M): Data cleansing, unpivoting (for Population Pyramid), and standardization.
-	DAX: Compound Annual Growth Rate (CAGR), Scenario Forecasting, and custom Risk Ratio calculation.
-	Data Modeling: Established a unified model linking demographics, finance, and workforce tables.
-	Visualization: Advanced use of Filled Maps and Dynamic Population Pyramid structures.


## License
This project uses publicly available data from THL, OECD, and Eurostat.
