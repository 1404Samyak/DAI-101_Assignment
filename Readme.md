# **Exploratory Data Analysis (EDA) Report**  

## **Project Overview**  
This project performs **Exploratory Data Analysis (EDA)** on a dataset, including:  
✅ **Data Cleaning**  
✅ **Univariate, Bivariate, and Multivariate Analysis**  
✅ **Data Visualization**  

---

## **1️⃣ Data Cleaning**  
- **Handling Missing Values**  
  - Categorical columns: Missing values replaced with the **mode** (most frequent value).  
  - Numerical columns:  
    - **Symmetric distributions** → Filled with the **mean**.  
    - **Skewed distributions with outliers** → Filled with the **median**.  
- **Date Handling**  
  - Date-related columns were split into **separate year, month, and day columns** for better analysis.  

---

## **2️⃣ Exploratory Data Analysis (EDA)**  

### **🔹 Univariate Analysis** (Single Variable)  
- **Histograms & Box Plots** were used to analyze individual feature distributions.  
- **Summary Statistics** (mean, median, mode, variance, skewness) were calculated.  

### **🔹 Bivariate Analysis** (Two Variables)  
- **Pair Plot**  
  - Displays scatter plots of all **numerical column combinations**.  
  - Also includes **univariate distributions** along the diagonal.  
- **Comparisons between categorical & numerical variables**  
  - **Bar plots, violin plots, and box plots** were used for visualization.  

### **🔹 Multivariate Analysis** (Multiple Variables)  
- **Heatmap** to show **correlations among numerical variables**.  
- **Grouped comparisons** to analyze the combined effect of multiple features.  

---

## **3️⃣ Outlier Detection & Treatment**  
- **Interquartile Range (IQR) method** was used to detect outliers.  
- Two approaches for handling outliers:  
  ✅ **Removing them** (strict cleaning).  

---

## **🔹 Conclusion**  
- The dataset was **cleaned and prepared** for analysis.  
- **EDA helped in understanding feature distributions and relationships.**  
- **Outliers were detected and treated** to improve model performance.  

---