# 🛍 Mall Customer Clustering App

This project is a **Tkinter-based desktop application** that performs **K-Means clustering** on a mall customers dataset to group customers based on their **Annual Income** and **Spending Score**.

The app allows you to:
- 📂 Load a CSV dataset.
- 🔍 Preview the dataset in a scrollable table.
- ⚡ Perform K-Means clustering.
- 📊 Visualize clusters with a scatter plot.
- 📝 View the dataset updated with cluster labels.


## 📌 Features
- **Beautiful UI** with Tkinter.
- **Dataset preview** before and after clustering.
- **Interactive cluster selection** (choose number of clusters).
- **Matplotlib integration** for charts.
- **Customer count per cluster** in the plot legend.

## 🛠 Tech Stack
- **Python 3**
- **Tkinter** – GUI
- **Pandas** – Data handling
- **NumPy** – Numerical computations
- **Matplotlib** – Visualization
- **Scikit-learn** – Machine learning (K-Means)


## 📂 Project Structure

Mall_Customer_Clustering/
│── mall_clustering_app.py # Main application code
│── Mall_Customers.csv # Sample dataset (replace with your own)
│── README.md # Documentation


---

## 📊 Dataset Format
The dataset should be a CSV file containing:
- **CustomerID** – Unique ID of customer
- **Gender** – Male/Female
- **Age**
- **Annual Income (k$)**
- **Spending Score (1-100)**

Example:
| CustomerID | Gender | Age | Annual Income (k$) | Spending Score (1-100) |
|------------|--------|-----|-------------------|------------------------|
| 1          | Male   | 19  | 15                | 39                     |
| 2          | Male   | 21  | 15                | 81                     |

---

## 🚀 How to Run

### 1️⃣ Install Requirements
```bash
pip install pandas numpy scikit-learn matplotlib
```
### 2️⃣ Run the Application in terminal
```bash
python mall_clustering_app.py


