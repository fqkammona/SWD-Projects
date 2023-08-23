## Problem Statement
Develop three distinct programs to achieve the following tasks: one for generating a key file, another for encrypting a message using the generated key file, and a final program for decrypting the encrypted message using the same key file.

## User Documentation
First, the user should run the `keyDriver` program to create the key file. Following this, they can execute the `EncryptorDriver` to produce an encrypted file, provided they input the correct path to the previously generated key file. Once both the key and encrypted files are in place, running the `DecryptorDriver`—again, with the correct paths to both files—will decrypt the message and display it on the screen.

## Developer Documentation
The project comprises six separate classes: `KeyGenerator`, `Encryptor`, and `Decryptor`, each paired with a corresponding driver class responsible for file operations such as reading, writing, opening, and closing. The `keyDriver` specifically creates a key file based on user inputs, including the file's name, the number of "n" values, and starting positions.

UML Diagram:
![B10_OneTimePadDiagram.png](https://github.com/fqkammona/SWD-Projects/blob/main/UML-Diagrams/B10_OneTimePadDiagram.png)
