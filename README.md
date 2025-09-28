# Employee Productivity Analysis

## Overview
This project analyzes **employee productivity** using key performance indicators (KPIs) such as working hours, technical skill scores, communication, training hours, and projects completed. The goal is to uncover patterns, visualize trends, and build a predictive model for productivity scores.  

This notebook is beginner-friendly and demonstrates how to combine **exploratory data analysis (EDA)** with **predictive modeling**.

## Dataset
- **Source:** Employee Productivity dataset (sample workforce data)
- **Key Features:**
  - `Employee_ID` – unique employee identifier
  - `Department` – department name
  - `Experience_Years` – total work experience
  - `Technical_Skill_Score` – technical competency rating
  - `Communication_Score` – communication competency rating
  - `Training_Hours` – total hours of training completed
  - `Projects_Completed` – number of projects handled
  - `Avg_Weekly_Work_Hours` – average hours worked per week
  - `Productivity_Score` – overall productivity rating
  - `Salary_USD` – annual salary

## Objectives
1. Clean and preprocess the dataset
2. Perform detailed exploratory data analysis (EDA)
3. Visualize trends and departmental performance
4. Build a predictive model for `Productivity_Score`
5. Provide actionable insights for HR and management

## Key Insights
- Productivity correlates strongly with **Technical Skill**, **Communication**, and **Projects Completed**
- Departments such as **Data Science** and **Machine Learning** show higher average productivity
- Experience and training hours positively impact productivity but are secondary to skill and project involvement
- Predictive modeling with linear regression provides reasonable estimates for productivity

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/lightonkalumba/employee-productivity-ml
