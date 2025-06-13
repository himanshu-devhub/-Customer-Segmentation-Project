# 🛍️ Customer Segmentation Project

## 🎯 Project Objective
Segment customers using clustering to support targeted marketing campaigns and personalize services.

## 📂 Dataset
- **Source**: Mall Customer Segmentation Dataset (Kaggle)
- **Size**: ~200 records
- **Features**: Gender, Age, Annual Income, Spending Score

## 🛠️ Tools Used
- Python (pandas, scikit-learn, matplotlib, seaborn)
- Excel (for reviewing cluster profiles and marketing analysis)

## 🚀 Methodology
1. **Data Preparation**: Loaded dataset and encoded gender.
2. **Feature Scaling**: Standardized numeric features.
3. **Elbow Method**: Determined optimal cluster count (K=5).
4. **KMeans Clustering**: Segmented the data into 5 clusters.
5. **Cluster Profiling**: Analyzed and saved segment statistics.

## 📊 Key Insights
| Cluster | Description                          | Avg Income (k$) | Avg Spending Score |
|---------|--------------------------------------|------------------|---------------------|
| 0       | High-income & high spenders          | 90               | 82                  |
| 1       | Young low-income & low spenders      | 25               | 15                  |
| ...     | ...                                  | ...              | ...                 |

## 🎯 Marketing Action Plan
- **Cluster 0** (“Premium Spenders”): Upsell loyalty plans and exclusive offers.
- **Cluster 2** (“Bargain Seekers”): Run discounts and coupon campaigns.
- **Cluster 4** (“Low spenders”): Educate with value-based messaging.

## 📁 Project Files
- `notebook.ipynb`: Full clustering code and visuals.
- `Mall_cutomer.csv`: Dataset.
- `IMG.pdf`: Bar Chart,Elbow Curve, Pairplot.
- `README.md`: Documentation.

## ✅ Next Steps
- Deep dive with demographic segmentation
- Build ML models to predict cluster membership
- Integrate clusters into CRM for targeted campaigns



