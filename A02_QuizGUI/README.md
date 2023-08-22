## Problem Statement

Using Java Swing creates a quiz GUI for students in an elementary school using different GUI components such as Checkbox, Radio Button, Dropdown Box, and Lists. The program must have at least 5 questions with at least 4 choices to answer. In addition, the program must also have an Acknowledgement box verifying the student did not cheat, the student is required to check the acknowledgment box before they are allowed to submit and see the quiz results. 

## User Documentation

Once the user starts the program they are prompted to answer 5 different elementary math questions. They are not required to answer any question, the only requirement is the acknowledgment checkbox at the end of the quiz. Once the user has submitted the quiz the results frame will show a summary of the examination. The summary displays all the questions with the correct answers as well as the answers that the user submitted or the program will display unanswered if no answer was given. 

## Developer Documentation

This program has an abstract class `Components` which is a template for all components created for the `Quiz` class. The reasoning for this is that it allows a much easier ability to create many types of a certain component and seeing as all the components follow the same template, which will be explained further on, it's overall better software design. The sub-classes of `Components` are the following components, `Checkbox`, `Radiobutton`, `DropdownBox`,  and `ListBox`. As stated before all components follow the same template, all of the sub-classes had a constructor that took an array of correct answers, an array of all answers, and a string with the prompt for the user. The sub-classes called different methods of the superclass to create their component in a JPanel that was then called in the `Quiz` class. The same design is later used in the results frame. 


UML Diagram: 
![A02_QuizGUIDiagram.png](https://github.com/fqkammona/SWD-Projects/blob/main/UML-Diagrams/A02_QuizGUIDiagram.png)
