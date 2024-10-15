# pointerOperations
## Aim 
To study pointer operations

## Software Used 
VS Code

## Theory
<br>
In C++, functions can receive parameters in different ways, influencing how the function manipulates the provided values. Two common methods are Call by Reference and Call by Value:
<br>

### Call by Reference  

**Definition:** Call by Reference means passing the address (reference) of the actual parameters to the function. This allows the function to modify the original values.  

**Working:** The function receives pointers to the variables, and operations performed inside the function affect the original variables directly.

### Call by Value 

**Definition:** Call by Value means passing a copy of the actual parameters to the function. Changes made to the parameters inside the function do not affect the original variables.

**Working:** The function operates on copies of the values, leaving the original variables unchanged.
| Features                | Call by Reference                      | Call by Value                        |
|---------------------------|----------------------------------------|--------------------------------------|
| **Definition**            | Passes the address (reference) of the actual parameter. | Passes a copy of the actual parameter. |
| **Function Parameters**   | Function receives pointers or references to the original variables. | Function receives copies of the original values. |
| **Effect on Original Data**| Modifies the original data.            | Does not modify the original data.  |
| **Example**        | `void swap(int *x, int *y)`            | `void swap(int x, int y)`            |
| **Modification of Values**| Changes made in the function affect the original variables. | Changes made in the function do not affect the original variables. |
| **Memory Usage**          | Uses memory for pointers/references.   | Uses memory for copies of values.    |
| **Performance**           | More efficient for large data structures due to avoiding copying. | Can be less efficient for large data structures due to copying. |
| **Use**              | Used when the function needs to modify the input variables. | Used when the function should not alter the input variables. |

<br>  

**Conclusion**

we learnt the pointer operations
