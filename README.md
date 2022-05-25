## Java Basic Assignment 1
1. What is a programming language? What is Java and what is Java used for?
Ans: A progamming language is a computer language that is used by programmers to communicate with computers. Java is a high level, class based, object oriented programming language that is designed to have as few implementation dependencies as possible. Java is used as the server-side language for most back-end develoement projects, including those involving big data and Android development. Java is also commonly used for desktop computing, other mobile computing, games and numerical computing.
2. Which version of Java you are working with? How can you find out the version of Java you are using?
Ans: java version "1.8.0_202"
Java(TM) SE Runtime Environment (build 1.8.0_202-b08)
Java HotSpot(TM) 64-Bit Server VM (build 25.202-b08, mixed mode)

You can find out the version of java by typing "java -version" on the command prompt.
3. What is IDE? Which IDE you are working with? 
Ans: IDE stands for Itegrated Development Environment. IDE is a software suit that consolidates the basic tools developers need to write and test softwares. Typically an IDE consists of a text-editor, a compiler and a debugger that the developer accesses through a single graphical user interface.
4. What is source code? What is file extension for Java source code?
Ans: Source code is the set of instructions and statements written by a programmer using a computer programming language. 
A file with the JAVA file extension is a Java source code file written in the Java programming language.
5. What is the second stage of Java life cycle?
Ans: The second stage of Java life cycle is compilation.
6. Which compiler is used for compiling Java file? 
Ans: The compiler used for compiling Java is javac.
7. What files are the input and output of the compilation stage?
Ans: Input for compilation stage is "*.java" files. Output is *.class" file.
8. Which command is used to call Java compiler in terminal or CMD?
Ans: javac.
9. What is the third stage of Java Life Cycle? 
Ans: Execution.
10. At which stage class loader is used and what function does it perform?
Ans: At execution stage class loader is used. It loads the bytecodes from ".class" file into memory.
11. Which unit is responsible for translating bytecodes into machine code?
Ans: JVM (Java Virtual Machine) is responsible for translating bytecodes into machine codes.
12. What is last stage of Java Life Cycle?
Ans: Execution.
13. Which command is used to run Java program in terminal or CMD?
Ans: java command followed by the name of ".class" file.
14. At what stage bytecode verifier is used? 
Ans: Execution.
15. What is JDK? Briefly explain the components of JDK.
Ans: The Java Development Kit (JDK) is a cross-platformed software development environment that offers a collection of tools and libraries necessary for developing Java-based software applications and applets.
JDK has many components, some of them are as follows:
The Runtime Interpreter: The runtime interpretor provides the support to run Java executable programs in compiled, bytecode format.
The Compiler: The Java compiler is used to compile source code files into executable Java bytecode classes.
The Applet Viewer: The applet viewer is a tool that serves as a minimal test bed for final release Java applets. 
The Debugger: Debugger debugs the piece of code.
The Class File Disassembler: Disassembles class file.
The Header and stub file generator: Generates header and source files that are required to emplemnt native methods.
The Document Generator: Generates HTML pages of API documentation from Java source files.
16. Name main components present in JVM and write function of each component.
Ans: JVM consists of nine main components.
        1. Class Loader: The class loader loads ".class" file into the main memory.
        2. Method Area: It stores class structures like metadata and the code for methods.
        3. Heap: All the object, their related instance variables, and arrays are stored in heap.
        4. JVM Language Stacks: Java language stacks store local variables and its partial results.
        5. PC Registers: PC Register store the address of the JVM instruction which is currently executing.
        6. Native Method Stacks: Holds the instruction of native code dependant of the native library.
        7. Execution Engine: It is used to test hardware, software, or complete systems.
        8. Native Method Interface: The native method interface os a programming framework that allows Java code which is running in a JVM to call by libraries and native applications.
        9. Native Method Libraries: Native libraries is a collection of the Native libraries which are needed by the execution engine.
