# ML_Loan_purchase_prediction
To predict if an individual will opt for personal loan with the given set of feature variables.

## Case Study:

Campaign for selling personal loans 

This case is about a bank (Thera Bank) which has a growing customer base. Majority of these customers are liability customers (depositors) with varying size of deposits. The number of customers who are also borrowers (asset customers) is quite small, and the bank is interested in expanding this base rapidly to bring in more loan business and in the process, earn more through the interest on loans. In particular, the management wants to explore ways of converting its liability customers to personal loan customers (while retaining them as depositors). A campaign that the bank ran last year for liability customers showed a healthy conversion rate of over 9% success. This has encouraged the retail marketing department to devise campaigns with better target marketing to increase the success ratio with minimal budget.

The department wants to build a model that will help them identify the potential customers who have higher probability of purchasing the loan. This will increase the success ratio while at the same time reduce the cost of the campaign. 

The file given below contains data on 5000 customers. The data include customer demographic information (age, income, etc.), the customer's relationship with the bank (mortgage, securities account, etc.), and the customer response to the last personal loan campaign (Personal Loan). Among these 5000 customers, only 480 (= 9.6%) accepted the personal loan that was offered to them in the earlier campaign. 

### Data Set:
	Name: Bank_Personal_Loan_Modelling.xlsx
	Number of rows: 5000
	Number of Inputs: 12
	Number of Output: 1

The tasks performed are as follows:
### Data Preprocessing
		Checking for missing values
		Imputing missing values
		Standardization of feature values
		Divide the data in to train and test sets
### Data Modelling
		Predict if the individual will opt for a personal loan or not
		Implementation of Following classification models.
			1.Logistic regression
			2.Naive Bayes
			3.KNN
			4.Support Vector Machines
### Evaluation
		Comparison of model performances on test data set
