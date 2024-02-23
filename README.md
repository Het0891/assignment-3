# Vowel Counting Program 

This C program counts the number of vowels in a given string using an inline function. The program compares the size and runtime performance with and without using the `inline` keyword.

## Files

- `main.c`: Contains the logic Program

## Functions

- `static inline int cnt_vowels(char *str)`: An inline function to count vowels in a string.
- `void call_inline_function(char *str)`: Calls the `cnt_vowels` function using inline.
- `void call_function(char *str)`: Calls the `cnt_vowels` function without using inline.

## How to Use

1. Compile the program using a C compiler (e.g., gcc).
2. Run the compiled executable.
3. Enter a string when prompted.
4. The program will count the number of vowels in the string and display the result.

## Performance Analysis

- Measure the size of the resulting binary using `size`, `objdump`, or `readelf`.
- Measure the system time taken to execute the program using the `clock` function.
