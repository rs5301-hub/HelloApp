
# HelloApp Use Case Documentation
## UC7 – Display "Hello" with Multiple Command-Line Arguments using String.join()

### Description
The application accepts multiple command-line arguments and displays a greeting. It uses the String.join() method to concatenate names. If no arguments are provided, it displays "Hello, World!".

### Preconditions
The application is launched with zero or more command-line arguments.

### Main Flow
1. User runs the application with or without names.
2. If no arguments are provided, the program uses "World".
3. If arguments are provided, the program uses `String.join(", ", args)` to combine names.
4. The greeting message is printed.

### Postconditions
A greeting message is displayed with all names or the default message.

### Example Output

Input:
