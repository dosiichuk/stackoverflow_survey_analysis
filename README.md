# Developer Salary Analysis

This repository contains a Jupyter Notebook that analyzes factors associated with developer salaries using data from the Stack Overflow 2023 Developer Survey. The analysis explores various questions to understand how different factors influence compensation in the tech industry.

## ATTENTION! Before running the analysis, you need to download the source data from the link indicated below and put the unpacked file called survey_results_public.csv into this project folder.

## Questions Addressed
1. **Is there a premium to a formal degree?**
   - Analyzes whether higher education levels (e.g., bachelor's, master's, or PhD) are associated with higher salaries.

2. **Is there a premium to working in a larger company?**
   - Investigates whether developers working in larger organizations earn more compared to those in smaller companies.

3. **Is there a premium for longer experience?**
   - Examines the relationship between years of professional coding experience and compensation.

4. **Is there a premium to using AI?**
   - Explores whether developers who use AI tools in their work earn more than those who do not.

## Methodology
- The analysis uses descriptive statistics (mean and median salaries) to compare groups based on the factors above.
- Statistical tests are conducted to determine whether observed differences are significant.
- A regression model is built to predict developer compensation based on these factors.

## Key Findings
- The analysis provides insights into the premiums (or lack thereof) associated with education, company size, experience, and AI usage.
- **Spoiler:** The regression model has poor explanatory power, indicating that these factors alone do not fully explain variations in developer salaries.

## How to Use
1. Clone this repository.
2. Open the Jupyter Notebook in your preferred environment (e.g., JupyterLab, VS Code, or Anaconda).
3. Run the cells to reproduce the analysis and explore the results.

## Data Source
The data used in this analysis comes from the [Stack Overflow Developer Survey 2023](https://survey.stackoverflow.co/datasets/stack-overflow-developer-survey-2023.zip).

## Requirements
- Python 3.7+
- Jupyter Notebook
- Required libraries: `pandas`, `numpy`, `seaborn`, `matplotlib`, `scikit-learn`, `shap`

## Disclaimer
This analysis is for educational purposes and may not capture all factors influencing developer salaries. The findings should be interpreted with caution.