17. What is JRE? In which stage of Java life cycle JRE is used?
Ans: Java Runtime Environment (JRE) is an open-access software distribution that has a Java class library, specific tools, and a separate JVM. 
In exection stage JRE takes the Java code, combines it with needed libraries and starts the JVM to execute it.
18. What is the syntax? Make a list of rules(you learned in a class) you should always follow while creating your Java application.
Ans: Syntax refers to the rules that define the structure of a language.
Some Java syntax rules are as follows:
        1. The file name must be identical to the class name.
        2. Charecters are case sensitive, String is not equal to string.
        3. The beginning of Java program processing always starts in the main method.
        4. The first letter of a class is is in uppercase. When using multiple words use uppercase for first letter of each word.
        5. Names of all methods begin with a lowercase letter. When using multiple words, the subsequent first letter of each word start with uppercase.
        6. Files are saved with class name and .java extension.
        7. "{}" denotes a block of code.
        8. Each code statement must end with a ';'.
19. How should we name our Java application? 
Ans: Java file name should always be the same as the class name.
20. Write a structure of a simple Java application.
Ans:  A typical structure of a Java application consists of the following elements:
        * Documentation Station
        * Package Declaration
        * Import Statements
        * Interface Section
        * Class Definition
        * Class Variables
        * Main Method Class
        * Methods and Behaviors
21. What is the importance of comments in the program? Mention different ways in which we can write comments in a program. 
Ans: Comments are text notes added to the program to provide explanatory information about the source code. They are used to document the program and to remind the programmers of what tricky things they just did with the code and also helps the later generation for understanding and maintenance of code.
Different language have different ways to write comments. In Java or C or C++ a single line of comment is denoted using '//' and multi line is denoted using '/*.....*/'. In Python '#' is used to denote comments. In HTML "<!--..........-->" us used to denote comments.
22. Write a simple Java program to print the “Hello World” message. Keeping in mind stages of Java Life Cycle draw a flow chart to show journey of your first program

23. What is file extension for Java executable code? At which stage of Java Life Cycle we get executable code?
Ans: .class. After compilation stage.
24. When does compile time starts?
Ans: Compile is the time when the source code is converted into a executable code.
25. Compile time ends with generation of which file?
Ans: .class file.
25. Can you run the program without compilation? Try running your first program without compilation and share result. 
Ans: no.
Error: Could not find or load main class helloworld

26. When does runtime start? 
Ans: It is the time that a program is running alongside all the external instructions needed for proper execution.
27. During which phase .class file is loaded into memory runtime or compile time? Who loads .class file into memory? 
Ans: Execution phase. Class loader load .class files into memory.

## Assignment 2 (Variable and Data Types)
1. What do you understand by variable?
Ans: In programming, variable is a value that can change, depending on conditions or on information passed to the program.
2. Name types of variables.
Ans: String, int, char, float, double, boolean.
3. What is the difference between static and instance variables?
Ans: Instance variables are created when an object is created with the use of keyword "new" and destroyed when the object is destroyed. Static variables are created when the program starts and destroyed when the program stops. Instance variables can be accessed directly by calling the variable name inside the class.
4.	Which type of variable requires a keyword to determine its scope?
        Ans: 
5.	Which thing specifies the size and type of variable?
6.	Can we use a variable without declaring it?
        Ans: No. 
7.	How can we declare a variable?
        Ans: To declare a variable  we will specify the type, leave at least one space, then the name for the variable and end the line with a semicolon(;).
8.	How can we initialize a variable?
        Ans: Add an equal sign (=) to the right of the variable name. To the right of the equal sign, write an expression.
9.	Make a list of common Java data types.
        Ans: String, int, double, float, char, boolean.
10.	Which data types are created by programmers and are not defined by Java?
        Ans: Class, object, array, String, and interface are called non-primitive data type and they are not predefined in java. They are created by programmers.
11.	Java has how many primitive data types?
        Ans: java has 8 primitive data type.   
12.	What data type would you use for storing the number of students in a class?
        Ans: int.
13.	What data type would you use for storing the average test score in a class?
        Ans: double.
14.	How would you declare a variable storing the tax rate?
        Ans: double.
15.	How would you declare a variable that tells the grade (A, B, C, or D) of students?
        Ans: char.
16.	List the name conventions you learned in class about variables.
        Ans: Lower camel case syntax.
17.	Name the Data type used for an object 'Pen'.
        Ans: Object.
