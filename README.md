# final-project

# 📊 Life Expectancy Analysis in Rwanda, Uganda, Zambia, and Zimbabwe

This project analyzes and visualizes life expectancy at birth in Rwanda, Uganda, Zambia, and Zimbabwe using data from the United Nations. The final visualizations are developed in **Power BI**,
and predictive modeling is done using **Python**.

---

## 📌 Table of Contents

- [Introduction](#introduction)
- [Dataset Description](#dataset-description)
- [Objectives](#objectives)
- [Tools Used](#tools-used)
- [Data Preprocessing](#data-preprocessing)
- [Visualization Dashboard (Power BI)](#visualization-dashboard-power-bi)
- [Predictive Analysis](#predictive-analysis)
- [Conclusion](#conclusion)
- [Screenshot](#screenshot)
- [Author](#author)

---

## 📖 Introduction

Life expectancy at birth is a key indicator of a population’s overall health. This project explores how life expectancy has evolved in Rwanda, Uganda, Zambia, and Zimbabwe, comparing data from the
years 2000 and 2012. Additionally, we apply linear regression to forecast life expectancy for the year 2025.

---

## 📂 Dataset Description

- **Source**: United Nations / UNICEF
- **Format**: `.csv` converted from Excel
- **Columns**:
  - `Country`: Rwanda, Uganda, Zambia, Zimbabwe
  - `Year`: 2000 and 2012
  - `Gender`: Male, Female, Both
  - `Life Expectancy`: Number of years
  ![image alt](https://github.com/Melissa-10-10/final-project/blob/cb61b8d3cfbde122274572d72f3ed4ac6216beea/extract.PNG)
   

---

## 🎯 Objectives

- Clean and transform the raw dataset using Python.
- Perform exploratory data analysis.
   ![image alt](https://github.com/Melissa-10-10/final-project/blob/fc6b2023891a6d9f6fd06463bf19101da54d0932/describe.PNG)


-   Visualize life expectancy trends using Power BI.
  ![image alt](https://github.com/Melissa-10-10/final-project/blob/79f0f280fca0951f22889f6e28524c2d8fb6777d/graph1.PNG)

- Predict life expectancy in 2025 using linear regression.


---

## 🛠️ Tools Used

- Python (Pandas, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook
- Power BI Desktop
- GitHub for version control and presentation

---

## 🧹 Data Preprocessing

- Removed unnecessary columns (`Value Footnotes`)
- Converted data types (e.g., year to int)
- Grouped by country and year
- Filtered to focus on "Both sexes" values
- Exported cleaned data and prediction results to `.csv` for Power BI use

---

## 📈 Visualization Dashboard (Power BI)

The Power BI dashboard includes:
- Bar chart comparing life expectancy across countries and years
- Line chart showing life expectancy trends over time
- Card displaying predicted life expectancy in 2025
- Slicer for dynamic filtering by year or country

---

## 🖼️ Screenshot

> 🔽 **Insert your Power BI dashboard image below**
> Upload the image in GitHub and replace the link below:

![Power BI Dashboard Screenshot](https://github.com/yourusername/yourrepo/blob/main/dashboard.png)

---

## 📊 Predictive Analysis

A simple linear regression model was trained using `Year` as the independent variable and `Life Expectancy` as the dependent variable. The model predicted the life expectancy in the year 2025 for each country.

Example prediction:

| Country  | Year | Predicted Life Expectancy |
|----------|------|----------------------------|
| Rwanda   | 2025 | 73                         |
| Uganda   | 2025 | 64                         |
| Zambia   | 2025 | 64                         |
| Zimbabwe | 2025 | 65                         |

---

## ✅ Conclusion

This project demonstrates how health-related data can be cleaned, analyzed, and visualized using both Python and Power BI. The visual insights and predictive model can support policy planning and further investigation into health outcomes in East and Southern Africa.

---

## 👤 Author

- **Name**: Kamanzi Mely
- **Course**: Introduction to Big Data Analytics (INSY 8413)
- **Institution**: [Insert Your Institution]
- **Supervisor**: [Insert Supervisor Name, if applicable]

---

