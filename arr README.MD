c interview questions in array topic

1) what is array?

An array is a collection of  data elements of the same data type stored in contiguous memory locations. Each element is accessed using an index, starting from 0.

2) what is the difference between array and string?

An array is a collection of elements of the same data type, whereas a string is a character array terminated by the null character ('\0'). it stores only characters .

3) what is contiguous memory allocation?

it is a method of storing elements in consecutive memory locations without any gaps.  (or) storing elements right next to the previous element without no gaps.

4) can an array size be changed after declaration?

No.In C,the size of a normal array cannot be changed after it is declared.Because it is stored or created  in static memory allocation so the size is not changed.

5) What is the difference between array and pointer?

Array is a collection of data elements of same data type the memory is allocated in static memory,and the size is fixed.
pointer is used to store the address of an variable ,memory can be allocated dynamically .

6) What happens if you access an array out of bounds?

Accesssing an array out of bounds result in a undefined behaviour because C does not check array bounds at runtime.

7) what are th advantages of array?

Easy to access
Fast to access
Reduce the number of  variables needed to a program

8) What are the disadvantages of arrays?

Fixed size -cannot be changed after declaration
insertion and deletion are costly because it takes time to shift the elements.
if the size of an array is larger than needed it is wase of memory.

9) why can't an array be assigned to another array using=?

we cannot aasigned array using assigment operator because the array name is not modifiable variable.it represents the address of the first element and is not assignable.

10) what is diferrence between one-dimensional array and a two-dimensionala array?

In one dimensinal array uses one index to store the data linearly,where as in two dimensional it uses two iindices to store the data in rows and columns.

