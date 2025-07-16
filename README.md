# StyleSense – Customer Segmentation Using K-Means Clustering

StyleSense is a customer-centric fashion retail analytics platform that segments customers based on purchasing behavior using unsupervised machine learning. This repository includes the code, dataset, and analysis used to generate meaningful customer groups for targeted marketing strategies.

## 🚀 Project Overview

Customer segmentation helps businesses understand their diverse customer base by categorizing them into distinct groups. In this project, we use the K-Means clustering algorithm to analyze historical customer purchase data and identify patterns that drive personalized recommendations, campaign targeting, and business decisions.

## 📊 Dataset

### Original Dataset (`StyleSense_Dataset.csv`)
- `Customer_ID`
- `Purchase_Date`
- `Total_Price`
- `Quantity`
- `Season`

### Processed Features (Post-Clustering)
- `Avg_Order_Value`
- `Recency`
- `Season_Number`
- `Cluster_Label`
- `Segment`
- `Suggested_Campaign`

## 🧠 Methodology

- Feature Engineering: Recency, average order value, and season encoding
- Clustering Algorithm: K-Means with Elbow Method to find optimal `K`
- Evaluation: Visualized clusters using scatter plots, bar charts, and pie charts

## 📌 Visualizations

- 📉 Elbow Method for optimal `K`
- 📊 Clustered scatter plot (Avg Order Value vs. Recency)
- 📈 Bar chart of customer segment counts
- 🥧 Pie chart showing customer segment proportions

## 📁 Project Structure
.
├── data/
│ └── StyleSense_Dataset.csv
├── notebook/
│ └── kmeans.ipynb
├── images/
│ └── (Graphs and visualizations)
├── README.md
└── requirements.txt


## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 🔮 Future Enhancements

- Add DBSCAN and Hierarchical clustering comparison
- Use time-series forecasting to analyze trends
- Integrate deep learning-based embeddings for better segmentation
- Build a real-time dashboard for business stakeholders

## 🤝 Contributing

Feel free to fork this repo and submit a pull request if you'd like to contribute!


---

