# Pointers
##Code 1
1. Start
2. Declare variables: int i, j, float fl (integer and float variables), int* int_ptr (pointer to an integer), float* float_ptr (pointer to a float), char* char_ptr (pointer to a character)
3. Assign values to i and fl: i = 5, fl = 3.14
4. Assign the address of variable i to the integer pointer int_ptr: int_ptr = &i
5. Output: "*int_ptr " followed by the value pointed to by int_ptr (dereferencing int_ptr) and a newline
6. Output: "&i=" followed by the memory address of variable i and a newline
7. Output: "int_ptr = " followed by the value stored in int_ptr (memory address of variable i) and a newline
8. End
The program starts and declares necessary variables including integer and float variables, pointers to integer and float, and a pointer to a character.
The integer variable i is assigned the value 5, and the float variable fl is assigned the value 3.14.
The address of variable i is assigned to the integer pointer int_ptr.
The program outputs the value pointed to by int_ptr (dereferencing), the memory address of variable i, and the value stored in int_ptr (which is the memory address of i).
The program demonstrates the use of pointers by storing the memory address of a variable and then accessing the value stored at that memory location.
The program ends after performing the pointer operations and displaying the results.


##Code 2
1. Start
2. Declare variable: int i
3. Try Block:
   a. Output: "Enter i:"
   b. Input: Read the value of i from the user
   c. If i > 20:
      - Output: "Number entered is more than 20"
   d. Else if i > 15:
      - Throw an exception with the value of i
   e. Else:
      - Throw an exception with the message "Number less than 15"
4. Catch Block for int:
   a. Catch the exception of type int and store it in variable x
   b. Output: "Exception occurred for i=x"
5. Catch Block for char*:
   a. Catch the exception of type char* and store it in a pointer to char variable message
   b. Output: Output the message pointed by message
6. Catch Block for any other type of exception (...):
   a. Output: "Default exceptional handling"
7. End
The program starts and declares the necessary variables.
The user is prompted to enter a value for i.
Inside the try block:
If i is greater than 20, a message is displayed indicating that the number entered is more than 20.
If i is greater than 15, an exception is thrown with the value of i.
If i is less than or equal to 15, an exception is thrown with the message "Number less than 15".
If an exception of type int is caught, the program outputs a message indicating the occurrence of an exception and the value of i.
If an exception of type char* is caught, the program outputs the message pointed to by the message variable.
If any other type of exception occurs, a default message indicating default exceptional handling is displayed.
The program ends after handling the exceptions.



##Code 3
