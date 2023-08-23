## Problem Statement
Develop a networking program that establishes a client-server connection where the server exclusively manages an enhanced linked list. The client can request various operations on this linked list, such as item insertion and deletion at any position within the list.

## User Documentation
Upon starting the program, a connection is established between the client and the server, and the user can proceed by following the server's instructions. Please note that the "End Program" button requires two clicks to terminate the connection. The text box for adding or deleting items will only become editable when either the "Add Item" or "Delete Item" options are selected.

## Developer Documentation
The managed linked list is an enhanced version, allowing for insertion and deletion at any position. Clients must specify the exact location for each insert or delete operation. The client-side interface uses a `GridBagLayout`, implemented in the `ClientWithGUIS` class, making the layout code extensive. While some issues remain with the instruction components, the fundamental layout and functionalities are already in place and can be refined later.

UML Diagram:
![B06_LinkedListNetDiagram.png](https://github.com/fqkammona/SWD-Projects/blob/main/UML-Diagrams/B06_LinkedListNetDiagram.png)
