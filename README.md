# Java-Variables-and-Literals
Java Variables and Literals


## Java Variables

A variable is a location in memory (storage area) to hold data.

To indicate the storage area, each variable should be given a unique name (identifier). 

### Create Variables in Java

Here's how we create a variable in Java,

```
int age  = 29;
```

Here, age is a variable of int data type and we have assigned value 29 to it.


## Rules for Naming Variables in Java

### Java is case sensitive. 
Hence, age and AGE are two different variables. For example,

```
int age = 24;
int AGE = 25;

System.out.println(age);  // prints 24
System.out.println(AGE);  // prints 25

```
###  Variables must start with either a letter or an underscore, _ or a dollar, $ sign. 
For example,
```
int age;  // valid name and good practice
int _age;  // valid but bad practice
int $age;  // valid but bad practice
```

### Variable names cannot start with numbers. 
For example,
```
int 1age;  // invalid variables
```

### Variable names can't use whitespace.
For example,
```
int my age;  // invalid variables
```
