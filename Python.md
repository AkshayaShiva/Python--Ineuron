# Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?

Python is a general-purpose language, as it can be used to create a variety of different programs and isn't specialized for any specific problems.Python is a high-level programming language as it is known for its ease of readability.

Q2. Why is Python called a dynamically typed language?
Python is s dynamically typed languages, since type checking takes place at runtime or execution time. This means that variables are checked against types only when the program is executed.

Q3. List some pros and cons of Python programming language?
Pros	                                    Cons
Beginner-friendly	                        Issues with design
Large Community	                            Slower than compiled languages
Flexible and Extensible	                    Security
Extensive Libraries	                        Work Environment
Embeddable	                                High memory consumption
Highly Scalable	                            Dynamically-typed language
IoT Opportunities	                        Complex multithreading
Portable	                                Garbage collection leads to potential memory losses


Q4. In what all domains can we use Python?
Python allows the user to work on multiple domains ranging from Data Science, Machine Learning, Deep Learning, Artificial Intelligence, Scientific Computing Scripting, Networking, Game Development to Web Development.

Q5. What are variable and how can we declare them?
A Python variable is a symbolic name that is a reference or pointer to an object. Once an object is assigned to a variable, you can refer to the object by that name. But the data itself is still contained within the object. 
A variable is created the moment you first assign a value to it.

Q6. How can we take an input from the user in Python?
This input() function helps in getting inputs from users.

Q7. What is the default datatype of the value that has been taken as an input using input() function?
By default,Python returns the user input in form of a string

Q8. What is type casting?
The conversion of one data type into the other data type is known as type casting in python or type conversion in python. 

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

Yes.Using split() method : 
This function helps in getting multiple inputs from users. It breaks the given input by the specified separator. If a separator is not provided then any white space is a separator. Generally, users use a split() method to split a Python string but one can use it in taking multiple inputs.

input().split(separator, maxsplit)

Q10. What are keywords?
Keywords are special reserved words that have specific meanings and purposes and can't be used for anything except for those specific purposes. These keywords are always available and we need not import them into your code to use them.

Q11. Can we use keywords as a variable? Support your answer with reason.
We cannot use a keyword as a variable name, function name or any other identifier. Keywords are reserved words that have a special meaning and can't be used for anything except for those specific purposes.

Q12. What is indentation? What's the use of indentaion in Python?
Indentation refers to the spaces at the beginning of a code line.The indentation in Python is very important. Python uses indentation to indicate a block of code.

Q13. How can we throw some output in Python?
The basic way to throw output in Python is through the print statement.Print() function help us to display the outputin the screen.

Q14. What are operators in Python?
Operators perform operations on variables and values in Python.
Following are some of the operators  in Python
Arithmetic operators
Assignment operators
Comparison operators
Logical operators
Identity operators
Membership operators
Bitwise operators

Q15. What is difference between / and // operators?
/ can be used to perform Float Divison in Python.i.e Delivers the result in decimal values.
// can be used to perform Integer Division in Python.i.e Delivers the result in Integer values.

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron

Output:
for x in range(5):    
    print("ineuron",end ="")
```

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

Code:
num = int(input('Enter the number: '))
if (num%2 ==0):
    print (f'Number {num} is even')
else:
    print (f'Number {num} is odd')

Q18. What are boolean operator?

The logical operators and, or and not are also referred to as boolean operators. While and as well as or operator needs two operands, which may evaluate to true or false, not operator needs one operand evaluating to true or false.

Q19. What will the output of the following?
```
1 or 0 => 1

0 and 0 => 0

True and False and True =>False

1 or 0 or 0 => 1
```

Q20. What are conditional statements in Python?
Conditional Statement in Python perform different computations or actions depending on whether a specific Boolean constraint evaluates to true or false. Conditional statements are handled by IF ELSE statements in Python.

Q21. What is use of 'if', 'elif' and 'else' keywords?
Python if Statement is used for decision-making operations. It contains a body of code which runs only when the condition given in the if statement is true. 
If the condition is false, then the optional else statement runs which contains some code for the else condition.
In Python, elif is short for "else if" and is used when the first if statement isn't true, but you want to check for another condition. 

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
