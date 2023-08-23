## Problem Statement
Create a quiz application for elementary school students using Java Swing. The application should include a variety of GUI components such as checkboxes, radio buttons, dropdown boxes, and lists. The quiz must consist of a minimum of 5 questions, each offering at least 4 multiple-choice answers. Additionally, the application must feature an acknowledgment checkbox that the student must check to confirm they have not cheated. This acknowledgment is mandatory before the student can submit the quiz and view the results.

## User Documentation
Upon launching the application, the user is presented with 5 elementary-level math questions. Answering the questions is optional; however, checking the acknowledgment checkbox at the end of the quiz is required for submission. After submission, a results frame will appear summarizing the student's performance. This summary will display each question along with its correct answer and the student's chosen answer. If a question is left unanswered, the summary will indicate so.

## Developer Documentation
The program architecture includes an abstract class named Components, serving as a template for all the GUI components used in the Quiz class. This design choice simplifies the process of creating different types of components by adhering to a consistent template. The subclasses derived from Components are Checkbox, RadioButton, DropdownBox, and ListBox.

Each subclass constructor takes three parameters: an array of correct answers, an array of all possible answers, and a string containing the user prompt. These subclasses call various methods from the superclass to construct their respective components, which are then encapsulated within a JPanel and integrated into the Quiz class. The same architectural pattern is replicated in the results frame for a cohesive design.


UML Diagram: 
![A02_QuizGUIDiagram.png](https://github.com/fqkammona/SWD-Projects/blob/main/UML-Diagrams/A02_QuizGUIDiagram.png)
