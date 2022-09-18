## Read & Write Files in Python
- Reading and writing files is a very common practice in Python
- A files is a set of bytes used to store data
- There are three main parts of a file
  - Header is about the contents of the file
  - Data is the actual contents of the file
  - EOF is a special character that indicates the end of the file
- Accessing a file or file path is required and its broken up into three parts
  - Folder path is the location of the folder
  - File name is the name of the file
  - Extension is the end of the file path
- Two most common encodings are:
  - ASCII which stores 128 characters
  - Unicode which can contain 1,114,112 characters 
- Characters to go through files:
  - r: read
  - w: Write
  - rb/wb: open in binary mode
- Three different categories of file objects:
  - Text files are the most common
  - Buffered binary files is used for reading and writing files
  - Raw binary files are generally used as a low lvl building block for binary text streams

## Exceptions in Python
- Syntax errors occur when the parser detects an incorrect statement
- if a if condition is true it will continue with a code block, False will return an Assertion Error
- A try and except block will catch and handle exceptions