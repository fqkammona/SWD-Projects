## Problem Statement
Using polymorphism write a program that simulates a scoreboard system with a selection of sports. 


## User Documentation
The user can run this program in the driver and follow the prompts that are given. At the being, the user will be prompted to choose which game, and after the choice has been input the program will ask for the home team and away team names. The menu and current quarter/period will be displayed as well as the scores for each team. Once the game is over there will be a replay of the game and the final scores and the winning team will be printed out. 

## Developer Documentation
Though the prompt of this program is to create a scoreboard using polymorphism the only time this program is a scoreboard is in the driver. This program has an abstract class `Game` which is the template for how all sub-classes of game should act and what they should also have. The sub-classes of `Game` are the following sports, `Football`, `Soccer`, `Baseball`, `Basketball` and `Hockey`.There are two additional classes the first being `Team` which is a class that has the name and points for a team. The constructor takes in a string and initializes the instance variable TeamName.The second additional class is `ScoreingMethod`, which has a constructor that takes a string and an integer and initializes the instance variables. `ScoreingMethod` is used to keep track of the name of the scoring method and the points associated with it. `Game` has an abstract method called `getScoreingMethods` that returns an array of `ScoreingMethod` objects.

UML Diagram:
![B11_ScoreboardDiagram.png](https://github.com/fqkammona/SWD-Projects/blob/main/UML-Diagrams/B11_ScoreboardDiagram.png)
