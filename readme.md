# Data Analysis and Visualization Project

---

## Overview

This project involves two main tasks: extracting and analyzing CSV data, and exploring mental health data. The work showcases various data manipulation techniques, correlation calculations, hypothesis testing, and visualization skills using Python libraries.

---

## Task 1: Extracting and Analyzing CSV Data

### Approach:

1. **Reading a Single Column (FR1):**
    - Utilized the `open` function to read a single column from a CSV file.
    - Handled the header separately and stored column values in a list.
    - Managed potential 'out of index' errors for invalid column indices.

2. **Reading CSV Data into Memory (FR2):**
    - Implemented a loop to read all columns into a dictionary.
    - Utilized the `read_a_column` function, continuing until an IndexError indicated no more columns.

3. **Calculating Kendall Tau Correlation (FR3):**
    - Created a function to handle lists of different lengths and calculate concordant and discordant pairs.

4. **Generating Kendall Tau Correlations (FR4):**
    - Developed a function to compute Kendall Tau Correlation Coefficients for all column pairs.
    - Minimized redundant calculations and stored results efficiently.

5. **Printing a Custom Table (FR5):**
    - Designed a function to print a custom table of correlation coefficients.
    - Applied string-building techniques for enhanced formatting and clear presentation.

### Reflection:

- **Thought Process:** Initial challenges gave way to a streamlined process with efficient functions.
- **Strengths:** Efficient looping solutions and comprehensive error handling.
- **Weaknesses:** Manual data processing could be less efficient for larger datasets.
- **Improvements:** Consider exploring alternative libraries for optimized CSV handling.

---

## Task 2: Exploring Mental Health Data

### Approach:

1. **Merging Data (FR6):**
    - Merged data from two CSV files using the pandas library.
    - Efficiently read and merged based on specified columns.

2. **Exploring the Dataset (FR7):**
    - Conducted thorough exploration using `describe` and `info` methods.
    - Analyzed patterns and generated a correlation table, focusing on high correlations between 'eating disorders' and 'bipolar disorder.'
    - Investigated individual countries over time for detailed insights.

3. **Detecting and Removing Outliers (FR8):**
    - Employed the Z-score method for outlier detection.
    - Grouped data based on correlation criteria to remove potential outliers.

4. **Defining a Hypothesis (FR9):**
    - Formulated a hypothesis expecting a high correlation between 'eating disorders' and 'bipolar disorder,' based on observed patterns.

5. **Testing the Hypothesis (FR10):**
    - Executed a one-sample t-test to determine if the correlation was at least greater than 0.4.
    - Findings highlighted the need for caution in making overarching statements about correlations due to dataset diversity.

### Reflection:

- **Thought Process:** Streamlined with the use of pandas; correlation analysis provided valuable insights.
- **Strengths:** Efficient use of libraries; detailed outlier analysis.
- **Weaknesses:** Hypothesis formulation could benefit from more nuanced considerations.
- **Improvements:** Explore additional hypothesis testing methods for a more comprehensive analysis.

---

## Conclusion

This exploration emphasized methodical approaches in data science, highlighting the importance of evidence-backed insights, judicious library use, and the continuous quest for nuanced understanding. The project demonstrates proficiency in Python, data manipulation, statistical analysis, and data visualization, providing a solid foundation for future work in data science and analytics.
