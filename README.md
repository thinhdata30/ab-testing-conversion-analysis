# A/B Testing Conversion Analysis

## Overview
This project evaluates whether advertisements (ad) perform better than public service announcements (PSA) in driving user conversions.

## Business Problem
A company wants to determine if running ads leads to higher conversion rates compared to PSA messages.

## Dataset
- ~1M+ user records  
- Features: user_id, test group, converted, ad exposure  

## Methodology
- Cleaned dataset and converted boolean values to numeric  
- Calculated conversion rates for each group  
- Performed two-sample Z-test for proportions  
- Visualized results using Seaborn  

## Results
- Ad conversion rate: 2.55%  
- PSA conversion rate: 1.78%  
- p-value ≈ 0  

## Key Insight
Ads increased conversion rate by ~43% compared to PSA.

## Conclusion
Ads significantly outperform PSA in driving conversions.  
The result is statistically significant (p < 0.05), indicating the improvement is not due to chance.

## Conclusion
Ads significantly increase conversion rate compared to PSA.

## Key Insight
The ad campaign increased conversion rate by ~43% compared to PSA.
