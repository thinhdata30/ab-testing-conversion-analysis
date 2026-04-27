# A/B Testing Conversion Analysis

## Overview
This project analyzes whether advertisements (ad) perform better than public service announcements (PSA) in terms of user conversion rate.

## Business Problem
A company wants to determine if running ads leads to higher conversions compared to PSA messages.

## Dataset
- ~1M+ user records  
- Features: user id, test group, converted, ad exposure  

## Methodology
- Converted boolean values to numerical format  
- Calculated conversion rate for each group  
- Performed two-sample Z-test for proportions  
- Visualized results using Seaborn  

## Results
- Ad conversion rate: 2.55%  
- PSA conversion rate: 1.78%  
- p-value ≈ 0  

## Conclusion
Ads significantly outperform PSA in driving conversions.  
The result is statistically significant (p < 0.05), meaning the improvement is unlikely due to chance.
## Results
- Ad conversion rate: 2.55%
- PSA conversion rate: 1.78%
- p-value < 0.05

## Conclusion
Ads significantly increase conversion rate compared to PSA.

## Key Insight
The ad campaign increased conversion rate by ~43% compared to PSA.
