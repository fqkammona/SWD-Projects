# SWD-Projects
The projects outlined here were developed as part of my ECE:3330 Introduction to Software Design class, where the objective was to understand and apply key principles of software design and development. These projects range from creating a quiz application aimed at elementary school students, to generating and decoding barcodes, to simulating a sports scoreboard. Across the projects, various programming paradigms and features such as GUI components, client-server networking, polymorphism, and encryption were employed. Each project offered a unique challenge, but the underlying theme was to enhance both technical skills and practical application know-how.

## A02_QuizGUI
I successfully developed a quiz application targeted at elementary school students using Java Swing. The application featured a range of GUI components, including checkboxes, radio buttons, dropdown boxes, and lists, and presented the user with 5 elementary-level math questions. I designed the program architecture with an abstract class called Components, which served as a template for all other GUI components, making the system modular and easy to expand or modify. The quiz also incorporated an acknowledgment checkbox to ensure academic honesty, a requirement before students could submit their quiz and view their performance summary. [View Project](https://github.com/fqkammona/SWD-Projects/tree/main/A02_QuizGUI)

## A03-B01_ExchangeComputation 
Initially, I focused on crafting a program that managed user accounts and performed currency exchanges, utilizing an abstract class for handling various currencies. Later, I integrated a JavaFX-based GUI, providing a more interactive way for users to manage accounts and see transaction history, merging two separate endeavors into a cohesive, user-friendly application. [View Project](https://github.com/fqkammona/SWD-Projects/tree/main/A03-B01-ExchangeComputation)

## A15_Barcodes
I designed and implemented a project that generates two different types of barcodes: POSTNET, used for mail sorting by postal services, and UPC-A, used for item tracking in grocery stores. The application not only generates these barcodes based on various input formats but also decodes them, offering a complete round-trip conversion. Advanced features include the use of Java expressions and recursive algorithms for functions such as calculating check digits and identifying the correct array for decoding in UPC-A. [View Project](https://github.com/fqkammona/SWD-Projects/tree/main/A15_Barcodes)

## B06_LinkedListNet
I developed a networking program that established a client-server connection focused on the management of an enhanced linked list. The server had exclusive control over this list, enabling the client to request specific operations like item insertion or deletion at any position within the list. The user interface, built with `GridBagLayout`, provided an interactive way for clients to make these requests. Despite some minor issues, such as the "End Program" button requiring two clicks to terminate the session, the core functionalities of the project were successfully implemented. [View Project](https://github.com/fqkammona/SWD-Projects/tree/main/B06_LinkedListNet)

## B10_OneTimePad
I created a trio of programs to facilitate cryptographic tasks. The first program generates a key file based on user input via the `keyDriver`. The second encrypts a message using the generated key file, executed through the `EncryptorDriver`. The final program, controlled by the `DecryptorDriver`, reverses this encryption, revealing the original message. To manage file operations, each main class is paired with a corresponding driver class, making the system both robust and user-friendly. [View Project](https://github.com/fqkammona/SWD-Projects/tree/main/B10_OneTimePad)

## B11_ScoreBoard
I architected a sports scoreboard simulation program that leverages the principles of polymorphism. The program is built around an abstract Game class, which provides a common template for a range of sports subclasses including Football, Soccer, and more. Additional utility classes, Team and ScoreingMethod, were introduced to manage team-related information and different scoring mechanisms. The scoreboard's primary functionalities reside in the driver, yet the program structure ensures that each sport can have its unique characteristics while adhering to a common interface. [View Project](https://github.com/fqkammona/SWD-Projects/tree/main/B11_ScoreBoard)





