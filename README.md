# Invoice-Anomaly-Detection
# 🧾 Invoice Anomaly Detection (Unsupervised Learning)

## 📌 Goal
The goal of this project is to detect unusual patterns in invoice submissions that could indicate fraudulent activities or errors. The system uses unsupervised learning techniques to identify anomalies in financial data.

## 🗂️ Dataset
- **Source:** (Insert your data source, e.g., "Sample invoice dataset provided here.")
- **Features:**  
    - Invoice Amount
    - Vendor Name
    - Date of Submission
    - Transaction ID
    - Other Relevant Features (Specify any additional columns)
  
## ⚙️ Techniques
- **Isolation Forest**: Detects outliers by isolating anomalies in high-dimensional data.
- **One-Class SVM**: Classifies invoice patterns as normal or anomalous.
- **Z-Score**: Identifies invoices that deviate statistically from the mean.
- **Boxplot**: Visualizes invoice distribution and highlights anomalies outside typical ranges.

## 🔬 Approach
1. **Data Preprocessing:**
   - Cleaned and standardized invoice data (amounts, dates, vendor names, etc.).
   - Handled missing values and outliers.
2. **Model Training:**
   - Applied **Isolation Forest** and **One-Class SVM** models to detect anomalies.
   - Used **Z-scores** and **Boxplots** to identify invoices outside expected behavior.
3. **Model Evaluation:**
   - Visualized results with boxplots and scatter plots for easy interpretation.
   - Flagged invoices for further review.

## 💡 Example Results
- **Outliers Detected:** 25 invoices flagged for further investigation.
- **Visualization:** Boxplot illustrating anomalies in invoice amounts.

## 📈 How to Run
### 1. Clone this repository:
```bash
git clone https://github.com/YourUsername/Invoice-Anomaly-Detection.git
