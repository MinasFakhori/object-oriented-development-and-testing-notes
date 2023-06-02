# Variables and Data types

Primitive data types can store 2<sup>n</sup>, where **n** is the number of bits. 

They are called primitive types because they can't be broken down further into smaller types.

--- 

### There are 8 primitives data types

**Numbers (Whole numbers)**  

* byte - 8 bits (-128 to 127)
* short - 16 bits (-32,768 to 32,767)
* int - 32 bit (-2,147,483,648 to -2,147,483,648)
* long - 64 bit (-9,223,372,036,854,775,808 to 9,223,372,036,854,775,807)

**Decimals**

* Float - 32 bits (23 bits before the decimal and 7 bits after the decimal)
* Double - 64 bits( 52 bits before the decimal and 15 bits after the decimal)

**Letters**

* Char 16 bits - Stores a single ASCII character, char goes up to 65,535 however short is also 16 bits and goes up to 32,767. This is because char is unsigned (meaning is can store positive and negative numbers) and short is signed.

**Boolean**

* Boolean is one bit - True/False 

---

### Data types that are not a data structure
Every data structure is a data type but not every data type is a data structure.

**System** - This is a class that is part of the java.lang package. It is a class that contains methods and variables that can communicate with the operating system.


**Scanner** - This is a class that is part of the java.util package. It is a class that contains methods and variables that can communicate with the input and output devices.

---

### Other data types

String is not a primitive data type, it is a class type. It is a data structure as well as a data type that stores a sequence of characters. 

---
### Other

Object is a super type of all other custom types.
object is a instance of a class.
class is a blueprint of an object.