# loan-applications

The objective of this project is to practice using different machine learning libraries and methods to take a deeper look at loan applications. More specifically, the true purpose of the assignment is to practice using different types of machine learning models and see what the benefits and consequences of using each are. To this extent, this project ends up taking a large role of importance, for its size, as its educational role takes precedence over the findings.
Below are the questions we set out to answer from the CSV data obtained from Kaggle:
1. Does being a graduate make a difference in getting approved?
2. Does being Self Employed make a difference?
3. Does the avg no of dependents make a difference in getting approved?
4. Does the total assets affect loan approval?
5. Does the income to loan amount ratio affect the likelihood of an application’s approval?
6. What will the majority of approved loans be in the future?

The libraries used for this assignment are pandas, tensorflow, and scikit-learn. After organizing and splitting the data, we attempted to use three different models for predicting the success of loan applications based on their qualifications. Our initial model had an accuracy of 60%, making us fairly sure that we should either tweak this model or try using a different method. To assess this, we instantiated and resampled the model, resulting in a worse model with 55% predicted accuracy. Finally we changed up our approach and created a neural network model. Our final fits and tests provided an accuracy score of 99%.

To find further visualizations of our findings (and answers to the questions above), please visit the following link which will take you to our tableau presentation.

https://public.tableau.com/app/profile/herbert.spektor/viz/LoanStory_16932640162860/LoanApplicationStory?publish=yes
