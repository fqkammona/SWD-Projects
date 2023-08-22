## Problem Statement

This project creates two different kinds of barcodes, POSTNET barcode, which is used by the post office to sort mail, and UPC-A, which is used for tracking items at grocery stores. POSTNET generates a barcode given a ZIP or a ZIP+4, or a ZIP+4+delivery and UPC-A generates a barcode given an eleven-digit product code. Both, POSTNET and UPC-A have a decoder class that reverts what they do and all classes have a driver class and an associated tester class.  

## User Documentation
For the POSTNET encoder, the user can enter the ZIP, a ZIP+4, or a ZIP+4+delivery and the barcode will be displayed. After receiving that code they can then use the decoder class `PostNetDecoder` and be able to do a round-trip, meaning get the ZIP that was originally given. The same follows with the UPC-A classes. 

## Developer Documentation
Java Expressions are used in the POSTNET encoder and decoder and there are also some recursive algorithms used for the check digit. There is another recursive algorithm in the UPC-A decoder to find which side of the barcode the binary string is on so that the program knows which array to use. 

UML Diagram:
![A15_BarcodesDiagram.png](https://github.com/fqkammona/SWD-Projects/blob/main/UML-Diagrams/A15_BarcodesDiagram.png)
