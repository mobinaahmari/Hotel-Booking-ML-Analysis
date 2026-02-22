
Target variable:
- `is_canceled`

To avoid **data leakage**, the following columns were removed:
- `reservation_status`
- `reservation_status_date`

Missing values were handled using:
- Filling categorical values
- Filling numeric values
- Dropping remaining null rows

---

## ⚙️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## 🤖 Machine Learning Models

### Classification Models
The following models were implemented:

- Logistic Regression  
- Decision Tree  
- K-Nearest Neighbors (KNN)

Evaluation metrics:
- Accuracy Score  
- Confusion Matrix  
- Classification Report  

---

### 📈 Clustering (K-Means)

K-Means clustering was applied to identify patterns in customer booking behavior.

Steps performed:
- Feature scaling using **StandardScaler**
- Elbow Method for selecting optimal number of clusters
- PCA visualization for dimensionality reduction

---

## 🔄 Data Preprocessing Steps

1. Removed data leakage columns  
2. Handled missing values  
3. One-hot encoding for categorical features  
4. Train-test split  
5. Feature scaling  

---

## 📊 Visualizations

The project includes:

- Elbow Method Plot  
- Cluster Scatter Plot (Lead Time vs ADR)  
- PCA Cluster Visualization  
- Cluster Distribution Bar Chart  

---

## ▶️ How to Run the Project

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
