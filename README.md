# Developer Salary Analysis

This repository contains a Jupyter Notebook that analyzes factors associated with developer salaries using data from the Stack Overflow 2023 Developer Survey. The analysis explores various questions to understand how different factors influence compensation in the tech industry.

The findings are presented in the form of a blog post here [link](https://medium.com/@just-some-thoughts/what-really-moves-programmer-pay-seven-data-driven-answers-62ab46a45752)

## ATTENTION! Before running the analysis, you need to download the source data from the link indicated below and put the unpacked file called survey_results_public.csv into this project folder. You can download the data here [link](https://survey.stackoverflow.co/datasets/stack-overflow-developer-survey-2023.zip) and then put it into the project folder. It is too large to fit in a repo.

## Questions Addressed
1. **What is the role of organization size in shaping compensation?**
   - Investigates whether there is a premium to working in larger companies by analyzing mean and median salaries across different organization sizes.

2. **Is there a discount attached to remote work?**
   - Examines whether remote workers earn less compared to in-office workers and explores the relationship between remote work and compensation.

3. **Is there a premium for experience and how much is it?**
   - Analyzes the relationship between years of professional coding experience and salary, including the average premium for each additional year of experience.

4. **What is the premium attached to advanced educational degrees (Bachelor, Master)?**
   - Explores whether higher education levels (e.g., bachelor's, master's, or PhD) are associated with higher salaries.

5. **Does the use of AI tools contribute to higher compensation?**
   - Investigates whether developers who use AI tools in their work earn more than those who do not.

6. **Is there a relationship between the variety of languages a developer worked with and their compensation?**
   - Analyzes whether the richness of experience, defined as the number of programming languages a developer has worked with, correlates with higher salaries.

7. **Can developer salaries be predicted using the above factors?**
   - Builds a regression model to predict developer compensation based on factors such as years of experience, organization size, education level, country, and type of work.


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