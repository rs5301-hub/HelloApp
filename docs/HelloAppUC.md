# HelloApp Use Case Documentation

## UC1 – Display "Hello World"

### Description
The application displays "Hello World" in the console when the program is executed. This demonstrates a basic Java application that prints text to the console.

### Preconditions
- The application is launched.

### Main Flow
1. User runs the application.
2. The application executes the `main()` method.
3. The program prints **"Hello World"** to the console.
4. The application terminates.

### Postconditions
- The message **"Hello World"** is displayed to the user.

### Example Output


## UC2 – Display Hello with Command-Line Argument

### Description
The application accepts a user's name as a command-line argument and displays a personalized greeting.

### Preconditions
Application is launched with a name argument.

### Main Flow
1. User runs the application with a command-line argument.
2. The program reads the name from `args[0]`.
3. The program prints "Hello, <name>!".

### Postconditions
A personalized greeting message is displayed.

### Example Output
Input: java HelloApp Alice  
Output: Hello, Alice!