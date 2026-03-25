# HelloApp Use Case Documentation
## UC5 – Display "Hello" with Multiple Command-Line Arguments using Enhanced For Loop

### Description
The application accepts zero or more command-line arguments and prints a greeting. It uses an enhanced for loop (for-each loop) to process multiple names. If no arguments are provided, it displays the default greeting "Hello, World!".

### Preconditions
The application is launched with zero or more command-line arguments.

### Main Flow
1. User runs the application with or without names.
2. The program checks if any arguments are provided.
3. If no arguments are provided, the program uses the default value **"World"**.
4. If arguments are provided, the program iterates through `args` using an enhanced for loop.
5. The program builds a comma-separated list of names.
6. The program prints the greeting message.

### Postconditions
A greeting message is displayed with all provided names or the default **"Hello, World!"**.


### Concepts Learned
- Enhanced for loop (`for-each`)
- Handling multiple command-line arguments
- Using `StringBuilder` for efficient string construction
- Conditional logic for default values
- Building formatted output (comma-separated values)
