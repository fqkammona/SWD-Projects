# A03:
## Problem Statement

Create a GUI program for ExchangeComputation using JavaFX. Information is entered from separate components and components should also display the withdrawals made. 

## User Documentation

When the user starts the program there are not any accounts saved so they will have to first create there account. After that, they will be logged in and they can choose anything from the menu options or log out. 


## Developer Documentation

The class `exchangeGUIController` holds all the different scenes in them and all of the action methods. It is a little crowded and it would be better to have different controllers but that wasn't something in my ability at the time.

UML Diagram A03: 
![A03_ExchangeComputationGUIDiagram.png](https://github.com/fqkammona/SWD-Projects/blob/main/UML-Diagrams/A03_ExchangeComputationGUIDiagram.png)


# B01
## Problem Statement
Create a program that allows the user to withdraw money from their account in SWD bills and print out the type of bills needed. 


## User Documentation
When the user first starts the program they are given the ability to create a new account, log into their existing account, set the SWD exchange rate, do some exchanging without withdrawing any money, and end the program. 

## Developer Documentation
There is an abstract class `Currencies` that has arrays of the type of bills per currency, the name of the bills and the exchange rate from that currency to USD. `Currencies` has a sub-class called, `Exchange` which creates an ArrayList of objects `CurrenciesList`. `CurrenciesList` is a class created to organize all of the instance variables of `Currencies` into an ArrayList in `Exchange`. An example of this looks like is shown below:

`add(new CurrenciesList("USD", USDdollars, USDcurrency, USDbillNames))`
 
`CurrenciesList` has getters and setters for all of its instance variables. `Exchange` has methods that allow users to update the currency for SWD exchange rate and to do exchanges between different currencies as well as what type of bills to return in the specified currency. The `Bank` class is a sub-class of `Exchange` and uses the `newAccount` class to create an ArrayList of accounts. `newAccount` has two instance variables; account number and balance, which are initialized in the constructor. `Bank` uses methods from the `Exchange` class for withdrawals and exchanging between curreinces. 


UML Diagram B01: 
![B01_ExchangeComputationDiagram.png](https://github.com/fqkammona/SWD-Projects/blob/main/UML-Diagrams/B01_ExchangeComputationDiagram.png)
