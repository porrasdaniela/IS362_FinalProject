# Final Project: Screen Time Among Children in New York

📊 **Daniela Porras**   
📁 **IS 362 - Data Analysis & Visualization**  
🗓️ **Spring 2025**

## 🧠 Project Overview

This project analyzes how much time children in New York State spend in front of screens on weekdays (excluding schoolwork), using data from the 2022–2023 National Survey of Children's Health (NSCH). The analysis focuses on three age groups: 0–5, 6–11, and 12–17 years old.

As a parent, I was personally motivated to explore how screen time evolves with age and whether the data supports common parental concerns. To enrich the analysis, I also included qualitative insights from Pew Research Center's 2020 report on parenting in the digital age.

---

## 📌 Objectives

- Identify average screen time by age group
- Use statistical aggregation to compare screen habits
- Visualize results using bar charts
- Use a word cloud to explore common parental sentiments on screen time
- Highlight any correlation between age and screen time habits

---

## 📊 Data Sources

1. **NSCH 2022–2023** (childhealthdata.org)  
   - Manually extracted chart data into a DataFrame for analysis  
   - Age groups vs. time spent in front of screens

2. **Pew Research Center Report**  
   - ["Parenting Children in the Age of Screens"](https://www.pewresearch.org/internet/2020/07/28/childrens-engagement-with-digital-devices-screen-time/)  
   - Used to generate a word cloud for qualitative sentiment analysis

---

## 🔁 Workflow

1. **Data Entry**: Manually entered percentages from NSCH chart  
2. **Transformation**: Converted wide data to long format using `pandas.melt()`  
3. **Aggregation**: Calculated weighted average screen time for each group  
4. **Visualization**:
   - Bar chart of screen time by age
   - Word cloud from Pew sentiment excerpts  
5. **Analysis**: Drew conclusions based on trends in numeric and textual data

---

## 📦 How to Run This Notebook

To ensure the notebook runs without errors, make sure to install the following dependency if not already installed:

```python
!pip install wordcloud
