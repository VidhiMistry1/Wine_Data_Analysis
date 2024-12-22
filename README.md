Inspired by the diverse world of wine and its intricate variables, this analysis delves into the magnesium and alcohol content across regions.

# Wine Data Analysis

## Introduction
This repository contains an analysis of wine data focusing on magnesium and alcohol content across different regions. The analysis was carried out as part of a project for the ALY6000 Introduction to Analytics course at Northeastern University. Below is an overview of the tasks, observations, and insights obtained through this project.

---

## Project Overview

### 1. Importance of Descriptive Statistics
Descriptive statistics play a vital role in understanding and visualizing data. They simplify complex datasets into interpretable formats, reducing guesswork.

**Applications**:
- **Science and Engineering**
- **Business and Economics**
- **Healthcare**
- **Astronomy**

### 2. Applications of R in Data Analysis
- **Finance**: Used for risk management and prevention.
- **Weather Forecasting**: Predictive analysis for natural calamities.
- **Insurance**: Analyzing customer behavior and designing policies.
- **Healthcare**: Identifying disease probabilities.

### 3. Wine Industry Focus
- **Alcohol Content**: Key for taste and customer satisfaction, typically between 10% and 15%.
- **Magnesium Levels**: Affects the wine's pH and quality, depending on soil and vineyard conditions.

---

## Libraries Used
- `knitr`, `ggplot2`, `dplyr`, `tidyverse`, `readxl`, `RColorBrewer`, `magrittr`
- Visualization libraries like `lattice` for enhanced graphical representations.

---

## Tasks and Observations

### **Task 1**: Data Structure
Using `glimpse()`, the dataset's structure was examined, revealing:
- 178 rows and 14 columns.
- Variables like `Alcohol`, `Magnesium`, `Proline` as numeric, and `Wine_Type` as a character.

### **Task 2**: Renaming Variables
- `Wine_Type` was renamed to `Region`, categorized into Region 1, 2, and 3.

### **Task 3**: Alcohol Distribution
- A boxplot showed Region 3 had the highest alcohol content and variability.

### **Task 4**: Mean Alcohol Content
- **Global Mean**: 13.38.
- **Regional Mean**:
  - Region 1: 13.75
  - Region 2: 11.18
  - Region 3: 16.16

### **Task 5 & 6**: Summarization with `group_by()` and `tapply()`
- Both methods confirmed the mean alcohol levels for each region.

### **Task 7**: Region Renaming
- Region 1: California
- Region 2: Colorado
- Region 3: Massachusetts

### **Task 8**: Proline Content
- Average proline:
  - California: 1116
  - Colorado: 520
  - Massachusetts: 630

### **Task 9**: Observation Counts
- California: 59 observations.
- Colorado: 71 observations.
- Massachusetts: 48 observations.

### **Task 10**: Magnesium Classification
- **Low Magnesium** (<100): 97 observations.
- **Medium Magnesium** (100-130): 75 observations.
- **High Magnesium** (>130): 6 observations.

### **Task 11**: Magnesium Distribution by Region
- **Low Magnesium**: Colorado dominated with 53 observations.
- **Medium Magnesium**: California had the highest at 42.
- **High Magnesium**: Colorado led with 5 observations.

---

## Conclusion
The analysis revealed insights into wine consumption and preferences across regions:
- **Alcohol and Magnesium** are key factors influencing wine quality and customer preferences.
- **California** showed the highest consumption of high proline wines.
- **Colorado** preferred low magnesium wines.
- Advanced visualizations with `lattice` enhanced interpretability.

---

## References
1. Ronald Aylmer Fisher, 2009, "Descriptive Statistics." [Link](https://booksite.elsevier.com/samplechapters/9780123748485/Sample_Chapters/02~Chapter_1.pdf)
2. Miller Stephen, 2021, "What Is R Used For?" [Link](https://www.codecademy.com/resources/blog/what-is-r-used-for/)
3. Hrelia Silvana et al., 2022, "Moderate Wine Consumption and Health." [Link](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9824172/)

---

### Note
This project demonstrates the power of descriptive statistics and R programming in uncovering meaningful insights from data. Further exploration could focus on other variables like acidity or sugar levels for a comprehensive understanding of wine preferences.

