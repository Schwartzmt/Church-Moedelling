# Church-Moedelling
VARIABLES
RowNumber: a unique identifier for each record.
CustomerId: a unique identifier for each customer.
Surname: surname of the customer.
CreditScore: credit score of the customer.
Geography: country of the customer.
Gender: gender of the customer.
Age: age of the customer.
Tenure: number of years for which the customer has been with the bank.
Balance: balance in the customer's account.
NumOfProducts: number of bank products the customer is using.
HasCrCard: indicates whether the customer has a credit card (1) or not (0).
IsActiveMember: indicates whether the customer is an active member (1) or not (0).
EstimatedSalary: estimated salary of the customer.
Exited: indicates whether the customer has exited the bank (1) or not (0).
Descriptions
EDA_and_logistic_efficient.ipynb |

The code first loads the data into a Pandas dataframe and performs some basic EDA operations such as checking missing values, statistical summary, distribution of target column, and correlation matrix.
Then it encodes the categorical features and concatenates the encoded features with the original data.
Finally, it splits the data into training and testing sets and fits a Logistic Regression model on the training data. It then predicts the target on the test data and evaluates the model using the confusion matrix and classification report.
Steps
Load the customer churn data into a pandas dataframe
Perform exploratory data analysis by checking the head of the data, the shape of the data, for missing values, and plotting the distribution of numerical and categorical variables.
Prepare the data for the model by splitting it into training and test sets, one-hot encoding categorical variables, and fitting a logistic regression model.
Predict customer churn using the logistic regression model and evaluate its performance using the classification report.
