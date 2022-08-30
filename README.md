# Assignment 1

OBJECTS FOR AUGUST 21, 2022

Task 1 - To complete this challenge, you must print Hello Solidity. Use str as a variable to store value.

Task 2 - Create functions

Task :
To complete this challenge, you have to create a state variable and initialised it with 10 and then you have to create a function returnStateVariable( ) which returns the value of the created state variable .

In the same way you have to create a local variable and initialised it with 20 and then you have to create a function returnLocalVariable( ) which returns the value of the created local variable.

# Assignment 2

OBJECTS FOR AUGUST 24, 2022

Task 1 - Create a state variable of uint type (need not to be public). Create a set ( ) and with one argument. And set the value of the created state variable with the value passed as an argument to the set ( ). Then create another function get ( ) which returns the value of the state variable.

Task 2 - Create a function evaluate(int a , int b).
Subtract the difference of a and b from the sum of a and b.
Return the result of the above task from the evaluate()

Task 3 - Create a function find(int a). Where a>0.
Return the remainder when a is divided by 3.

Task 4 - Create a function average(int a,int b,int c). Where a>0,b>0,c>0.
Return the average of a,b and c.

# Assignment 3

OBJECTS FOR AUGUST 26, 2022

Task 1 :

Create a function digitSum(int n). Where n>0.
Return the sum of digit for n.
For Example - If n=345 then digitSum() must return 12 i.e. 3+4+5 = 12
If n=909 then digitSum() must return 18 i.e. 9+0+9 = 18

Task 2 :

There is a series, S , where the next term is the sum of pervious three terms. Given the first three terms of the series, a ,b ,c and respectively, you have to output the nth term of the series.

S(n) = a for n=1

S(n) = b for n=2

S(n) = c for n=3

S(n) = S(n-1) + S(n-2) + S(n-3) for n>3

Create a function nthTerm(uint n, uint a, uint b, uint c) where n is the nth term to find and a,b,c are the three terms of the series.

For Example - If n=5 a=1 b=2 c=3 then nthTerm() must return 11 as S(1) = 1 S(2) = 2
S(3) = 3 S(4) = S(3) + S(2) + S(1) = 1+2+3 = 6 S(5) = S(4) + S(3) + S(2) = 6 + 3 + 2 = 11

# Assignment 4

OBJECTS FOR AUGUST 28, 2022

Task 1 :

Create a function prime(uint n) . This prime() will check whether n is a prime number or not.
If n is a prime number then prime() returns 1 and n is not prime then prime() must return 0.

For Example - If n=103 then prime() must return 1 as 103 is a prime number. If n=200 then prime() must return 0 as 200 is not a prime number.

# Assignment 5

OBJECTS FOR AUGUST 29, 2022

Task 1 : 

Create a function power(uint x,uint y) . This power() will calculate x raised to the power of y and return it.
For Example - If x=2 y=3 then power() must return 8 (2x2x2=8) If x=7 y=2 then power() must return 49 (7x7=49)

Task 2 :

A palindrome number is a number that is same after reverse. For example 545, 151, 34543 etc.
Create a function palindrome(uint n) . Thispalindrome() will check whether n is a palindrome or not.
If n is a palindrome then palindrome() returns 1 and n is not palindrome then palindrome() must return 0.
