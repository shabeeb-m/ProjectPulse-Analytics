# ProjectPulse Analytics

## Overview
ProjectPulse Analytics is a data science project that analyzes and manages project performance data for a team of project heads. Using Python, NumPy, and Pandas, it processes employee, seniority level, and project data to provide actionable insights into project costs, employee designations, and performance metrics.

## Features
- Handles missing project cost data by computing running averages.
- Splits employee names into first and last names for better organization.
- Merges employee, seniority, and project data into a unified dataframe.
- Calculates 5% bonuses for employees with finished projects.
- Adjusts designation levels based on project status (demotion for failures) and age (promotion for those over 29).
- Adds salutations (Mr./Mrs.) to names and removes gender data.
- Computes total project costs per employee.
- Filters employees by city names containing the letter "o".

## Requirements
- Python 3.x
- Libraries: `numpy`, `pandas`
- Jupyter Notebook (for `.ipynb` file execution)

## Installation
1. Clone the repository:
