0x0B. Python - Input/Output
0. Read file
mandatory
Write a function that reads a text file (UTF8) and prints it to stdout:
1. Write to a file
mandatory
Write a function that writes a string to a text file (UTF8) and returns the number of characters written:
2. Append to a file
mandatory
Write a function that appends a string at the end of a text file (UTF8) and returns the number of characters added:
Write a function that returns the JSON representation of an object (string):
Write a function that returns an object (Python data structure) represented by a JSON string:

Prototype: def from_json_string(my_str):
5. Save Object to a file
mandatory
Write a function that writes an Object to a text file, using a JSON representation:

Write a function that creates an Object from a “JSON file”:
Write a script that adds all arguments to a Python list, and then save them to a file:
Write a function that returns the dictionary description with simple data structure (list, dictionary, string, integer and boolean) for JSON serialization of an object:

mandatory
Write a class Student that defines a student by:

Public instance attributes:
first_name
last_name
age
Instantiation with first_name, last_name and age: def __init__(self, first_name, last_name, age):
Public method def to_json(self): that retrieves a dictionary representation of a Student instance (same as 8-class_to_json.py)
Write a class Student that defines a student by: (based on 9-student.py)

Public instance attributes:
first_name
last_name
age
Instantiation with first_name, last_name and age: def __init__(self, first_name, last_name, age):
Public method def to_json(self, attrs=None): that retrieves a dictionary representation of a Student instance (same as 8-class_to_json.py):

Write a class Student that defines a student by: (based on 10-student.py)

Public instance attributes:
first_name
last_name
age
Create a function def pascal_triangle(n): that returns a list of lists of integers representing the Pascal’s triangle of n:

Returns an empty list if n <= 0
You can assume n will be always an integ
Write a function that inserts a line of text to a file, after each line containing a specific string (see example):

Prototype: def append_after(filename="", search_string="", new_string=""):
You must use the with statement
Write a script that reads stdin line by line and computes metrics:

Input format: <IP Address> - [<date>] "GET /projects/260 HTTP/1.1" <status code> <file size>
Each 10 lines and after a keyboard interruption (CTRL + C), prints those statistics since the beginning:
Total file size: File size: <total size>

