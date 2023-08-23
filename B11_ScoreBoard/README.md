## Problem Statement
Design a program that utilizes polymorphism to simulate a scoreboard system for a variety of sports.

## User Documentation
To use the program, the user initiates it via the driver and follows on-screen prompts. Initially, the user selects the sport, after which they are prompted to enter the names of the home and away teams. Throughout the game, the program displays a menu, the current quarter or period, and the scores for each team. When the game concludes, a replay is available, along with the final scores and the name of the winning team.

## Developer Documentation
Although the program is framed as a scoreboard, its scoreboard functionalities are primarily located in the driver. The architecture includes an abstract class called `Game`, serving as a template for all sports subclasses, including `Football`, `Soccer`, `Baseball`, `Basketball`, and `Hockey`.

Two additional classes play crucial roles. The `Team` class holds information about team names and points, taking a string in its constructor to initialize the `TeamName` instance variable. The second class, `ScoreingMethod`, has a constructor that accepts a string and an integer to initialize its instance variables, which are used to keep track of different scoring methods and their associated points. The `Game` class contains an abstract method named `getScoringMethods` that returns an array of `ScoreingMethod` objects.

UML Diagram:
![B11_ScoreboardDiagram.png](https://github.com/fqkammona/SWD-Projects/blob/main/UML-Diagrams/B11_ScoreboardDiagram.png)
