1) what is a structure?

A structure is a user-defined data type. we can store hetrogeneous data items .
bascially structure is a collection of different data items under a single varaiable .these data items are called members.
syntax
struct tag{
int rollno;
char name[20];
};s;

2) what is union in c?

A union is also a collection of diferent data items as like a structure, but it's shares only single memory,the memory size is depends on the data type which is taking a more bytes in memory .it overwritten the previous data because it is sharing single memory.
syntax
union tag{
int a;   //4bytes in 32-bit machine
float g; //4 bytes in 32-bit machine
short int f; //2 bytes in 32-bit machine
here the memory size is 4 bytes.

3) what is typedef?

typedef is a keyword which is used to crate a newname for exisisted data type.it is easy to use ,commonly used in struct and union.

4) what is structure padding?

structure padding is the extra memory is added by the complier between structure members that data is properly aligned in memory.

5) what is the use of structure padding?

improves processor performance
faster memory access

6) what is structure packing?

structure packing is used to reduce the wastage of memory which is added by the complier between structure members.efficient use of memory
syntax
#pragma pack(push,1)
struct tag{
int a;
char a[20];
};s;

7) what are the disadvantages of structure packing in c?

slower memory access
reduced performance
complier and platform dependence

8) what is file handling?

when we want to store the program or data permanently in a file we use file handling.
we can read,write,store,fetch, delete or add,open or close the data in file.

