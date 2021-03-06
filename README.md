# C++ Basic Data Types
The following project will give the user a basic introduction on how basic data types work in C++ programming. This project covers, but is not limited to, the following data types: integers, doubles, booleans and characters. It is important to note that there are other basic data types such as floats, however, for now what we cover will serve the purposes you need.

## Declaring Variables
In programming we need a way to store the information that we are working with in a safe place; the way we do this is through something called **variables**. Variables are ways of holding different pieces of data in computer science. Below demonstrates an example of declaring a variable in C++ programming:

```c++
int number; //Declares variable
number = 1; //Assigns value
```
You can also combine the declaration of variables in C++ programming into one line which is demonstrated below:

```c++
int number = 1;
```
When programming with variables you will only need to declare the variable once.

## Data Types of Variables
When we are programming with variables we need to specify to the computer what type of information is being stored in the variables we are working with. In order to do this, we need to make sure we specify the **data types** of the variables. The data type of a variable is what tells the computer what type of information is being store in that variable. It is common practice to specify the data type when we declare the variable.

### Integers
**Integers** are a type of variable that is meant to store whole numbers. Integers do not account for decimals so you should be careful when working with them. Below demonstrates an example of declaring integers in C++ programming:

```c++
int num1 = 1;
int negVal = -5;
int large = 102909;
```
### Doubles
**Doubles** are a type of variable that is meant to store decimal numbers. Doubles are much more precise than integers since they account for decimals, however, they also take up a much larger amount of memory storage. For that reason, you should only use doubles if you know that your program will require decimals. Below demonstrates an example of declaring doubles in C++ programming:

```c++
double decVal = 1.25;
double negDec = -5.26;
double wholeDec = 3.0;
```
### Booleans
**Booleans** are a type of variable that is used to hold true or false values. Booleans are often useful when we need to identify when a condition has or has not been meant for our program. Below demonstrates an example of declaring a boolean in C++ programming:

```c++
bool passed = true;
bool failed = false;
```
### Characters
**Characters** are a type of variable that is meant to store single character values. Characters can only hold one letter value. We'll cover how you can store multiple letter values (full words) in a later project. Below demonstrates an example of declaring characters in C++ programming:

```c++
char letter = 'e';
char punct = '?';
char letVal = 'T';
```
