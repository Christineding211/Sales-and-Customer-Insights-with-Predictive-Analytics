## Project Title

### Retail Sales and Customer Insights with ML Predictions

## Business Objective

### To analyse sales data, customer behaviour, promotions, and competition distance to discover actionable insights that improve sales performance and inform strategic business decisions. A Random Forest Regressor was used to predict future sales trends by learning patterns in historical data, such as promotions, customer behaviour, and seasonality.

## Methodology
![image](https://github.com/user-attachments/assets/920bfda7-4d86-43e1-9acd-f5561461a9f6)


## Business Insights
### Sales and Seasonal insights
#### 1.  Impact of Holidays:
- School holidays generally increase sales, however the effect is less significant or mixed when combined with certain state holidays.
- Type a state holidays consistently show high sales and Type b holidays show an extreme spike in sales when no school holiday coincides.

#### 2.  Seasonal Trends:
- Winter and Spring have the highest average sales, with December peaking across all assortments.
- Assortment b consistently outperforms others, while a has weaker performance overall.


![image](https://github.com/user-attachments/assets/7e5b5645-3cc7-417d-8391-7c253a33220d)

![image](https://github.com/user-attachments/assets/305a6378-9f5e-4505-bd3d-728b50c08310)

### Promotions effect:
Running multiple promotions reduces average sales by 9.09%, possibly due to overlapping promotions or the two promotions might target the same customer base, causing one promotion to cannibalise the effect of the other.


### Competitor Analysis:
#### 1.  Distance Effect:
- Competitor distance has minimal impact on store sales, with a very weak negative correlation.
- Internal factors like promotions and assortment are more impactful than competitor proximity.

#### 2.  Promotions in Competitive Areas:
- Promotions are most effective in stores near competitors (0-1 km).
- When competitors are located further away, promotions have a reduced impact on customer traffic.

## Prediction Results
The model achieved an MAE of 734.94, an RMSE of 1002.60, and an R² score of 0.895, suggesting that the model explains approximately 89.5% of the variance in the sales data. This demonstrates strong predictive power.


![image](https://github.com/user-attachments/assets/57121f96-0be7-4dc3-acd7-08fabf84c998)

## Business Recommendations
### 1. Promotions 
- Focus on a single, well-structured promotion for greater impact.
- Allocate more promotional resources to stores near competitors.

### 2. Holiday and Seasonal Strategy
- Prioritise state holidays and combined holidays for marketing and promotions.
- Target specific assortments (b and c) during peak seasons to maximise sales.
  
### 3. Competitor Strategy
- Stores near competitors should prioritize aggressive promotions to draw in customers.
- Stores further away should focus on enhancing customer experience rather than heavy promotions.

### 4. Insights into Traffic and Sales
- Investigate reasons for sales drops in months 7–8 for Assortment b.
- Analyse December's daily customer traffic to understand shopping habits and adjust store hours accordingly.
