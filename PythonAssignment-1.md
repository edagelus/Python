## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
  Python is a general purpose language becuase we can create any kind of software applications through it . Its also an highly language because it more closer to user than processor 
Q2. Why is Python called a dynamically typed language?
Python is called dynamically typed language because you are not bound to declare the type of dataype for variables. 
Q3. List some pros and cons of Python programming language?
Pro:
Python is easy to learn 
Python has extensive libraries with a diversified community .
Python allows us to developed almost any application with the support of libraries . 
Con :- 
Python is not so strong with mobile computing applications 
It consumes huge memory during development of huge applicatons and memory optimization needs to be done.

Q4. In what all domains can we use Python?
Yes Python is used almost in all fields 
Q5. What are variable and how can we declare them?
Variables are temporary location that  hold some values 
ex ; x = "Jai Ho iNeuron"
Q6. How can we take an input from the user in Python?
To take input from user we need to make use of input function 
example ; 
 name = input("Enter your name ")

Q7. What is the default datatype of the value that has been taken as an input using input() function?
By default it will be string object
Q8. What is type casting?
Type Casting simply means conversion of one datype into another dataype 
Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
Input function does  not allow you to enter multiple inputs as declaration is only meant for only one .
Q10. What are keywords?
Python has special subset of words with specific functions 
Q11. Can we use keywords as a variable? Support your answer with reason.
we cant use them as variable because python Intreprter has already used those words for different purpose 
Q12. What is indentation? What's the use of indentaion in Python?
Indentation simply means adding empty spaces before a statment inside a block of code .Its increases code relability 
Q13. How can we throw some output in Python?
To throw output we simply make use of printf function
Q14. What are operators in Python?
Operators are specfic symbols that are used to evaulate a specfic expression . 
Q15. What is difference between / and // operators?
/ :- Divsion Operator with decimal part 
// :- Operator without decimal part 
Q16. Write a code that gives following as an output.

x = "iNeuron"
print (str(x)*4)

```
iNeuroniNeuroniNeuroniNeuron
```

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
print("Please give me a number : = ")
num  =int(input())
if (num % 2) == 0 :
    print("Number is Even " )
else:
    print("Number is Odd ")

Q18. What are boolean operator?
Booleans are set of operators that represent truth values of an expression .The  fundamantal boolean are 
And , or ,not

Q19. What will the output of the following?
```
1 or 0   True

0 and 0   False

True and False and True

1 or 0 or 0  True 
```

Q20. What are conditional statements in Python?
Python has set of statements called as conditionals used when some decison making logic needs to be implemented.
Q21. What is use of 'if', 'elif' and 'else' keywords?
If /else / elif   are decision making statments .If contains  a  block of code  and gets executed when the condition is true . Else contains a block of code and gets excuted when the condition is false . The elif allows you to check multiple expressions for true and execute the block of code . 
Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
print("Please give me a age of the person : = ")
age =int(input())
if age >= 18 :
    print("The person can vote ")
else:
    print("The Person cant vote")


Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

numbers = [12, 75, 150, 180, 145, 525, 50]

total = 0 

for i in numbers: ## loop through each element 
    if i % 2: ##check if number is even 
        total = total + i  # add them 
print("The sum of all even numbers is :- ",total)


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

num1,num2,num3 = input("Please enter three number : ").split()
print("The greatest number is :", (max(num1, num2,num3)))

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```


numbers = [12, 75, 150, 180, 145, 525, 50]

b = []
for i in numbers:
    if i > 150:
        if i > 500:
            break
        continue
    if i % 5 == 0:
        b.append(i)
        
print(b)