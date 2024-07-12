# Employee-Attrition-Model-For-Salifort-Motors

## Salifort Motors Employee Attrition Analysis

### Overview
This project aims to analyze and predict employee attrition at Salifort Motors using various machine learning models. The dataset contains employee information, including satisfaction levels, evaluation scores, project involvement, work hours, and more. Our goal is to identify the key factors contributing to employee attrition and build models to predict whether an employee will leave the company.

### Business Understanding
Employee attrition is a critical issue for businesses, as it can lead to increased recruitment and training costs, loss of company knowledge, and decreased morale among remaining employees. Understanding the factors that lead to employee attrition can help Salifort Motors implement effective retention strategies and improve overall employee satisfaction.

### Data Understanding
The dataset consists of employee information from Salifort Motors, with the following features:
- **satisfaction_level:** Employee satisfaction level
- **last_evaluation:** Last evaluation score
- **number_project:** Number of projects assigned
- **average_montly_hours:** Average monthly working hours
- **time_spend_company:** Years spent at the company
- **Work_accident:** Whether the employee had a work accident (1: Yes, 0: No)
- **left:** Whether the employee left the company (1: Yes, 0: No)
- **promotion_last_5years:** Whether the employee was promoted in the last 5 years (1: Yes, 0: No)
- **Department:** Department the employee belongs to
- **salary:** Salary level (low, medium, high)

### Modeling and Evaluation
A random forest model was used to determine feature importance in predicting whether employees leave the company or not. The plot below shows that in this random forest model, satisfaction_level, last_evaluation, number_project, tenure, and average monthly hours have the highest importance, in that order. These variables are most helpful in predicting the outcome variable, left.

![Feature Importance](https://github.com/user-attachments/assets/593a1bf3-5816-4a49-bdea-3b218188447c)

Overall, the model performed with:
- **Accuracy:** 98%
- **Precision:** 96%
- **Recall:** 92%
- **F1 Score:** 94%
- **AUC:** 95%

### Conclusion
The analysis provides valuable insights into the factors influencing employee attrition at Salifort Motors. Key factors include employee satisfaction, evaluation scores, number of projects, tenure, and average monthly hours. By addressing these areas, Salifort Motors can implement strategies to improve employee retention and satisfaction.
