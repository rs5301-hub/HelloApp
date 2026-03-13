# HelloApp Use Case Documentation
## UC3 – Display "Hello" with Command-Line Argument or Default Message

### Description
The application accepts a user's name as a command-line argument and displays a personalized greeting. If no name is provided, the program uses the default value "World".

### Preconditions
The application is launched with or without a command-line argument.

### Main Flow
1. User runs the application with or without a name argument.
2. The program checks if a command-line argument exists.
3. If an argument exists, the program reads the name from `args[0]`.
4. If no argument exists, the program assigns the default value **"World"**.
5. The program prints the greeting message.

### Postconditions
A greeting message is displayed using either the provided name or the default value.


### Concepts Learned
- Command-line arguments using `String[] args`
- Checking array length using `args.length`
- Conditional logic
- Default values
- Ternary operator
