# 🧠 Customer Segmentation using K-Means Clustering

Welcome to my Data Science project built for CodeClause Internship!   
This notebook applies **K-Means Clustering** to group mall customers into distinct segments based on their **Annual Income** and **Spending Score**.

---

##  Project Objective

 Segment customers into meaningful groups so that businesses can:
- Personalize marketing strategies
- Improve customer experience
- Boost sales and loyalty

---

## 📂 Dataset Info

- **Dataset**: `Mall_Customers.csv`
- **Attributes**:
  - `CustomerID`: Unique ID
  - `Gender`: Male/Female
  - `Age`: Age of the customer
  - `Annual Income (k$)`: Income in 1000s
  - `Spending Score (1-100)`: Score based on shopping behavior

---

##  Technologies Used

- Python 
- Pandas, NumPy
- Matplotlib, Seaborn 
- Scikit-learn (KMeans) 

---

##  Feature Selection

For clustering, we selected the most relevant features:
- `Annual Income (k$)`
- `Spending Score (1-100)`

These reflect purchasing power and spending habits.

---

##  Elbow Method

Used to determine the **optimal number of clusters (k)**  
 Plotted WCSS (Within-Cluster Sum of Squares) vs. clusters 1–10 to find the "elbow point".

 Optimal clusters found: `5`

---

##  K-Means Clustering

- Applied **KMeans** with `n_clusters=5`
- Used **k-means++** for better centroid initialization
- Cluster labels added back to the dataset

---

##  Visualizations

- 2D scatter plot of customers by income & spending score
- Clusters clearly show unique customer groups

![Scatter Plot](https://i.imgur.com/6dbfdU9.png) *(replace with your own image if you have one)*

---

## 🔍 Cluster Insights

| Cluster | Income Level | Spending Score | Customer Type                    |
|---------|---------------|----------------|----------------------------------|
| 0       | Low           | High           |  Enthusiastic Budget Spenders   |
| 1       | Moderate      | Very Low       |  Cautious or Uninterested Buyers |
| 2       | Low           | Low-Mid        |  Need-Based Shoppers            |
| 3       | High          | High           |  Confident Luxury Seekers       |
| 4       | Moderate      | Very High      |  Impulse or Loyal Shoppers      |

---

##  Business Use Case

With this segmentation, businesses can:
- Target luxury seekers with premium deals
- Engage budget shoppers with discounts
- Understand who to upsell or retain

---

##  Conclusion

- K-Means successfully segmented mall customers
- Real-world use in marketing & CRM
- Simple unsupervised ML with impactful insights

---

##  Made by: Jyotshna Komma  

-  B.Tech Data Science | Intern @ CodeClause
-  Passionate about Data & AI!

---

If you like this project, feel free to star it on GitHub!

