# Lab Report 2 - Week 4
## Errors/Fixes for MardownParse.java

### Fix 1: Filtering out images and other non-link types
The first fix involved removing non-link type inputs such as images and pdfs
![image](lab2images/notlinktest-gitChange.png) <br>
The test file that caused this problem can be found [here](https://github.com/Potato0112/markdown-parser/blob/main/notlinktest.md) <br>
![image](lab2images/notlinktest-errorfile.png) <br>
The symptom of the bug was that non-link type inputs such as images and pdfs were being influded in the output <br>
![image](lab2images/notlinktest-beforeOutput) <br>