18.	Write a program and declare the variable of each data type you learned in class. Initialize each variable with appropriate values and print them.  
19.	Write a program to print your name, email, address, phone number, and id. 
20.	What do you understand by typecasting?
21.	In which type casting Java automatically converts one data type to another data type?
22.	Write a program to convert int to double and print a message stating which type casting you did?
23.	Write a program to convert double to int and print a message stating which type casting you did?
24.	Write a program to convert int to string and print a message stating which type casting you did?
25.	Write a program to convert string to int and print a message stating which type casting you did?
26.	Write a program to convert float to double and print a message stating which type casting you did?
27.	Write a program to convert byte to float and print a message stating which type casting you did?
28.	Write a Java program to get the character at the 5th index of the String “automation”.
29.	Write a program to find the length of the string "automation".
30.	Write a Java program to concatenate a string “Java” to the end of another string “C#”.
31.	Write a Java program to compare a string “automation” and another string “Automation”.
32.	Write a Java program to check whether a string “Software” ends with the contents of another string “Hardware”. 
33.	Write a Java program to replace a character “n” with character “m” in the string “Automation”.
34.	Write a Java program to check whether a string “Java is my favorite programming Lang” starts with the contents of another string “Python is my favorite programming language”.
35.	Write a program to get a substring of the string “Let this be the last year tha you doubt yourself, fear, change or quit. Never give up” starting from index 10 and ending at index 26.
36.	Write a Java program to convert all the characters in a string “YourName” to lowercase.
37.	Write a Java program to convert all the characters in a string “YourName” to uppercase.
38.	Write a program to reverse a string “ Java is my favorite”. 


## Assignment 3 (Operators)
39.	What are operators?
        Ans: Operators are symbols tht perform operations on variables and values.
40.	Write the types of operators you studied in class.
        Ans: Arithmetic, Unary, Relational, and Conditional operators.
41.	The operators used in Arithmetic expressions can be classified into which type?
        Ans: 
42.	Examine the following code. The programmer is not getting the same value for result and result2. Why?
        double result = (20-10/3);
	double result = ((20-10)/3);
43.	Write a program to check if the two numbers 23 and 45 are equal.
44.	Write a Java program to find the value of specified expression. 
        a. 301 + 0) / 5
        b. 7.0e-6 * 10000000.1
	c. true && true
	d. false && true
	e. (false && false) || (true && true)
	f. (false || false) && (true && true)
45.	Length and breadth of a rectangle are 9 and 5 respectively. Write a program to calculate the area and perimeter of the rectangle.
46.	Write a program to calculate the perimeter of a triangle having sides of length 9,6 and 5 units.
47.	Write a program to find if both the conditions 'a < 50' and 'a < b' are true when value of a is 45 and b is 67.
48.	Write a program to find total marks and percentage of students when his marks in three subjects are 87, 39 and 52 respectively (each out of 100 ).
49.	Write a program to convert temperature from Fahrenheit to Celsius degree. (You can take temperature of your choice)
50.	Write a program to find largest number among three numbers: 76,54 and 89.
51.	Write a program to find smallest number among three numbers: 76,54 and 89.
52.	If num1=5 and num2=4 then write a program to swap values of these numbers.
53.	Write a program to convert positive number to negative number. (You can take any number of your choice)
54.	Consider the following code snippet.
        arrayOfInts[j] > arrayOfInts[j+1]
        a. Which operators does the code contain?
55.	Consider the following code snippet.
        int i = 10;
        int n = i++%5;
        a. What are the values of i and n after the code is executed?
        b. What are the final values of i and n if instead of using the postfix increment operator (i++), you use the prefix version (++i))?
56.	To invert the value of a boolean, which operator would you use?
57.	Write a program to show the difference between postfix expr ++ and prefix ++ expr operators. In the comments of your program explain each line of code.
58.	Write a program to show the difference between postfix expr -- and prefix -- expr operators. In the comments of your program explain each line of code.
59.	Which operator is used to compare two values, = or == ?
60.	Explain the following code sample: result = someCondition ? value1 : value2;
61.	Write a program to divide 154 with 7.
62.	Write a program to print the sum, product, difference, divide and remainder of two numbers (First number=579 and second number=17).
63.	Write a Java program to print the area and perimeter of a circle when radius of circle is 4.2 cm.
64.	Write a program that compares two number 13 and 16 are not equal.
65.	Write a program to decrease value of variable by 1 without using arithmetic operator. (Value of variable is 13)
66.	Write a program to increase value of variable by 1 without using arithmetic operator. (Value of variable is 13)
67.	Write a program that shows the message true first number is greater than second number or third number. (First number= 23, Second number = 32 and third number = 15). 
68.	Write a program that shows message true first number is greater than second number and third number. (First number= 23, Second number = 32 and third number = 15).

