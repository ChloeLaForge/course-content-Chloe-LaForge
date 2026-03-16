##Summary
This project analyzes how universities differ in performance across a variety of ranking categories while determining how these differences contribute to their overall score. Comparative ranking features apply regression modeling to assess the relationship between performance in a specific category with overall outcomes. To validate these results, a Random Forest Model shows which factors are more important determinants in predicting a university’s score. Raw data has a wide variance, including meaningful outliers, which were kept to best represent real-world differences between universities. The dataset includes several ranking categories, such as (but not limited to) teaching, research quality, research environment, industry impact, and student-to-staff ratio. 

##Reproduction
​​To reproduce the analysis and figures presented in the final project paper, follow the steps below. 

### System Requirements
This project was developed in Colab using Python.

### Data Availability
The raw open-source data used is a publicly available dataset from Kaggle called THE World University Rankings 2016-2026. This complete dataset features data on more than 1,500 universities worldwide and was compiled using metrics from the Times Higher Education.


##Execution steps
Data preparation and exploration
Determine distribution, mean, and median values of key variables
Determine number of outliers in numerical columns
Apply min-max normalization where necessary
Feature Engineering 
Develop two new variables
Teaching score per student
Research quality score per student 
Convert performance categories into ranks
Analysis 
Build two models
Logistic Regression
Random Forest
Analyze model performance
Scatter plots comparing actual versus predicted values.
Calculate mean-squared error and R-squared metrics
