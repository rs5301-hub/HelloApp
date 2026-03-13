# HelloApp Use Case Documentation
## UC4 – Display "Hello" with Multiple Command-Line Arguments

### Description
The application accepts multiple names as command-line arguments and displays a greeting including all names. If no names are provided, the program defaults to "World".

### Preconditions
The application is launched with zero or more command-line arguments.

### Main Flow
1. User runs the application with multiple names or no names.
2. The program checks if command-line arguments are provided.
3. If arguments exist, the program reads all names from the `args` array.
4. The program joins the names with commas and spaces.
5. If no arguments exist, the program uses the default value **"World"**.
6. The program prints the greeting message.

### Postconditions
A greeting message is displayed with all provided names separated by commas, or the default message **"Hello, World!"**.


### Concepts Learned
- Handling multiple command-line arguments
- Working with arrays (`args[]`)
- Using loops or `String.join()` to process multiple inputs
- Default values when no arguments are provided

Input:

