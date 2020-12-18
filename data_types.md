# Data Types

Java is a *statically-typed* programming language: all variables must be declared before its use. So we need to declare variable's type and name.

Data types specify the different sizes and values that can be stored in the variable. There are two types of data types in Java:

## Primitive data types

### boolean

```java
Boolean isActive = true;
```
Size: 1 bit

### char

The char data type is used to store characters.
Java uses Unicode system not ASCII code system. The `\u0000` is the lowest range of Unicode system.

```java
char letterA = 'A'
char cMin = 0; // '\u0000'
char cMax = 65535; // '\uffff'
```
Size: 2 byte

### byte

The byte data type is used to save memory in large arrays where the memory savings is most required. It saves space because a byte is 4 times smaller than an integer.

```java
byte bMin = -128;
byte bMax = 127;
```
Size: 1 byte

### short

The short data type can also be used to save memory just like byte data type. A short data type is 2 times smaller than an integer.

```java
short sMin = -32768;
short sMax = 32767;
```
Size: 2 byte

### int

The int data type is generally used as a default data type for integral values unless if there is no problem about memory.

```java
int iMin = -2147483648; // (-2^31)
int iMax = 2147483647; // (2^31 -1) 
```
Size: 4 byte

### long

The long data type is used when you need a range of values more than those provided by int. Don't forget to append `L` to the end.

```java
long longMin = -9223372036854775808L; //(-2^63)
long longMax = 9223372036854775807L; // (2^63 -1)
```
Size: 8 byte

### float

Its value range is unlimited. It is recommended to use a float (instead of double) if you need to save memory in large arrays of floating point numbers. 
The float data type should never be used for precise values, such as currency.

```java
float f1 = 3.14159f;
```
Size: 4 byte

### double

The double data type is generally used for decimal values just like float. 
It also should never be used for precise values, such as currency.

```java
double d = 3.14159;
double dMax = 1.7976931348623157E+308; // which is approximately 17 followed by 307 zeros
double dMin = 4.9E-324; // which is 324 decimal places
```
Size: 8 byte

## Non-primitive data types

### Classes

### Interfaces

### Arrays
