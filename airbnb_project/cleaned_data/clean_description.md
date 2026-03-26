
## Data Cleaning Process (Price Prediction Model)
### Key Steps
- Removed missing or invalid entries (e.g., price = 0)  
- Handled outliers in price distribution  
- Converted categorical variables into numerical formats  
- Standardized data types and formats

### Feature Correlation Analysis
![Correlation Heatmap](./airbnb_project/cleaned_data/price_correlation_heatmap.png)
- Several features show high correlation (e.g., availability metrics and review-related variables)  
- Strong multicollinearity was observed among variables such as:
  - availability_30, availability_60, availability_90  
  - review score subcategories
    
To improve model stability and reduce multicollinearity:
- Highly correlated variables (correlation > 0.8) were identified  
- Redundant features were removed while keeping the most representative variable  
- This helps:
  - Reduce overfitting  
  - Improve interpretability  
  - Ensure more reliable coefficient estimates  

**Notebook:** [View Data Cleaning Process](./cleaned_price_prediction.ipynb)
