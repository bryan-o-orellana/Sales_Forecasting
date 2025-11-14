# Sales Forecasting - Intermoda S.A

**Note:** This is a real forecasting project for Intermoda S.A. All data is the company's property; therefore, the complete dataset cannot be shared.

## Summary
The goal of this forecast was to provide an overview of expected sales for early 2026 using **Forecast Pro**, applying an **exponential smoothing** model with a **bottom-up** strategy.

The full dataset contains sales reports from 2022. The main product is **dress jeans**, organized in the following hierarchy:  

- Gender  
- Base  
- Color  
- Size  

## Methodology
1. Historical sales data from 2022 was loaded into Forecast Pro.  
2. An **exponential smoothing** model was applied, selecting the most suitable variant based on trend and seasonality.  
3. A **bottom-up** strategy was used: forecasts were generated at the most granular level first and then aggregated to higher levels.  
4. Charts and tables were created to visualize the projections and identify key patterns.  

## Key Insights
- Sales show seasonal patterns with peaks during promotional periods.  
- Certain product combinations (color/size) are projected to have higher demand in early 2026.  
- Aggregated forecasts help anticipate inventory and production planning.  

## Visualizations
![Monthly Forecast](assets/proyeccion_mes.png)  
![Size Distribution](assets/grafica_tallas.png)  

(Additional charts and insights are available in the `assets/` folder.)

## Conclusion
This analysis allows Intermoda S.A. to better plan inventory and production of dress jeans for the first months of 2026, making data-driven decisions based on both disaggregated and aggregated forecasts.

---

*Repository created for portfolio purposes. Complete data cannot be shared due to confidentiality.*
