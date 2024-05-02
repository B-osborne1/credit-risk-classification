# credit-risk-classification

This Repo utilises supervised machine learning to classify whether instances of loan applications should be classified as 'high-risk' or not. The data includes information such as debt/loan-size, interest rate and income. The loan_status column is treated as the column of interest (y), and seperated from the main DF. With a 75/25 split, the data is trained and confusion matrices and classification reports are conducted. 
In-line analysis of the code is included, however, a summary can also be found below:

---------------------------------------------------------------

Analysis of borrowers credit-risk:

Aim: To train a dataset to determine if a loan applicant should be considered as a low-risk or high-risk investment. 
Purpose/benefit: To reduce company loss through rejecting, or provding alternatatives, to high-risk loan applicants.

Breakdown of results:
- Training set had a 99% accuracy of a correct response. Of that, 99% of low-risk were accurately predicted, while 90% of high-risk were accurately predicted. The precision of low-risk was at 100%, while at 85% for the high-risk
- When moving to the test set, results showed a slightly higher result across the set. Accuracy remained at 99%, while precision raised 3% for high-risk cases, and recall by 1%

Overall:
- Overall, the training set has been able to predict with reasonably high accuracy the characteristics that define what make a high risk applicant. While not infallible, this model could used to assist with business decisions