# MSc-project

## Visualize Trends & Distributions

  - Overall attendance trends: Are there seasonal trends?
  - Individual attendance: Are some people more consistent?
  - Missing data: Any gaps in attendance records?
  
  
## Statistical Analysis

Since this is longitudinal data, we need models that account for repeated measurements per individual.

### Potential Models:

  - Linear Mixed-Effects Models (LME)
      - Good for continuous dependent variables (e.g., attendance frequency)
      - Accounts for individual differences with random effects
      - Handles missing data better than traditional regression
      
  - Time-Series Analysis (ARIMA)
      - If attendance shows temporal patterns (seasonality)
      - Uses autocorrelation to model attendance over time
      
  - Clustering
  
    - cluster individuals based on attendance patterns 