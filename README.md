# Bank Application

## Acenario: This app acts as a backend to handle new customer bank account requests

### It does the following:
- Read a .csv file of names, social security numbers, account type and initial deposit.
- use a proper data structure to hold all these accounts.
- both savings and checking accounts share the following properties:

  `deposit()`
  `withdraw()`
  `transfer()`
  `showinfo()`

  11-Digit Account Number (generated with the following process: 1 or 2 depending on Savings or Checking, last 2 digits of SSN, unique 5-digit number, and random 3-digit number)
- savings account holders are given a Safety Deposit Box, identified by a 3-digit number and accessed with a 4-digit code.
- checking account holders are assigned a Debit Card with a 12-digit number and a 4-digit PIN.
- Both accounts will use an interface that determines the base interest rate.
*Savings accounts will use .25 points less than the base rate*
*Checking accounts will use 15% of the base rate*
- The ShowInfo method should reveal relevant account information as well as information specific to the Checking account or Savings account.


> Objectives:
> - a robust application architecture
-  use when to use abstract classes and abstract methods
- use an interface API to recieve information from a developer's application
- explore constructors deeper and use the super() keyword
- explore access modifiers and when to use public, private or protected
- read data from a file and store in an appropriate data structure
- generate random numbers and work with String API