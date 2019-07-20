# **my_C_Notes**
In my C Notes i will make notes based on my understanding

## Features of C language
 - It is a robust language with rich set of built-in functions and operators that can be used to write any complex program.
-  The C compiler combines the capabilities of an assembly language with features of a high-level language.
-  Programs Written in C are efficient and fast. This is due to its variety of data type and powerful operators.
-  It is many time faster than BASIC.
-  C is highly portable this means that programs once written can be run on another machines with little or no modification.
- Another important feature of C program, is its ability to extend itself.
-  A C program is basically a collection of functions that are supported by C library. We can also create our own function and add it to C library.
-  C language is the most widely used language in operating systems and embedded system development today.
![features.jpg]({{site.baseurl}}/features.jpg)


## TOKENS:
Totally tokens are six types, Those are
- **Identifiers** ( {0,1….,9}, {A,B,….,Z},{a,b,…..,z},{special characters})
- **Keywords** (auto, char, double, int, struct, enum,…..,etc... )
- **constants** (integer constants, character constants, floating constants, enumeration constants)
- **String literals** (string constant)
- **Operators** (arithmatic, logical, Decrement, Bitwise, Assignment, unary, Ternary, Relational, Conditional)
- **Separators** (white space, and ;)
[https://www.cs.uic.edu/~jbell/CourseNotes/C_Programming/CharacterStrings.html](https://www.cs.uic.edu/~jbell/CourseNotes/C_Programming/CharacterStrings.html)


## DATA TYPES: 
### PRIMARY DATA TYPES
**1) char 	 
2) integer	
3) float 	
4) void**

![data_types.jpg]({{site.baseurl}}/data_types.jpg)

### DERIVED DATA TYPES
Derived data are nothing but primary data types but a little twisted or grouped together like array, stucture, union and pointer.

**Data types sizes depend upon machine OS type { 8bit, 16bit, 32bit , 64bit }**

 
**Ex**:-   sizeof(**int**)=**1**byte(**8bit**),**2**bytes(**16bit**),**4**bytes(**32bit**) and **8**bytes(**64bit**)

### Integer type
Integers are used to store whole numbers.
### Size and range of Integer type on 16-bit machine:
![int.png]({{site.baseurl}}/int.png)


**Floating point type**

Floating types are used to store real numbers.

**Size and range of Integer type on 16-bit machine**
![float.png]({{site.baseurl}}/float.png)


**Character type**

Character types are used to store characters value.

**Size and range of Integer type on 16-bit machine**
![char.png]({{site.baseurl}}/char.png)

**void type**

void type means no value. This is usually used to specify the type of functions which returns nothing. We will get acquainted to this datatype as we start learning more advanced topics in C language, like functions, pointers etc.



