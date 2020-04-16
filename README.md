# Python-ChurnCustomers

#variables:
customerID	tenure	PhoneService	Contract	Paperless	PaymentMethod	MonthlyCharges	MonthlyGroceryspent	
Churn	Revenue	gender	Age	Partner	N_dependent

The dataset of churn contains 14 columns. customerID, tenure, PhoneService, Contract , Paperless, PaymentMethod, 
MonthlyCharge, MontlyGroceryspent, Revenue, gender, Age, Partner, N_dependent and Churn as dependent variable. 
Monthly Charges has 12, churn 52 and revenue 44 missing values. median is used to replace revenue and monthly 
charges missing values, and “Undecided” for the 52 missing values for y=churn. After cleaning we have 7042 
rows of data. Encoding on categorical variables, Phone Service with 2 levels yes=1, no=0, Contract with 3 
levels month-to-month=1, one-year=2 and two-year=3, Paperless with 2 levels yes=1, no=0, PaymentMethod with 
4 levels Bank transfer (automatic)=1, Credit card (automatic)=2, Electronic check=3 and Mailed check=4, 
gender with 2 levels male=1 and female=2, Partner with 2 levels yes=1, no=0, churn with 3 levels undecided=1, 
no=2 and yes=3 is done.

#Models tested:
#1- Logistic Regression
#2- Decision Tree



