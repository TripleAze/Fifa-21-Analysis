
---

# **FIFA 21 Dataset Analysis Project**

This project analyzes the **FIFA 21 dataset** to explore player attributes, market values, and potential growth patterns using Python. The analysis includes data cleaning, feature engineering, exploratory data analysis (EDA), and predictive modeling to extract valuable insights into player performance and value.

---

## **Dataset**  
The dataset is sourced from **Kaggle's FIFA 21 dataset**.

---

## **Project Objectives**  
- **Clean** and preprocess the dataset, including handling missing values, duplicates, and data types.  
- **Analyze** player attributes like age, overall rating, and market value.  
- **Explore** the relationship between age, potential, overall rating, and market value.  
- **Identify** underrated players with a high potential gap.  
- **Predict** market value using linear regression and evaluate model performance.  
- **Visualize** insights using various plots and graphs.

---

## **Project Workflow**

### **Data Cleaning**:  
- Dropped irrelevant columns  
- Removed duplicates  
- Standardized data formatting (e.g., converting height, weight, and currency data)  
- Extracted and converted date information from the "Joined" column.

### **Exploratory Data Analysis (EDA)**:  
- **Correlation Heatmap**: Analyzed correlations between numeric attributes.  
- **Best Players by Position**: Identified top players in each position.  
- **Age vs. Performance**: Visualized relationships between age and overall rating/potential.  
- **Underrated Players**: Identified players with high potential but low current overall ratings.  
- **Market Value vs. Overall Rating**: Explored the relationship between market value and performance.

### **Predictive Modeling**:  
- Built a **linear regression model** to predict player market value using attributes like overall rating, potential, and age.  
- Evaluated the model's performance using **mean squared error (MSE)** and log transformation.

---

## **Key Insights**  

- **Player Attribute Correlations**: Certain attributes, like dribbling, shooting, and pace, are highly correlated with the overall rating, affecting player performance.  
- **Best Players by Position**: Top players in positions like RW (Right Wing) and ST (Striker) show a significant impact on the team.  
- **Age vs. Performance**: Younger players often have higher potential, while older players peak in overall rating around ages 28–30.  
- **Underrated Players**: Some players show significant growth potential despite low overall ratings, offering good investment opportunities.  
- **Market Value vs. Overall Rating**: A positive relationship between market value and overall rating was observed, with some notable outliers.  
- **Predictive Modeling**: The linear regression model predicts market value with an MSE of [insert value]. The model can be improved by including additional features or transforming data.

---

## **Visualizations**

- **Correlation Matrix**: Heatmap to show relationships between numeric player attributes.  
- **Age vs. Overall Rating**: Scatter plot comparing player age to overall rating.  
- **Age vs. Potential**: Scatter plot comparing age to potential rating.  
- **Underrated Players**: Scatter plot and table identifying players with the highest potential gaps.  
- **Market Value vs. Overall Rating**: Scatter plot showing the relationship between market value and overall rating.  
- **Top Nationalities**: Bar chart visualizing the top nationalities by player count.  
- **Wage vs. Performance**: Scatter plot of wage against overall rating.  
- **Average Market Value by Age**: Line plot of average market value by age group.  
- **3D Plot**: Visualize the relationship between overall rating, potential, and age against market value.

---

## **Dependencies**

- **Python 3.x**  
- **Pandas**  
- **Matplotlib**  
- **Seaborn**  
- **Scikit-learn**  
- **NumPy**

---

## **How to Run**  
1. **Clone the repository**:  
   ```bash
   git clone <repository-url>
   ```

2. **Install dependencies**:  
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter notebook or script** to view the analysis and results.

---

