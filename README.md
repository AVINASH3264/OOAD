# OOAD ASSIGNMENT
## Class Diagram
![Assignment_version_2 8 umlcd](https://github.com/AVINASH3264/OOAD/assets/85469720/86cae0f8-7e12-432b-a8da-2fe7c0e6bcb0) 
## Domain: Banking
 
Use case : When a customer attempts to deposit money, the list of all accounts which the customers possess should be listed so that the customer can select to which account he would like to deposit the money. Customer can have the following accounts
 
#### SavingsMaxAccount
 
#### CurrentAccount
 
#### LoanAccount
 
· Customer(customerCode, customerName, List<Account>)
 
· Account(accountNo, accountType, balance, Product).
 
· Product(productCode, productName, List<Service>)
 
· SavingsMaxAccount is a Product(minimumBalance of Rs.1000 should be maintained in the account)
 
· CurrentAccount is a Product
 
· LoanAccount is a Product.(chequeDeposit should be chargeable ie 3%).
 
· Service(serviceCode, serviceName,rate)
 
### Default services
 
SavingsMaxAccount(CashDeposit, ATMWithdrawl, OnlineBanking)
 
CurrentAccount(CashDeposit, OnlineBanking, ATMWithdrawl, MobileBanking)
 
LoanAccount(CashDeposit, ChequeDeposit)
 
 

 

