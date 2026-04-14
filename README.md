# Project Overview

End-to-end data analytics project untuk menganalisis performa bisnis e-commerce, perilaku customer, serta memprediksi return menggunakan machine learning. Hasil digunakan untuk menghasilkan insight bisnis dan strategi optimasi profit & retention.

## Data Extraction & tranformation (SQL)
1. Data Extraction : Import data from Excel to Dasabase SQL
2. Data Tranformation :
   - Net Revenue
   - Return Rate ( Date, Customer, Category )
   - High Risk Customer by Country
     
## Quick Analysis & pivot table (Excel)
1. left Joining : table Return dengan Order for (Column Return "Flag")
2. Feature Engeneering : Order(value :1), Net Sales, Net Return, Discount Loss
3. Pivot Table :
   - Time-based Profit Analysis
   - Location-based Profit Analysis
   - Category-based Profit Analysis
   - Customer Profit Segmentation


## Depp Analysis (Python) 
1. Profitability Analysis
   - Analisis profit berdasarkan quarter, market, country, category, dan product.
2. RFM Customer Segmentation
   - Segmentasi customer menjadi Champions, Loyal, At Risk, dan Hibernating.
3. Cohort & Retention Analysis
   - Analisis dampak discount terhadap retention (short-term vs stability).
4. Return Pattern Analysis
   - Identifikasi faktor return berdasarkan customer, market, category, dan shipping time.
4. Market Basket Analysis
   - Menemukan pola pembelian produk untuk strategi cross-selling & bundling.
5. Machine Learning
   - Model: Random Forest Classifier
   - Best resampling: Random Under Sampling
   - Hyperparameter tuning & threshold optimization
   - Feature importance: Profit, Sales, Shipping Cost, Shipping Days
   - F2-score improvement: 0.412 → 0.426
7. Insights
   - Maximize Q4 Revenue → campaign besar & fokus market : APAC, EU, US (74,6%), Category :  Technology (45,2%)
   - Improve Retention → kombinasi discount (short-term) + loyalty program (long-term)
   - Reactivate Customers → targeted promo untuk hibernating (27,2%)
   - Reduce Returns → percepat shipping & tingkatkan quality control
   - Cross-Selling → bundling Office Supplies + Staples
   - Model Improvement → Retraining secara berkala (per quartal) untuk adaptasi terhadap data baru
