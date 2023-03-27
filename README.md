0x11. C - printf
This is a project for ALX SE Program focused on recreating the printf function in C. The project aims to help students develop a deeper understanding of the inner workings of the printf function, as well as develop their skills in C programming, memory management, and project organization.

Functionality
The recreated printf function, which we will call _printf, will work similarly to the original printf function. It will take in a format string, which specifies how the output should be formatted, and any number of additional arguments to be printed according to that format.

The format string can include various conversion specifiers, such as %s for strings, %d for integers, and %c for characters. These specifiers will be replaced in the output string with the corresponding values from the additional arguments passed to the function.

In addition to the basic conversion specifiers, our _printf function will also support a number of additional options, such as width and precision modifiers, as well as flags for left justification, zero padding, and more.

Usage
The _printf function can be called like any other function in C, with the format string as the first argument, followed by any additional arguments.

Files
The following files are included in this project:

main.h: Header file containing function prototypes and struct declarations.
get_print_func.c: File containing a function that retrieves the correct print function based on the format specifier.
print_char.c: File containing a function to print a single character.
print_string.c: File containing a function to print a string.
print_integer.c: File containing a function to print an integer.
print_binary.c: File containing a function to print a binary number.
print_unsigned.c: File containing a function to print an unsigned integer.
print_hex.c: File containing functions to print a hexadecimal number.
print_octal.c: File containing a function to print an octal number.
print_address.c: File containing a function to print a memory address.
_printf.c: Main file containing the _printf function.
man_3_printf: Manual page for the _printf function.
teamwork(MehdiFatheddine, ABDELHAMID HMIDANI)
