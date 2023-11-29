# C- Programming Basics
# Lab 1 (22/08/2023)
# Q1) Write a simple Hello World program and its development process
# Theory
Compilation is the process of turning C language source code into machine code. Because C is a mid-level language, a compiler is required to turn it into executable code that can run on our machine. A C programme is transformed into an executable by a compiler. The source code is typically written in a high-level, human-readable language such as Java or C++.
# Output
![Screenshot 2023-09-17 at 8 13 15 PM](https://github.com/shrutitalyan/c-programs2/assets/143024392/d54e7bb6-51d2-40bf-9d77-4d1cc9e498b4)
# C- Programming Basics - Lab 2 (23/08/23)
# Q1) Write a program to print sizes of different data types
# Theory 
The size of a data type is the size it takes in memory. Their sizes vary. This size is represented in bytes. We can use the sizeof() method to get their sizes.
# Output
![Screenshot 2023-09-17 at 8 21 38 PM](https://github.com/shrutitalyan/c-programs2/assets/143024392/a1a67545-f2ce-44ae-951e-72f62f9cb263)
# Q2) Write a C program to read a number from the user and print a table of multiplication for that number.
# Theory
The program below takes an integer input from the user and generates the multiplication tables
# Output 

![Screenshot 2023-09-17 at 8 25 28 PM](https://github.com/shrutitalyan/c-programs2/assets/143024392/7d851c86-21ed-43cf-8f36-1606a44756d4)

# Q3) Write a program to display different start patterns on screen.
# Theory 
We must use two or three loops to create a star pattern in the C language. The number of loops depends on the pattern that we need to create. For pattern, a minimum of two is used i.e. one for a row and one for a column. The First loop is called an outer loop that shows the rows, and the second loop is called an inner loop that shows columns.
# Output 1
![Screenshot 2023-09-17 at 8 31 46 PM](https://github.com/shrutitalyan/c-programs2/assets/143024392/09645a23-c365-46bf-8e13-517cb655cc26)
# Output 2
![Screenshot 2023-09-17 at 8 32 24 PM](https://github.com/shrutitalyan/c-programs2/assets/143024392/115bfda9-2851-429c-9c4d-b26e907081fe)
# Output 3
![Screenshot 2023-09-17 at 8 32 59 PM](https://github.com/shrutitalyan/c-programs2/assets/143024392/e31f88d0-d7ff-4f1c-afb7-7d756dca8cd4)
# C-Programming Basics - Lab 3 (29/08/2023)
# Q1) Write a program to demonstrate pointers. Declare a pointer ptr to integer and equate it to the address of integer i. Print value of i, value of &i, value of ptr and value of *ptr.
# Theory
The use of pointers allows low-level memory access, dynamic memory allocation, and many other functionality in C.
A pointer is defined as a derived data type that can store the address of other C variables or a memory location. We can access and manipulate the data stored in that memory location using pointers.T he syntax of pointers is similar to the variable declaration in C, but we use the ( * ) dereferencing operator in the pointer declaration.

datatype * ptr;
# Output 
![Screenshot 2023-09-17 at 8 42 33 PM](https://github.com/shrutitalyan/c-programs2/assets/143024392/489835ec-c063-43ab-b39e-0515b3f6615b)
# Q2) Write a program in C to demonstrate function call by value and call by reference by writing a swap function to swap two integers.
# Theory
The methods of passing arguments to a function in C can be divided into two categories: "call by value" and "call by reference." These methods ascertain the impact of changing function parameter values on the initial values outside the function.
![Screenshot 2023-09-17 at 9 06 53 PM](https://github.com/shrutitalyan/c-programs2/assets/143024392/8109aa44-e2ae-408f-915a-6dc1c3e7ba7a)
# C- Programming Basics - Lab 5 (11/09/23)

# Q1) Write a program to demonstrate Recursion
# Theory 
Recursion in C is a programming technique that allows a function to call itself. This can be useful for solving problems that can be broken down into smaller, self-similar subproblems.

# (1) Addition of first n integers
![Screenshot 2023-11-23 at 11 26 12 PM](https://github.com/shrutitalyan/c-programs2/assets/143024392/9ec3bdea-82b1-44c3-b337-b6385a8411f3)

# (2) Factorial of n
![Screenshot 2023-11-23 at 11 28 24 PM](https://github.com/shrutitalyan/c-programs2/assets/143024392/965b4c88-7ca3-4209-ae35-0c946d6c181f)
# C- Programming Basics - Lab 6 (14/09/23) - (18/09/23)
# Q1) Write a program to demonstrate arrays and strings.
# Theory 
Arrays and strings are fundamental data structures in C programming. They are used to store collections of data of the same type.
An array is a collection of elements of the same data type stored in contiguous memory locations. Each element in an array is identified by an index, which is an integer value starting from 0.
A string is a sequence of characters terminated by a null character (\0). Strings are commonly used to represent text data. In C, strings are essentially one-dimensional character arrays.
# Q1) Aim : Print five digit number in words.
![Screenshot 2023-11-23 at 11 42 15 PM](https://github.com/shrutitalyan/c-programs2/assets/143024392/be1a87fd-5f1a-4aab-bfd8-be88106c6f25)

# C- Programming Basics - Lab 8 , 9 (5/10/23) - (9/10/23)
# Q1) Write a class (date), access its functions using class object (today)
# Theory 
Create a class named date, Initialize int arr month_days, initialize ptr to strings months and weekdays, Take day, month, year from user, Display the date in slashed form with the help of disp_date() function, Check whether the year entered by user is leap or not leap by using is_leap(), Calculate the total days from Jan 1 to current date day_of_year(), Display the date without slashed form using disp_date1(), Display the weekday for the current date using disp_weekday()

![Screenshot 2023-11-29 at 9 19 36 PM](https://github.com/shrutitalyan/c-programs2/assets/143024392/0665738b-bcc5-4f44-a10b-7e9e69908a08)

# LAB10
## DATE: 12-13 October
## Aim: Operator Overloading
## Algorithm :

Initialize Date Class:

Create a class called Date with private variables for day, month, and year.
Implement a constructor to set the initial date, and a display function to print the date.

Leap Year Check:
Create a function (isLeapYear) to check if a given year is a leap year.
A leap year is divisible by 4, but century years must also be divisible by 400.

Days in Month:
Create a function (daysInMonth) to determine the number of days in the current month.
February has 29 days in a leap year and 28 days otherwise.
April, June, September, and November have 30 days, while other months have 31 days.

Overloaded ++ Operator:
Overload the ++ operator as a member function in the Date class.
Increment the day by 1.
Check if the new day exceeds the number of days in the month.
If yes, reset the day to 1 and increment the month.
If the month exceeds 12, reset the month to 1 and increment the year.
Main Function:
In the main function, create an instance of the Date class with an initial date.
Display the current date.
Use the overloaded ++ operator to increment the date by one day.
Display the updated date.

This algorithm provides a simple way to manage dates, ensuring that the day, month, and year are correctly updated when the date is incremented by one day. The logic considers variations in the number of days in different months and leap years.
## Explanation 

Initialize Date Class:
Imagine we have a special box called "Date" that holds three pieces of information: day, month, and year.
When we create a new date, we put in the starting values for day, month, and year.

Leap Year Check:
We want to figure out if a certain year is a special type called a "leap year." It's like asking, "Is this a special year that has an extra day?"
If the year is divisible by 4 (like 2004, 2008), it's a leap year. But if it's a century year (like 1900, 2000), it should be divisible by 400 to be a leap year.

Days in Month:
Now, let's think about how many days are in each month. February is a bit tricky because it can have 28 days or 29 days in a leap year.
Other months have different numbers of days: some have 30, and some have 31.

Overloaded ++ Operator:
We want a special way to add one day to our date. So, we create a rule: when we add a day, we increase the day value by 1.
But, we need to be smart. If the day becomes too big for the month, we reset it to 1 and add 1 to the month.
If the month becomes too big (more than 12), we reset it to 1 and add 1 to the year.

Main Function:
In the main part of our program, we create a date (our special box) and set it to a specific day, month, and year.
We show what the date looks like (display it).
We then add one day to our date using our special rule.
Finally, we show the updated date.

In simple terms, it's like managing a calendar. We set a date, check for special years, know how many days each month has, and when we want to move to the next day, we follow some rules to keep things in order.
## OUTPUT
![Screenshot 2023-11-29 at 9 24 11 PM](https://github.com/shrutitalyan/c-programs2/assets/143024392/538a819c-b8d3-47ae-b81c-1d873339fbbf)
































































