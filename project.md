## Executive Summary
Built machine learning models to analyze Airbnb pricing and host performance using real-world data.

- Identified key drivers of price: location, property type, and host quality  
- Developed a classification model achieving 82% accuracy with a high recall (91%)  
- Generated actionable insights to support pricing optimization and host performance strategies  

---
## Project 1: Airbnb Price Prediction

### Business Problem
- Pricing is a critical factor influencing both booking rates and revenue. This project analyzes how various listing and host features impact Airbnb pricing.

### Approach
- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature engineering  
- Regression modeling  

### Key Insights
- Location is the most significant driver of price variation  
- Property type and room type strongly influence pricing tiers  
- Listings with higher ratings and stronger host profiles achieve price premiums  

### Model Performance 
- R²: 44.1%
- While the model explains a moderate proportion of price variation, this is expected given the complexity and noise in real-world Airbnb data. Many influencing factors, such as exact location nuances, listing visuals, and temporal demand patterns, are not fully captured in the dataset. Despite this, the model successfully identifies key pricing drivers and provides meaningful directional insights. 

### Business Impact
- Enables data-driven pricing strategies for hosts  
- Supports dynamic pricing recommendations  
- Improves revenue optimization decisions
 
### File
- `airbnb_price_prediction.ipynb`: Full analysis and model development

---
## Project 2: Airbnb Superhost Classification
### Business Problem
- Superhosts play a key role in platform trust and customer satisfaction. This project identifies factors that predict high-performing hosts.

### Approach
- Data preprocessing and cleaning  
- Handling class imbalance  
- Feature selection  
- Classification modeling (Decision Tree, Random Forest)  
- Cross-validation  

### Key Insights
- Review scores are the strongest predictor of Superhost status  
- Response rate and responsiveness significantly influence outcomes  
- Consistency in host performance is more important than isolated high ratings  
- Ensemble methods improve predictive performance  

### Model Performance
- The model achieves a high recall (91.69%), indicating a strong ability to correctly identify Superhosts. However, precision is relatively lower (55.16%), suggesting the model tends to classify some non-Superhosts as Superhosts.
- This trade-off is acceptable in scenarios where identifying potential high-performing hosts is prioritized over minimizing false positives.

### Business Impact
- Helps identify high-potential hosts early  
- Enables targeted improvement strategies  
- Strengthens platform trust and customer experience  

### File
- `airbnb_superhost_classification.ipynb`: Full model and analysis

---
## Tools & Technologies
- Python (pandas, scikit-learn)
- Regression Analysis
- Classification Models
- Data Visualization

---
## About Me
I am a fresh graduate from Korea University, majoring in Business Administration with a strong interest in data-driven decision making, consulting and strategic analysis.
