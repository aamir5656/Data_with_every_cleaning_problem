# Simple README for Data Cleaning Project

This project focuses on cleaning a dataset by addressing common data quality problems.

---

## 📁 Files

| File Name                                             | Description                                              |
|------------------------------------------------------|----------------------------------------------------------|
| Unclean_Data_with_full_Problems.csv                 | Raw data with missing values, typos, outliers, etc.     |
| Analysis.ipynb                                      | Jupyter notebook that performs the cleaning process     |
| Full_cleaned_dataset_for_prediction.csv             | Final cleaned data ready for modeling                   |

---

## 🧹 Data Cleaning Steps

1. **Handle Missing Values**
   - Replace missing numeric values with median
   - Replace missing categorical values with "Missing"

2. **Fix Spelling Mistakes**
   - Standardize category names (e.g., Pakistan vs. Pakstan)

3. **Detect and Remove Outliers**
   - Use boxplots and statistical methods (IQR, z-score)
   - Visualize using seaborn/matplotlib

4. **Encode Categorical Variables**
   - Apply Label Encoding for ordinal columns
   - Use One-Hot Encoding for nominal columns

5. **Scale Numerical Features**
   - Use RobustScaler for better handling of outliers

---

## ▶️ How to Use

1. Open `Analysis.ipynb` in Jupyter Notebook
2. Run all the cells step-by-step
3. Final cleaned dataset will be saved as `Full_cleaned_dataset_for_prediction.csv`

---

## 📞 Contact

**Developer:** Aamir Shahzad  
**Email:** your-email@example.com

---

Feel free to use or improve this project as needed!

