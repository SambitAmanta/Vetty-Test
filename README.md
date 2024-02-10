# Vetty-Test
Vetty Test

## Description:

This Flask application serves as a lightweight file reader. It features a single GET route that reads the content of a specified text file and renders it in an HTML page, preserving any existing markup. 

## Routes:
1. To read the default file (file1.txt) from start to end:
   http://localhost:5000/readfile/
   
3. To read a specific file (e.g., file2.txt) from start to end:
   http://localhost:5000/readfile/file2.txt
   
5. To read a specific range of lines (e.g., lines 10 to 20) from a specific file (e.g., file3.txt):
   http://localhost:5000/readfile/file3.txt?start_line=10&end_line=20
