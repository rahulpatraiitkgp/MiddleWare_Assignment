# MiddleWare_Assignment
Case Study | Mobile Recharge Application | Billing Software Application


## Mobile Recharge Application

Problem Statement: Mobile Service Provider needs an application for Customer to provide support, so the customer is able to perform various operations like Account Balance Enquiry and Recharge Account. 
1.	Account Balance Enquiry Option	:
        If customer selects this option, MobileNo should be accepted from the user.  
        If mobileNo exists in the AccountEntry Map, Balance amount should be displayed, otherwise error message should be displayed.



        Sample Run

        Enter Mobile No : 9922943943

        Your Current Balance is Rs. 500.00

        OR

        Enter MobileNo : 9834391234

        ERROR:  Given Account Id Does Not Exits

2. 	Recharge Account : 
        If customer selects this option, then Mobile No and Recharge Amount needs to be entered by the customer.
        Depending on the given Mobile no update the final amount in Account table i.e.
        Note :  New Account Balance=Existing Balance Amount+ New Recharge Amount

                    On Success Recharge display “Account Recharged successfully : “ and also display the account details as below.


        Sample Run

        Enter MobileNo : 9932012345
        Enter Recharge Amount : 140

        Your Account Recharged Successfully 
        Hello Manish ,Available Balance is 440 .
        OR

        Enter Mobile No : 90110212

        ERROR:  Cannot Recharge Account as Given Mobile No  Does Not Exits
        
## Billing Software Application

Problem Statement: A Take Home company requires a billing software for its super market where different types of products are sold to the customers on retail basis. This billing software will help

- a.	the cashier to see the product information on entering the product code
- b.	calculate the total cost for each product based on the quantity
- c.	and display the final bill to user.


1.	Generate Bill by entering Product code and quantity

A)	Enter Product Details		 

Following information should be accepted from the cashier when he/she bills the product chosen by the customer. 

Enter the product code: 1001
Enter the quantity: 2

Note: 
i.	Quantity should not be lesser than or equal to zero
ii.	Validation should be taken care for all input fields(i.e. ProductCode should be 4 digit )
     
B)	Calculating Total and displaying the bill

When the above details are entered by the cashier, this application should calculate the line total (product_price * quantity), display the following information 

Product Name: 		iPhone
Product Category:		Electronics
Product Description:		Smart Phone
Product Price (Rs): 		35000
Quantity:			2
Line Total (Rs): 		70000

C)	If the Product Code is not available in existing  HashMap  collection following error message will be displayed

Sorry ! The Product Code<<product_code>> is not available.


