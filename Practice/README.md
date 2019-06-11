### Project Overview

 # The mission is to decipher a message from a text file. There were multiple text files that need to be read and have certain operations performed to get the final message.


### Learnings from the project

After completing this project I have learned:
 
String operations

Conditional statement and loops

File I/O

Functions

Compherensions

Lamda Functions


### Approach taken to solve the problem

 Stage-1
Write a function by name read_file which takes file as the parameter in read mode to read the contents by line by line and save the first line in a variable and close the file and return the variable.
Call the function and store it in a variable

Stage-2
Write a function which takes two files as the parameters
Convert the received messages to int and do a floor division and store it in a variable 'quotient'
Do a type conversion on quotient to string and return the string
Call the function and store it in a variable

Stage-3
Write a function which takes in message as a parameter
Construct a for loop to check the message passed in the parameter to check for a condtion and returns matched condtion as output

Stage-4
Write a function which takes in two messages as a parameter
Split the messages using split function and store in different variables
Use a list compherension to save variables which are in 1st list but not in the second list
Use string.join() function to combine the messages and returns the message

Stage-5
Write a function which takes in a messages as a parameter
Split the messages using split function and store a variable
Create a lambda function to check if length of the variable is even
Use filter function and pass the lambda function and pass the previous variable and store it in another variable 
Use join and combine the variables together and store it a variable and return it

Stage-6
Combine all the messages in the previous stages using join()
Open the file write content and close 
Run the function to see the decipher message 



