# c-interview-questions

1)what is array?

An array is a collection of  data elements of the same data type stored in contiguous memory locations. Each element is accessed using an index, starting from 0.

2)what is the difference between array and string?

An array is a collection of elements of the same data type, whereas a string is a character array terminated by the null character ('\0'). it stores only characters .

3)what is contiguous memory allocation?

it is a method of storing elements in consecutive memory locations without any gaps.  (or) storing elements right next to the previous element without no gaps.

4)what is pointer?
 
A pointer is a user defined data type which is used to store the address of variable 

5) what are the types of pointers?
 types of pointers 
 1.NULL pointer 
 2.void pointer 
 3.wild pointer 
 4.darling pointer 

6) what is null pointer?

Null pointer points nothing .it indicates that the pointer is not pointing to any memory address.

7) what is wild pointer?

A pointer which is declared  but not initialized.

8) what is double pointer?

A pointer which stores the address of a pointer not a normal variable.

9) what is void pointer?
A pointer which stores the address of any data type.

10) what is * and &?

dereference operator which is used to return the value
address operator which is used to return the address .

11) what is a structure?

A structure is a user-defined data type. we can store hetrogeneous data items .
bascially structure is a collection of different data items under a single varaiable .these data items are called members.
syntax
struct tag{
int rollno;
char name[20];
};s;

12) what is union in c?

A union is also a collection of diferent data items as like a structure, but it's shares only single memory,the memory size is depends on the data type which is taking a more bytes in memory .it overwritten the previous data because it is sharing single memory.
syntax
union tag{
int a;   //4bytes in 32-bit machine
float g; //4 bytes in 32-bit machine
short int f; //2 bytes in 32-bit machine
here the memory size is 4 bytes.

13) what is typedef?

typedef is a keyword which is used to crate a newname for exisisted data type.it is easy to use ,commonly used in struct and union.

14) what is structure padding?

structure padding is the extra memory is added by the complier between structure members that data is properly aligned in memory.

15) what is the use of structure padding?

improves processor performance
faster memory access

16) what is structure packing?

structure packing is used to reduce the wastage of memory which is added by the complier between structure members.efficient use of memory
syntax
#pragma pack(push,1)
struct tag{
int a;
char a[20];
};s;

17) what are the disadvantages of structure packing in c?

slower memory access
reduced performance
complier and platform dependence

18) 








 








