
# HelloApp Use Case Documentation

## UC6 – Display "Hello" with Multiple Command-Line Arguments using substring()

### Description
The application accepts multiple command-line arguments and displays a greeting. It uses an enhanced for loop to process names and the substring() method to remove the trailing delimiter. If no arguments are provided, it displays "Hello, World!".

### Preconditions
The application is launched with zero or more command-line arguments.

### Main Flow
1. User runs the application with or without names.
2. If no arguments are provided, the program prints "Hello, World!".
3. If arguments are provided:
   - The program iterates through all names using an enhanced for loop.
   - Each name is appended with ", ".
4. The trailing comma and space are removed using `substring()`.
5. The final greeting is printed.

### Postconditions
A greeting message is displayed with all names or the default message.


### Concepts Learned
- Enhanced for loop
- StringBuilder usage
- substring() method
- Removing trailing delimiters
- Default value handling
