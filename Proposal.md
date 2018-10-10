# Finalproject


Problem: The tax company I work for has very limited understanding on what drives IRS funding likelihood, which is very important, because IRS funding is what ultimately dictates whether our clients are able to pay for the services they received. This lack of understanding makes projecting company performance very difficult, particularly regarding company revenue projections and forecasts. 

Hypothesis: I believe there are certain characteristics embedded within each customer’s tax return information which can be used to identify and score each client’s likelihood of receiving IRS funding. There is also potentially metadata that can be used to help enrich this IRS funding likelihood score. 

Goal: Create a logistic regression that ingests all available tax return information and certain metadata in order to create an IRS funding likelihood score.

Success Metrics:
1.	Model will be able to score IRS funding likelihood more accurately than a simple average.
2.	Model will be able to score IRS funding likelihood more accurately than simple demographic information.
3.	Model estimates will accomplish steps (1) and (2) above during the 2019 tax season (based solely on the 2018 tax season dataset).

Risks/Limitations:
1.	It is very possible -- and likely -- that there are important risk-factors that are not observed and not available from a tax return. Without these important risk-factors, the model’s explanatory power may be hindered.
2.	It is possible that the behaviors observed during the 2018 tax season (which will be used to create the model) may not occur similarly for the 2019 tax season, causing the model to perform poorly.

Dataset: I have access to a dataset with large amounts of demographic information and tax information, which will be scrubbed for all personal contact information. Additionally, the dataset will have non-explanatory variable names, in order to prevent persons outside of the company from understanding what each variable actually represents. Lastly, categorical variable values will be converted into non-explanatory values, also in order to prevent persons outside the company from understanding each variable. This scrubbing should have no impact on the model’s performance. However model results will not be intuitive, since all the variable names will be non-explanatory. This scrubbing is necessary for me to use the company’s dataset for this project.
