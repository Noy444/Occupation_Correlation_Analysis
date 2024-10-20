# Occupation Correlation Analysis

This repository contains Jupyter notebooks for analyzing the correlations between professional categories and various other factors such as education, gender, sleep quality and anxiety.

## Project Overview

The goal of this project is to explore how different professional categories relate to other aspects of participants' lives. Each notebook focuses on analyzing a specific correlation:

- **Occupation And Education.ipynb**: Examines the relationship between the occupation category and participants' education levels.
- **Occupation And Anxiety.ipynb**: Investigates the correlation between occupation and anxiety levels.
- **Occupation And Gender.ipynb**: Analyzes gender distribution across different occupations.
- **Occupation And Sleep.ipynb**: Studies the impact of occupation on participants' sleep quality.

## Repository Structure

Each notebook has 3 main parts:
1. **correlations plots**: Visual representations of the relationship between occupation and other factors.
2. **ANOVA test**: A statistical test to determine whether there are significant differences between groups.
3. **Tukey's test**: A post-hoc analysis to identify which specific groups differ from each other after the ANOVA test.

## Requirements

To run the analyses, you'll need the following Python packages installed:

- `pandas`
- `matplotlib`
- `seaborn`
- `scipy`

You can install the necessary dependencies with:

```bash
pip install pandas matplotlib seaborn scipy

