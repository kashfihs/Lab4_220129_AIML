# K-Means Clustering — Customer Segmentation

**Assignment:** K-Means Clustering Implementation  
**Dataset:** Mall Customers (Age, Annual Income, Spending Score)  
**Student ID:** 190110

---

## 📁 Repository Structure

```
├── dataset/
│   └── custom_customers.csv     ← 10 real-world custom data points
├── model/
│   └── 190110.pkl               ← Saved trained KMeans model
├── 190110.ipynb                 ← Google Colab notebook (full pipeline)
└── README.md
```

---

## 📊 Cluster Scatter Plot

> *(After running the notebook, screenshot your scatter plot and paste it here)*

---

## 🔍 Cluster Profiles (Interpretation)

Based on the 5 clusters identified by the model:

| Cluster | Income Level | Spending Level | Profile |
|---------|-------------|----------------|---------|
| 0 | Low | Low | Budget-conscious, conservative spenders |
| 1 | High | Low | Wealthy but frugal customers |
| 2 | High | High | Premium target — high income, high spend |
| 3 | Low | High | Impulsive buyers, spend beyond means |
| 4 | Medium | Medium | Average balanced customers |

---

## ⚙️ How to Run

1. Open `190110.ipynb` in Google Colab
2. Update `GITHUB_REPO_URL` and `REPO_NAME` variables in Cell 1
3. Click **Runtime → Run All**
4. The notebook will automatically:
   - Clone this repo
   - Load standard Mall Customers dataset
   - Find optimal K via Elbow Method
   - Fit and save the KMeans model
   - Predict clusters for custom data

---

## 📦 Custom Data

10 individuals surveyed with their Age, estimated Annual Income (k$), and self-rated Spending Score (1–100):

| CustomerID | Age | Annual Income (k$) | Spending Score |
|------------|-----|--------------------|----------------|
| 1  | 22 | 18  | 75 |
| 2  | 35 | 62  | 45 |
| 3  | 28 | 45  | 80 |
| 4  | 50 | 90  | 20 |
| 5  | 45 | 105 | 15 |
| 6  | 31 | 38  | 70 |
| 7  | 60 | 72  | 25 |
| 8  | 24 | 20  | 85 |
| 9  | 42 | 130 | 40 |
| 10 | 38 | 55  | 60 |
