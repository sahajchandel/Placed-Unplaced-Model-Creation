# Placed Unplaced Model

![Project Banner](https://img.freepik.com/free-photo/front-view-young-beautiful-lady-red-t-shirt-black-jeans-holding-different-copybooks-files-smiling-with-bag-white_140725-18639.jpg?w=1060&t=st=1694343443~exp=1694344043~hmac=29e6d73ad86d51b72dc98f4e5d617cbff6c54ab3148d2bb0c3d2d121200f68e0)

## Introduction

Welcome to the Placed Unplaced Model project! This machine learning project aims to predict whether a student will be placed or not based on various features. We've conducted a comprehensive analysis and built different machine learning models to achieve this goal. In this README, you'll find an overview of the project, its features, data analysis, preprocessing, data visualization, machine learning models used, and a conclusion summarizing our findings.

## Features

The dataset includes the following columns:

- 'sl_no': Serial Number
- 'gender': Gender of the student
- 'ssc_p': Secondary Education percentage (10th Grade)
- 'ssc_b': Board of Education for 10th Grade
- 'hsc_p': Higher Secondary Education percentage (12th Grade)
- 'hsc_b': Board of Education for 12th Grade
- 'hsc_s': Specialization in Higher Secondary Education
- 'degree_p': Degree percentage
- 'degree_t': Type of Undergraduate Degree
- 'workex': Work Experience ('Yes' or 'No')
- 'etest_p': E-test percentage
- 'specialisation': MBA Specialization
- 'mba_p': MBA percentage
- 'status': Placement Status ('Placed' or 'Not Placed')
- 'salary': Salary offered (if placed)

## Data Analysis

- The average Secondary Education percentage (10th Grade) is 67.30%.
- There are 148 students who are placed, and 67 students who are not placed.
- The most common degree among placed students is 'Comm&Mgmt' with XXX students.

## Data Preprocessing

Before training our machine learning models, we identified and removed unnecessary columns.

## Data Visualization

We created a scatter plot between 10th and 12th-grade percentages with labels and titles.

![Scatter Plot](insert_scatter_plot_image_url_here)

## Machine Learning Models

### Linear Regression

- Extracted dependent and independent variables.
- Standardized the data.
- Performed Linear Regression.
- The intercept of the linear regression model is -64884.547827187576.
- Evaluated the model using Mean Squared Error (MSE): 93241647311.78693

### Decision Tree

- Extracted dependent and independent variables.
- Moving towards Decision Tree modeling.

### Random Forest

- Imported necessary libraries.
- Extracted dependent and independent variables.
- Moving towards Random Forest modeling.

### Logistic Regression

- Extracted independent and dependent variables.
- Used standardization.
- Built the Logistic Regression model.

## Conclusion

In this project, we analyzed a dataset containing information about students and their placement status. After data preprocessing, we explored various machine learning models, including Linear Regression, Decision Tree, Random Forest, and Logistic Regression.

Linear Regression produced an MSE of 93241647311.78693, indicating its predictive performance. Decision Tree and Random Forest models are being explored and will provide insights into their effectiveness shortly. Logistic Regression is another potential model for predicting student placement.

Overall, this project demonstrates the application of machine learning techniques to predict student placement based on various factors. Further analysis and model tuning may improve predictive accuracy.

## Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn


