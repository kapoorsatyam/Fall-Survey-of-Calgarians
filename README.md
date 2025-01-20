# Fall-Survey-of-Calgarians

## Overview
This project analyzes survey data from the City of Calgary's **2023 Fall Survey of Calgarians** to explore citizens' opinions about the City's practices in governance and decision-making. The analysis involves exploratory data analysis (EDA), confidence interval estimation, and hypothesis testing to investigate three key survey questions.

---

## Agenda
1. Explain the purpose and motivation behind the analysis.
2. Elaborate on the dataset's reliability and data collection process, including its challenges.
3. Perform an exploratory data analysis (EDA) to visualize survey responses.
4. Conduct hypothesis testing and statistical analysis with reasoning for the findings.
5. Conclude the findings of the statistical analysis.
6. Discuss learnings from the analysis.
7. Provide relevant references.

---

## Purpose and Motivation
Surveys are essential tools for gathering public feedback, understanding citizens' needs, and informing decisions that improve their experiences. The City of Calgary conducts surveys to ensure that the voices of Calgarians are represented in policy-making and to validate that decisions reflect the needs of its residents. This analysis focuses on understanding sentiments toward the City's governance and decision-making practices, inspired by real-world examples of local government engagement.

---

## Dataset and Data Collection
The dataset used is from the **City of Calgary's 2023 Fall Survey**, conducted by Ipsos Public Affairs between August 2, 2023, and September 4, 2023. The survey features a randomly selected sample of 2,500 Calgarians aged 18 and older, collected through 60% landline and 40% cellphone responses. The dataset is statistically representative with a margin of error of ±2%.

### Key Features:
- Large, random sample ensuring diverse representation.
- Weighting based on demographics for accuracy.
- Focus on citizens' opinions regarding City governance.

### Challenges:
- Telephone surveys may exclude those who prefer other communication methods.
- Non-responses and partial answers could bias results.
- Responses to initial questions might differ in representativeness from later questions.

For more details, refer to:
- [Fall Survey of Calgarians - Newsroom](https://newsroom.calgary.ca/fall-survey-of-calgarians-shows-satisfaction-with-city/)

---

## Focused Survey Questions
The analysis focuses on three survey questions:
1. **q19_5**: The City of Calgary practices open and accessible government.
2. **q19_7**: The City allows citizens to have meaningful input into decision-making.
3. **q19_8**: The City uses input from Calgarians in decision-making about City projects and services.

Responses were grouped into two categories:
- **Agree**: Includes responses "Somewhat agree" and "Strongly agree."
- **Don't Agree**: Includes responses "Strongly disagree," "Somewhat disagree," and "Don't know/Not sure."

---

## Statistical Analysis
### Confidence Interval Estimation
Confidence intervals were computed for the population proportion of Calgarians who agree with each question.

### Hypothesis Testing
Two-sample proportion tests were performed to compare the proportions of agreement across the three questions:
1. **q19_8 vs. q19_7**: Comparison of Calgarians' agreement on using input versus meaningful input.
2. **q19_8 vs. q19_5**: Comparison of agreement on using input versus open and accessible governance.
3. **q19_7 vs. q19_5**: Comparison of meaningful input versus open and accessible governance.

---

## Learnings and Conclusions
- **EDA Insights**: Visualizations revealed the distribution and proportion of responses.
- **Confidence Intervals**: Estimations provided insights into the agreement levels with the survey questions.
- **Hypothesis Testing**: Statistical comparisons highlighted significant differences in citizens' sentiments across different aspects of governance.

