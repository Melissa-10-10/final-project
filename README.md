# final-project

# 📊 Life Expectancy Analysis in Rwanda, Uganda, Zambia, and Zimbabwe

This project analyzes and visualizes life expectancy at birth in Rwanda, Uganda, Zambia, and Zimbabwe using data from the United Nations. The final visualizations are developed in **Power BI**,
and predictive modeling is done using **Python**.

---


---

## 📖 Introduction

Life expectancy at birth is a key indicator of a population’s overall health. This project explores how life expectancy has evolved in Rwanda, Uganda, Zambia, and Zimbabwe, comparing data from the
years 2000 and 2012. Additionally, we apply linear regression to forecast life expectancy for the year 2025.

---

## 📂 Dataset Description


  ![image alt](https://github.com/Melissa-10-10/final-project/blob/cb61b8d3cfbde122274572d72f3ed4ac6216beea/extract.PNG)
   

---


- Clean and transform the raw dataset using Python.
- Perform exploratory data analysis.
   ![image alt](https://github.com/Melissa-10-10/final-project/blob/fc6b2023891a6d9f6fd06463bf19101da54d0932/describe.PNG)


-   Visualize life expectancy trends using Power BI.
  ![image alt](https://github.com/Melissa-10-10/final-project/blob/ff2bb13b600246b96dd949e10c550f48c42790ad/Screenshot%20(192).png)




---



- Python (Pandas, Matplotlib, Seaborn, Scikit-learn)
- ![image alt](https://github.com/Melissa-10-10/final-project/blob/e9c7640aefead1e24769867f39e80394e7752a86/plot%20style.PNG)
- ![image alt](https://github.com/Melissa-10-10/final-project/blob/92b46f50b4820ca113ffe159d6641c8f00324a3c/scikit.PNG)


---

## 🧹 Data Preprocessing

- Converted data types (e.g., year to int)
- Grouped by country and year
- Filtered to focus on "Both sexes" values

  ![image alt](https://github.com/Melissa-10-10/final-project/blob/a3cd297269587c81b4860e6986b3400f04ac4796/Clear.PNG)

---

## 📈 Visualization Dashboard (Power BI)

The Power BI dashboard includes:
- Bar chart comparing life expectancy across countries and years
  ![image alt](https://github.com/Melissa-10-10/final-project/blob/4ca129d1cbed8abfec2a6330a135410bc4619d3f/graph2.PNG)
- Line chart showing life expectancy trends over time
  ![image alt](https://github.com/Melissa-10-10/final-project/blob/519df3f91f91da6e3e5ae3da39e5e6f9b943fe36/graph1.PNG)

---

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

- **Name**: Sangwa Kamanzi Melissa
- **Course**: Introduction to Big Data Analytics (INSY 8413)

---

