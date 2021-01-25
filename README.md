# Python education project by JetBrains: loan calculator stage 4/4 Differentiate Payment
## Description
Finally, let's add to our calculator the capacity to compute differentiated payments. We’ll do this for the type of repayment where the loan principal is reduced by a constant amount each month. The rest of the monthly payment goes toward interest repayment and it is gradually reduced over the term of the loan. This means that the payment is different each month. 

PP = the loan principal;
ii = nominal interest rate. This is usually 1/12 of the annual interest rate, and it’s usually a float value, not a percentage. For example, if our annual interest rate = 12%, then i = 0.01.
nn = number of payments. This is usually the number of months in which repayments will be made.
mm = current repayment month.
The user has to input a lot of parameters, so it might be convenient to use command-line arguments.
You can run your loan calculator via command line like this:

## Objectives
In this stage, you are going to implement the following features:

Calculation of differentiated payments. To do this, the user can run the program specifying interest, number of monthly payments, and loan principal.
Ability to calculate the same values as in the previous stage for annuity payment (principal, number of monthly payments, and monthly payment amount). The user specifies all the known parameters with command-line arguments, and one parameter will be unknown. This is the value the user wants to calculate.
Handling of invalid parameters. It's a good idea to show an error message if the user enters invalid parameters (they are discussed in detail below).
The final version of your program is supposed to work from the command line and parse the following parameters.
