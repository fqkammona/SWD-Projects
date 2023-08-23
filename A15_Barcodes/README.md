## Problem Statement
This project aims to develop two types of barcodes: POSTNET, primarily used by postal services for mail sorting, and UPC-A, commonly used in grocery stores for item tracking. The POSTNET barcode generator accepts ZIP, ZIP+4, or ZIP+4+delivery codes, while the UPC-A generator requires an eleven-digit product code. Both barcode types come with corresponding decoder classes, as well as driver and tester classes.

## User Documentation
For the POSTNET encoder, users can input either a ZIP code, ZIP+4 code, or ZIP+4+delivery code to generate a barcode. Subsequently, the `PostNetDecoder` class can be used to revert the barcode back to its original ZIP code, completing a round-trip conversion. A similar workflow exists for the UPC-A barcode generation and decoding.

## Developer Documentation
Java expressions are employed in both the POSTNET encoder and decoder classes. Recursive algorithms are utilized to calculate the check digit in the POSTNET system. In the UPC-A decoder, another recursive algorithm identifies which side of the barcode a binary string resides on, enabling the program to select the appropriate array for decoding.

UML Diagram:
![A15_BarcodesDiagram.png](https://github.com/fqkammona/SWD-Projects/blob/main/UML-Diagrams/A15_BarcodesDiagram.png)
