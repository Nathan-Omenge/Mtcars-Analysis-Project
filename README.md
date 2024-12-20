
# Mtcars Dataset: Statistical Analysis and Visualization

This project documents the solutions and analysis for the mid-semester exam using R programming. The tasks focus on exploring data, performing statistical analysis, and creating visualizations to derive meaningful insights.

---

## **Tasks Performed**

### 1. **Exploratory Data Analysis (EDA)**
   - **Dataset:** Used the `mtcars` dataset for analysis.
   - **Key Functions:**
     - `summary()`: Provided a statistical summary of the dataset, including mean, median, and quartiles.
     - `str()`: Displayed the structure of the dataset, including variable names, data types, and observations.
   - **Objective:** Gain insights into the overall data distribution and relationships.

---

### 2. **Scatter Plot with Regression Line**
   - **Purpose:** Analyzed the relationship between `horsepower (hp)` and `miles per gallon (mpg)`.
   - **Visualization Tool:** `ggplot2`
   - **Key Features:**
     - Scatter plot of `hp` vs. `mpg`.
     - Added a linear regression line to understand trends in the data.
     - Custom labels and themes for clarity.

---

### 3. **Categorical Data Analysis**
   - **Focus:** Distribution of the `cylinders (cyl)` variable.
   - **Visualization:**
     - Created a bar chart to visualize the count of cars with different cylinder configurations (`4`, `6`, `8`).
   - **Purpose:** Highlight the frequency distribution of cylinder categories in the dataset.

---

### 4. **Correlation Analysis**
   - **Method:** Generated a correlation heatmap of numerical variables.
   - **Tool Used:** `heatmaply`
   - **Purpose:** Identify strong positive or negative correlations between features (e.g., `hp`, `mpg`, `wt`, etc.).

---

### **Files in the Repository**

1. **Mid-Semester-Exam.Rmd**: R Markdown file containing the analysis and code for all tasks.
2. **Mid-Semester-Exam.html**: Pre-generated HTML output showcasing the results and visualizations.

---

## **How to Use**

### Prerequisites:
- Install R and RStudio.
- Install the following R libraries:
  ```R
  install.packages(c("ggplot2", "dplyr", "heatmaply"))
