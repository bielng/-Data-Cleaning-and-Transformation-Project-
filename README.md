# 🚀 Data Cleaning and Transformation Project 📊

Welcome to my **Data Cleaning and Transformation Project** repository! This project showcases a comprehensive workflow for preparing and transforming raw datasets into clean, actionable insights using **Python** and libraries like Pandas, NumPy, and Seaborn.

---

## 📝 **Project Overview**

This project demonstrates key **data cleaning and transformation** techniques through a series of assignments involving different datasets. The primary focus areas include:

- **Data Loading and Type Conversion**
- **Handling Missing Data**
- **Text Standardization**
- **Removing Duplicates**
- **Outlier Detection and Treatment**
- **Feature Engineering**
- **Datetime Operations**
- **Text Splitting and Flagging**

---

## 📂 **Repository Structure**

```
📁 Project Root
├── 📜 Alarm_Survey_Data_Pen_Sales_Data.ipynb    # Combined Jupyter Notebook for Alarm Survey and Pen Sales Datasets
├── 📜 README.md                                 # Project Documentation
├── 📂 data                                      # Folder containing datasets (not uploaded due to privacy)
│   ├── Alarm Survey Data.xlsx
│   └── Pen Sales Data.xlsx
└── 📂 images                                    # Visuals for analysis and results

```

---

## ⚙️ **Tools and Libraries**

- **Programming Language:** Python 🐍
- **Libraries Used:**
  - Pandas 🐼
  - NumPy 🔢
  - Seaborn 📊
  - Matplotlib 🎨

---

## 🛠 **Features Implemented**

### Alarm Survey Data

1. **Data Import and Inspection:**

   - Loaded Excel data into a Pandas DataFrame.
   - Checked column data types and converted `alarm_rating` and `number_of_children` to appropriate types.

2. **Handling Missing Data:**

   - Replaced missing `sleep_quality` values with a default label and numerical equivalent.

3. **Text Standardization:**

   - Fixed inconsistencies in `activity_level` (e.g., `light_activity` ➡️ "lightly active").

4. **Duplicate Removal:**

   - Identified and removed duplicate rows.

5. **Outlier Detection:**
   - Used histograms and boxplots to detect and handle extreme values in numerical columns.

---

### Pen Sales Data

1. **Feature Engineering:**

   - Created `Total Spent` using arithmetic operations.
   - Added a `Free Shipping` column using conditional logic.

2. **Datetime Operations:**

   - Calculated `Delivery Time` as the difference between `Delivery Date` and `Purchase Date`.
   - Determined the **average delivery time**.

3. **Text Splitting and Flags:**
   - Split `Review` into `User Name` and `Review Text`.
   - Flagged reviews mentioning "leak" or "spill".

---

## 🎨 **Visualizations**

Key insights were visualized using:

- **Histograms** for distribution analysis.
- **Boxplots** to identify outliers.

---

## 📈 **Future Improvements**

- Automate the cleaning process for scalability.
- Integrate more advanced outlier treatment methods.
- Use machine learning models for predictive insights post-cleaning.

---

## 🤝 **Contributions**

Feel free to fork this repository and submit pull requests. Let's collaborate and grow together! 💡✨

---

## 📬 **Contact**

- **Author:** [Taban Ngunar](https://www.linkedin.com/in/taban-ngunar-x217/)
- **Email:** [ngunartaban@gmail.com](mailto:YourEmail@example.com)
- **GitHub:** [bielng](https://github.com/bielng/Data-Cleaning-and-Transformation-Project)

---

## 🏷️ **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
