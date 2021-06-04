# Default_Payment 

This is a credit default dataset. The label in this dataset is called default_payment_next_month. It is a 1 / 0 indicator, with 1 meaning that the individual defaulted on credit the next month, while 0 means a default did not occur. The model_pred variable is the model prediction. 

Here's the data dictionary: 

ID = unique identifier for a customer
LIMIT_BAL refers the amount of the credit given to the customer
The PAY_0, PAY_1, ...etc. variables refer to past payments at different time frames. These are categorical variables with the following mapping:
-1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above
The PAY_AMT1, PAY_AMT2, ... etc. variables refer to previous payments (e.g. 1 month in the past, 2 = 2 months in the past, etc.)
    
The BILL_AMT1, BILL_AMT2, ...etc. variable are similar, except referring the billed amounts at different timeframes.
