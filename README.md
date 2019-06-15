# Customer-Churn-Management

# Introduction
Customer churn survey is an important part of telecommunications industry. Customer churn refers to the
fact that the existing customer of the telecommunications company terminated the existing business with
the company because of certain factors.

The telecommunications company determine that the customer to be lost if a telephone user has not recorded
the communication data after a certain period. In this report, the customer churn data will be analyzed, and
determine through classification analysis methods which users are the class of churn, and finally confirm
that which customers are likely to leave by supervised learning methods.

The data set contains two part, one is prediction data set churn-holdout, another is training data set churn-
train. The main processing of the project is training the churn-train data first and then make prediction on
churn-holdout data.

# Data describtion 
The raw churn-train data contains 4000 rows (customers) and 21 columns (features) and the “class” column
is prediction target. There are 20 variables include 19 predictors. Includes in predictors there are 15 numeric
variables and 4 categorical variables. Numeric variables are: account length, number vmail messages, total
day minutes, total day calls, total day charge, total evening minutes, total evening calls, total evening charge,
total night minutes, total night calls, total night charge, total international minutes, total international calls,
total international charge, number customer service calls. The categorical variables are state, area code,
international plan, voice mail plan. Includes in categorial variables, there are 50 different states (from 1 to
50), 3 different area codes (408, 415, 510), 2 different international plans (1, 2) and 2 voice mail plans (0,
1). There is no missing value in the training data. Phone number was deleted from the raw data because of
the useless meaning.
The raw churn-holdout data contains 1000 rows and columns are same with churn except “class” column.
The class column is a classification variable which make determination. The main target is to make a
judgment for churn-holdout data whether the customer is determined to be lost. If the class is 1, the customer
is determined to be lost, 0 otherwise.
