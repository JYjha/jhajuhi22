## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
Ans. It's called general purpose dynamic language because it is not written in machine readable language and it's easy for humans to understand that is why it is high-level programming language.     

Q2. Why is Python called a dynamically typed language?
Ans. type of the variable is determined only during runtime that is why it is dynamically typed language.

Q3. List some pros and cons of Python programming language?
Ans. Pros:                                       Cons:
1.Python is easy to learn and read               1.It can have runtime errors 
2.It is open source language                     2.It consumes a lot of memory space
3.It has vast collection of libraries            3. Due to consumption of lot memory space it is not good for mobile computing
4.It is an interpreted language

Q4. In what all domains can we use Python?
Ans. 1.Artificial intelligence
     2. Data analytics and data visualization
     3.Web development
     4. Graphical User Interface
     5. mobile app development

Q5. What are variable and how can we declare them?
Ans. Value that can change, We can assign value depending upon the conditions. Variable consists of a data type
     example: 'x' is a variable and there will be a value assigned to it. It could be any data type.

Q6. How can we take an input from the user in Python?
Ans. By using input() function.
Ex. X = input("Enter the ....")

Q7. What is the default datatype of the value that has been taken as an input using input() function?
Ans. String datatype is the default datatype of the value that has been taken as an input using input() function.

Q8. What is type casting?
Ans. Typecasting is conversion of one datatype in to other datatpe according to the programme requirements.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
Ans. Yes, By using split() function.
Example. x,y = input("Enter values ").split()

Q10. What are keywords?
Ans. Keywords are reserved words that can be used for specific purpose.

Q11. Can we use keywords as a variable? Support your answer with reason.
Ans. No we can't because it a predefined words reserved for specific purpose in a programming language.

Q12. What is indentation? What's the use of indentaion in Python?
Ans. Indentation means the spaces at the beginning of an statement or code. Python uses indentation to indicate a block of code.

Q13. How can we throw some output in Python?
Ans. Through Print() statement.

Q14. What are operators in Python?
Ans.1.Arithmetic operators.
    2.Assignment operators.
    3.Comparison operators.
    4.Logical operators.

Q15. What is difference between / and // operators?
Ans. / for float division and // for integer division.

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
Ans. 
x = "iNeuroni"
print(x*4)
      
Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
Ans.
x = int(input("Enter a number "))
if (x % 2) == 0:
    print("The number is even")
else:
    print("The number is odd")   

Q18. What are boolean operator?
Ans. Logical operators AND, OR and NOT are boolean operators which provides output as True , False

Q19. What will the output of the following?
```
1 or 0 = 1

0 and 0 = 0

True and False and True  = True

1 or 0 or 0 = 1 or 0 = 1
```

Q20. What are conditional statements in Python?
Ans. Statements used to handle condition in the programme.

Q21. What is use of 'if', 'elif' and 'else' keywords?
Ans. if is used for multiple expressions in the programme in which decision making is required.
Example: If it is raining and weather is cold, we will not play outside


Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
Ans.
age = int(input("Enter age of the person "))
if age >= 18:
    print("I can vote")
else:
    print("I can't vote") 
   
Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
Ans.
numbers = [12, 75, 150, 180, 145, 525, 50]
evensum = 0


for i in numbers:
     if i%2==0:
         evensum += i
print(evensum)```


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
Ans.
x = input("Enter 1st number ")
y = input("Enter 2nd number ")
z = input("Enter 3rd number ")
if (x >= y) and (y >= z):
   largest = x
elif (y >= x) and (y >= z):
   largest = y
else:
   largest = z
   print("Largest of all", largest)
25. Write a program to display only those numbers from a list that satisfy the following conditions

 - The number must be divisible by five

 - If the number is greater than 150, then skip it and move to the next number

 - If the number is greater than 500, then stop the loop
 ```
numbers = [12, 75, 150, 180, 145, 525, 50]
for num in numbers:
    if num>500:
        break
    elif num>150:
        continue
    elif num % 5 == 0:
        print(num)
           


