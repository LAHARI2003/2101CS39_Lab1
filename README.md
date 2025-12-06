# C Programming Projects

This repository contains two C programs: a simple calculator and a sorting algorithm demonstration.

## Programs

### 1. Calculator Program (`cal prog.c`)

A simple command-line calculator that performs basic arithmetic operations on two operands.

#### Features
- Addition (+)
- Subtraction (-)
- Multiplication (*)
- Division (/)

#### Compilation
```bash
gcc "cal prog.c" -o calculator
```

#### Usage
```bash
./calculator
```

The program will prompt you to:
1. Enter an operator (+, -, *, /)
2. Enter two operands

#### Example
```
Enter an operator (+, -, *, /): +
Enter two operands: 10 5
10.0 + 5.0 = 15.0
```

---

### 2. Sorting Program (`sorting.c`)

An interactive program that demonstrates five different sorting algorithms. Users can choose which algorithm to use and provide their own array to sort.

#### Implemented Algorithms
- **I** - Insertion Sort
- **S** - Selection Sort
- **B** - Bubble Sort
- **Q** - Quick Sort
- **M** - Merge Sort

#### Compilation
```bash
gcc sorting.c -o sorting
```

#### Usage
```bash
./sorting
```

The program will prompt you to:
1. Enter the type of sorting algorithm (I, S, B, Q, or M)
2. Enter the size of the array
3. Enter the elements of the array

#### Example
```
Enter the type of Sorting you wish to do(I S B Q M): Q
Enter the size of array: 5
Enter the elements of array:
64 34 25 12 22
122253464
```

**Note:** The output displays the sorted array without spaces. In the example above, the sorted array `[12, 22, 25, 34, 64]` is printed as `122253464`.

#### Algorithm Details

- **Insertion Sort**: Builds the sorted array one element at a time by inserting each element into its correct position.
- **Selection Sort**: Repeatedly finds the minimum element and places it at the beginning.
- **Bubble Sort**: Repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order.
- **Quick Sort**: Uses a divide-and-conquer approach with a pivot element.
- **Merge Sort**: Divides the array into halves, sorts them, and merges them back together.

## Requirements

- GCC compiler (or any C compiler)
- Linux/Unix environment (or compatible system)

## Compilation Notes

- The calculator program filename contains a space, so use quotes when compiling: `gcc "cal prog.c"`
- Both programs use standard C libraries (`stdio.h`) and should compile on any standard C compiler.

## Author

This project contains educational C programming examples demonstrating basic arithmetic operations and various sorting algorithms.
