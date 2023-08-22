## Problem Statement
Create a networking program where there is a client-server connection and the server is the only one who has access to the linked list and the client request updates to the linked list such as deleting and adding new items. This linked list should be an enhanced linked list that allows for insertion and deletion from anywhere in the list.

## User Documentation
Once the programs have started up the connection will be set and the user can follow the instructions coming from the server. There is an issue with the end program button where the client is required to press the button twice to terminate the connection. The textbox won't be editable until the adding item or deleting item is selected. 

## Developer Documentation
The linked list is an enhanced list so when the user request for an item to be added they must state where exactly they would like for it to be added. The form for the client is a gridbaglayout so there is a lot of code to create that layout in the `ClientWithGUIS` class. There are some issues with instruction parts but those can be solved later on. The foundation and layout for them are built. 

UML Diagram:
![B06_LinkedListNetDiagram.png](https://github.com/fqkammona/SWD-Projects/blob/main/UML-Diagrams/B06_LinkedListNetDiagram.png)
