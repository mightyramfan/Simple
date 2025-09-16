# MODULE 4: PRACTICE PYTHON FUNDAMENTALS

#### Practice using these Python building blocks to start writing readable, structured scripts.

#### Create a New Python File

1. In VS Code, click File > Open Folder, and create/select a folder like python-course
2. In the Explorer tab (left sidebar), click New File and name it: **basics.py**


#### Practice fundamental  tasks

Type the following text into the terminal and observe the outputs.

| DEFINITIONS                                                  | CODE                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| A **VARIABLE** stores information (like a name or number) so you can reuse it later. | name = "Sam"         # a string (text)<br/>age = 34             # an integer (number)<br/>is_writer = True     # a boolean (True or False) |
| Use **PRINT()** to show the result of your code in the terminal. | print("Name:", name)<br/>print("Writer?", is_writer)<br/><br/>**The output will look like this:**<br/>Name: Sam<br/>Writer? True |
| Use **+** for basic combinations of text and variables. (Should be used rarely) | print(name + " is a technical writer.")                      |
| Use **F-STRING** for all other combinations of text and variables. (Best practice) | print(f"{name} is a technical writer aged {age}.")           |
| Include **MATH SYMBOLS** for basic equations.<br/><br/>**+** addition <br/>**-** subtraction<br/>***** multiplication<br/>**/** division<br/> | docs_written = 10<br/>days = 5<br/><br/>print("Docs per day:", docs_written / days)<br/><br/>**The output will look like this:**<br/>Docs per day: 2.0 |
| A **COMMENT** starts with `#` and is ignored by Python.  It's just for humans reading the code. | # This script prints a summary for a technical writer        |
