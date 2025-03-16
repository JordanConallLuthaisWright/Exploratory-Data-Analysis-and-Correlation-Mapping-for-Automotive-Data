# Automotive Data Analysis: Correlation Mapping and Feature Engineering for Pattern Recognition

This project focuses on performing **Exploratory Data Analysis (EDA)** and **correlation mapping** on an automotive dataset to uncover relationships between different vehicle attributes. The analysis leverages **feature engineering, data preprocessing, and advanced visualization techniques** to extract meaningful insights.

---

## Project Aim  
The goal of this project is to analyze automotive data and identify key **correlations between numerical features**. The study provides insights into **vehicle performance, pricing factors, and attribute dependencies**, which can be useful for **predictive modeling, pricing strategies, and feature selection** in machine learning applications.

---

## Technical Skills Demonstrated  
- **Data Preprocessing & Feature Engineering**: Encoding categorical variables and selecting numerical features.  
- **Exploratory Data Analysis (EDA)**: Visualizing **data distributions, trends, and patterns**.  
- **Correlation Mapping**: Using **Pearson’s correlation coefficient** and heatmaps to analyze relationships between vehicle attributes.  
- **Data Visualization**: Implementing **Seaborn heatmaps and scatter plots** to interpret complex feature interactions.  

---

## Files in This Repository  
| File | Description |
|------|------------|
| `Automotive_Data_Analysis_Correlation_Feature_Engineering.ipynb` | Jupyter Notebook containing the full analysis workflow. |
| `autos.clean.csv` | Dataset used for the analysis. |

---

## How to Run This Project  
1. **Clone the repository**  
   ```bash
   git clone https://github.com/JordanConallLuthaisWright/Exploratory-Data-Analysis-and-Correlation-Mapping-for-Automotive-Data.git
   ```
2. **Navigate to the project directory**
   ```bash
   cd Exploratory-Data-Analysis-and-Correlation-Mapping-for-Automotive-Data
   ```
3. **Install dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
4. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```
5. Open and run `Exploratory Data Analysis and Correlation Mapping for Automotive Data.ipynb`

---

## Business Scenario  
This project investigates key relationships between **automobile characteristics and pricing factors**, helping to answer questions such as:

- **Which vehicle attributes are most correlated with price and performance?**  
- **How does engine size impact fuel efficiency and horsepower?**  
- **Which attributes are crucial for predictive modeling in automotive pricing?**  

By understanding these correlations, **car manufacturers, analysts, and dealerships** can make **data-driven decisions** about **pricing strategies, vehicle design, and consumer preferences**.

---

## Methodology & Technical Implementation  

### 1. Data Preprocessing & Feature Engineering  
- **Encoded categorical variables** using **Label Encoding** to enable correlation analysis.  
- **Filtered numerical features** to retain only relevant data for correlation computation.  
- **Normalized and cleaned dataset** to remove inconsistencies and missing values.  

### 2. Exploratory Data Analysis (EDA)  
- **Created visualizations** using **histograms, scatter plots, and summary statistics**.  
- **Identified outliers** and explored feature distributions.  

### 3. Correlation Mapping  
- **Computed Pearson’s correlation coefficient** to evaluate feature relationships.  
- **Generated heatmaps using Seaborn** to highlight **positive and negative correlations**.  
- **Visualized dependencies** between key features such as **horsepower, engine size, fuel efficiency, and price**.  

### 4. Key Findings & Insights  
- **Strong correlations** were observed between **engine size, horsepower, and price**, highlighting their influence on vehicle performance.  
- **Fuel efficiency (city-mpg and highway-mpg) showed an inverse correlation with engine size and weight.**  
- **Correlation mapping proved valuable for feature selection in machine learning models.**  

---

## Key Learnings & Applications  
This project reinforced the importance of:  

- **Feature Engineering**: Proper encoding and selection of variables improve model interpretability.  
- **Correlation Visualization**: Heatmaps provide a **clear, data-driven understanding of feature dependencies**.  
- **Data-Driven Decision Making**: The insights gained from this study can be **applied beyond automotive analytics**, including **finance, healthcare, and retail** industries.  

### **Potential Future Work:**  
- **Outlier detection and removal** for cleaner data analysis.  
- **Regression modeling** to predict vehicle pricing.  
- **Advanced statistical techniques** for deeper insight extraction.  

---

## **Contact & Contributions**  
Feel free to explore and contribute. If you have any suggestions, reach out or submit a pull request.  

- **Email**: [jordan.c.l.wright@gmail.com](mailto:jordan.c.l.wright@gmail.com)  
- **Author**: Jordan  
- **GitHub Profile**: [JordanConallLuthaisWright](https://github.com/JordanConallLuthaisWright)
