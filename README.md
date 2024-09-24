# Pointer Basics
Experiment 9

## Aim 
To understand and use basic pointers.

## Software Used 
VS Code

## Theory
**Definition**  
A pointer is a variable that stores the memory address of another variable. It doesn’t hold data itself but points to the location in memory where the data is stored. Pointers facilitate efficient array and memory management, enabling direct memory manipulation. They are particularly useful for operations involving data structures.

Basic syntax to define a pointer:
```cpp
int a = 5;
int *ptr = &a;
```

**Features of Pointers**  
- Access any array type without worrying about its size.
- Used in file handling.
- Enable dynamic memory allocation.

**Advantages of Pointers**
- **Memory Efficiency:** Allow data sharing between different parts of a program.
- **Improved Performance:** Can reduce code size and enhance performance.
- **Multiple Values:** Enable returning multiple values from functions.
- **Data Structures:** Facilitate building complex structures like linked lists and trees.

**Drawbacks of Pointers**
- Requires an additional dereference step.
- Forgetting to deallocate memory can lead to memory leaks.

## Algorithms
### Pointer Address
1. **Start**
2. **Initialize Variables**
   - Declare an integer `a` and set it to 10.
   - Declare an integer pointer `aptr` and assign it the address of `a`.
3. **Print Values**
   - Print the value pointed to by `aptr`.
   - Print the address stored in `aptr`.
   - Print the address of `a`.
4. **End**

### Pointer Increment
1. **Start**
2. **Initialize Variables**
   - Define `a` with value 10 and pointer `ptr` to `a`.
   - Define `b` (float) with value 9.4 and pointer `fptr` to `b`.
   - Define `c` (char) with value 's' and pointer `cptr` to `c`.
   - Define `d` (bool) with value `true` and pointer `dptr` to `d`.
3. **Integer Pointer Operations**
   - Print "For integer."
   - Print the address in `ptr` before incrementing.
   - Increment `ptr`.
   - Print the new address in `ptr`.
4. **Float Pointer Operations**
   - Print "For float."
   - Print the address in `fptr` before incrementing.
   - Increment `fptr`.
   - Print the new address in `fptr`.
5. **Boolean Pointer Operations**
   - Print "For boolean."
   - Print the address in `dptr` before incrementing.
   - Increment `dptr`.
   - Print the new address in `dptr`.
6. **Character Pointer Operations**
   - Print "For character."
   - Print the address in `cptr` before incrementing.
   - Increment `cptr`.
   - Print the new address in `cptr`.
7. **End**

## Conclusion
We learned the basics of pointers.
