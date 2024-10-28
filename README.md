# 📊 **PyCity Schools District Analysis**

## **Project Overview**
Welcome to the **PyCity Schools District Analysis**! Imagine stepping into the role of a data-driven education strategist tasked with uncovering insights across a district of over 39,000 students. How do budget allocations, school size, and type influence student success? This project dives into the data, revealing factors that shape academic outcomes and highlight areas for improvement.

Using a combination of school and student data, the analysis reveals patterns in average math and reading scores, passing rates, and overall academic performance metrics across the PyCity School district. 

## **Key Insights**

### 🔍 **What Did We Discover?**
1. **Smaller Schools, Stronger Performance**  
   Small schools, defined as those with fewer than 1,000 students, show the highest passing rates, nearly 90% overall. This trend suggests that a more personalized, small-scale environment could play a key role in student achievement.

2. **Charter vs. District Schools: A Surprising Gap**  
   Charter schools significantly outperform District schools, with nearly double the passing rates. This finding raises questions about best practices within Charter schools that, if adapted, could benefit District schools.

3. **Spending Per Student: Less Is More?**  
   Interestingly, lower spending per student (under $585) correlates with higher passing rates. This counterintuitive result suggests that lower spending may encourage efficiency or targeted support structures worth investigating.

## **Project Structure**

### 📂 **Files and Structure**

- **Data Files**  
  - `schools_complete.csv`: Contains school-specific information, such as budget and type.
  - `students_complete.csv`: Provides individual student performance data.

- **Jupyter Notebook**  
  - `py_city_schools.ipynb`: The heart of the analysis, featuring data cleaning, aggregation, and visualizations. Each section includes calculations and visual representations to capture insights at both district and school levels.

### 🧩 **Analysis Breakdown**

1. **District Summary**  
   An overview of total schools, students, budget, and performance averages for math and reading scores.

2. **School Performance Summary**  
   Detailed performance metrics for each school, including budget per student, average scores, and passing rates by subject.

3. **Impact of Spending, Size, and Type**  
   Insights into how different spending ranges, school size, and type influence academic performance.

## **Quick Start Guide**

### 🚀 **Getting Started**
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/pycity_schools_analysis.git
   cd pycity_schools_analysis

2. **Set Up Dependencies**
- Ensure pandas is installed:
   ```bash
   pip install pandas

3. **Run the Jupyter Notebook**
- Open py_city_schools.ipynb in Jupyter Notebook or JupyterLab, and execute each cell sequentially to complete the analysis:
   ```bash
   jupyter notebook py_city_schools.ipynb

### ⚙️ **Modify Parameters**
To explore further, consider adjusting:

Spending Bins: Customize spending ranges to see how different budget allocations influence outcomes.
School Size Ranges: Change the size bins to examine performance across alternative groupings.
Additional Groupings: Add new dimensions to uncover unique trends within the data.

**Conclusions and Next Steps**
Findings show that smaller schools and Charter schools contribute significantly to higher academic performance in the PyCity district. With these insights, district leaders can focus on resource allocation, study effective practices from Charter schools, and prioritize more personalized learning environments to benefit student outcomes.

### **Requirements**
Python Libraries: pandas
Environment: Jupyter Notebook or JupyterLab
