## Problem Statement
Write three separate programs, one to generate a key file, another to encrypt the message using the key file, and finally one program to decrypt the message using the key file. 


## User Documentation
The user must first run the `keyDriver` to create the key. After making the key the user can run the `EncryptorDriver` to create the encrypted file. However, the user needs to input the correct path to the key file to create the file. After the key and encrypted files have been generated the user can run the `DecryptorDriver`, given that they know the path to both files, which will take the encrypted message, decrypt it and print it to the screen. 

## Developer Documentation
This program has six separate classes, `KeyGenerator`, `Encryptor`, and `Decryptor`, and a driver associated with each of those classes. The drivers are responsible for everything regarding the files, such as reading, writing, opening, closing, etc. The `keyDriver` creates a file using the inputs from the user, such as the name of the file, how many n values and starting positions.

UML Diagram:
