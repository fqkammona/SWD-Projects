## Problem Statement
Initially, the B01 project was designed to enable users to withdraw money in SWD bills from their accounts, providing them with the type of bills needed. Later on, an A03 extension was introduced, aiming to develop a GUI program for ExchangeComputation using JavaFX. This GUI should incorporate separate components for information entry and display withdrawals.

## User Documentation
For the B01 project, the application starts with multiple options: creating a new account, logging into an existing account, setting the SWD exchange rate, engaging in currency exchange without withdrawals, or exiting the program. Post A03 extension, when a user starts the program for the first time, they need to create an account. Upon account creation, users can explore various menu options or log out.

## Developer Documentation
At the core of B01 is an abstract class named `Currencies`, containing arrays specifying types of bills, bill names, and the exchange rate to USD. This class has a subclass, `Exchange`, which compiles an ArrayList of `CurrenciesList` objects to organize all currency-related information. For example:
`add(new CurrenciesList("USD", USDdollars, USDcurrency, USDbillNames))`

`Bank`, another subclass of `Exchange`, is dedicated to account management. It uses the `newAccount` class to store account numbers and balances within an ArrayList. Functions from `Exchange` are used for withdrawals and currency conversions.

The A03 extension brought in a GUI controller named `exchangeGUIController`, which handles all scenes and action methods. Though the controller would benefit from further decomposition, the current setup was based on available skills at the time of development. The combined project offers a comprehensive solution for currency exchange and account management, now enhanced with a JavaFX GUI, making it more interactive and user-friendly.


UML Diagram A03: 
![A03_ExchangeComputationGUIDiagram.png](https://github.com/fqkammona/SWD-Projects/blob/main/UML-Diagrams/A03_ExchangeComputationGUIDiagram.png)


UML Diagram B01: 
![B01_ExchangeComputationDiagram.png](https://github.com/fqkammona/SWD-Projects/blob/main/UML-Diagrams/B01_ExchangeComputationDiagram.png)
