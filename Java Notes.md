JAVA

1. What is Java?
    Java is a high level, Object oriented, Platform independent programming language.
    It was developed by Sun micro system in 1995, later occupied by Oracle.
    James Gosling is the author of java.

2. What is JVM?
    Java Virtual Machine.
    JVM is the machine that runs the java program.
    Converts bytecode (.class) into machine code

3. What is JRE?
    Java Runtime Environment.
    JRE provides everything needed to run the java application.
    It provides core libraries like java.lang, java.util, etc..

4. What is JDK?
    Java Development Kit.
    JDK is used to develop the java application.
    It has developer tools like javac(compiler), java(runner), jdb(debugger) & jar(packaging tool).

5. What is Variable?
    Variable is a container used to store data in the memory.
    Types of variable:
        1. Local variable:
            Stored inside a method or block.
            Must be initialized before use.
        2. Instance variable:
            Declared inside a class but outside the method.
            Each object gets it own copy.
        3. Static variable:
            Declared using static.
            Shared among all object.

6. What is Datatype?
    Datatype is a kind of value need to stored inside the memory.
    There are two types of datatype:
        1. Primitive datatype:
            byte, short, int, long, float, double, char & boolean.
        2. Non primitive datatype:
            String, Array, Classes & Interfaces.

7. What is Typecasting?
    Typecasting in java means converting one datatype into another datatype.
    There are two types of typecasting:
        1. Widening casting (Implicit casting):
            Automatic casting, Smaller to larger datatype, No dataloss.
        2. Narrowing casting (Explicit casting):
            Manual casting, Larger to smaller datatype, Data loss may occur.

8. What is Type promotion?
    Java automatically converts smaller types in expressions.
    byte a = 1;
    byte b = 2;
    int c = a + b;

9. What is Wrapper class?
    Every primitive type in java has corresponding wrapper class.
    int a = 10;
    Integer b = a;

10. What is Autoboxing & Unboxing?
    Autoboxing:
        Automatic conversion of primitive datatype into wrapper object.
        Integer a = 10;
        Integer a = Integer.valueOf(10); // Internal process
    Unboxing:
        Automatic conversion of wrapper object into primitive datatype.
        Integer a = 10;
        int b = a;
        int b = a.intValue();

11. What is Operator?
    Operators are symbol which are used to perform operations.
    1. Arithematic Operator: Used to perform mathematical operations. (+, -, *, /, %).
    2. Relational Operator: Used to compare two values. (==, !=, >, <, >=, <=).
    3. Logical Operator: Used to combine conditions. (&&, ||, !).
    4. Assignment Operator: Used to assign values. (=, +=, -+, *=, /=).
    5. Unary Operator: Used to operate on single value. (+, -, ++, --).
    6. Bitwise Operator: Used to perform on bit level operations. (& AND, | OR, ^ XOR, ~ NOT, << LEFT SHIFT, >> RIGHT SHIFT).
    7. Ternary Operator: Shortcut method of If-Else. (? :).
    8. InstanceOf Operator: Checks the type of object.
        String name = "Java";
        System.out.println(name instanceof String); // Output: true.

12. What is Control Statement?
    Control statement is used to control the flow of execution in the program.
    1. Decision making statement:
        1. If Statement: It is used to execute the set of code when the condition is true.
        2. If Else Statement: It provides an alternative block when the condition is false it executes the set of block.
        3. If Else If Statement: It is used when there are multiple conditions are present.
        4. Switch Statement: It is used to select one case from the multiple conditions to execute.
    2. Looping statement:
        1. For Loop: Used when the number of iteration is known.
        2. While Loop: Executes the condition while the statement is true.
        3. Do-While Loop: Executes the loop atleast one time, even the condition is false.
    3. Jump statement:
        1. Break: Terminates the loop.
        2. Continue: Skips the current iteration.
        3. Return: Exit from the method.

13. What is Array?
    Array is an object container which holds fixed number of same values.
    It is used to store multiple values in single variable.
    Easy to manage large data sets.
    Faster access through index.

    int[] a; or int a[];
    To initialize it int[] a = new int[5]; or int[] a = {10, 20, 30};
    Accessing array with index int a[] = {10, 20, 30}; System.out.println(arr[1]);

    Types of array:
        1. Single dimensional array: int[] a;
        2. Multi dimensional array: int[][] a = {
            {1,2,3},{4,5,6}
        };

14. What is Object Array?
    Object array in java is used to store the objects instead of primitive values.
    class Student{
        int id;
        String name;
        public static void main(String arg[]){
            Student[] students = new Student[3];

            students[0] = new Student(1, "Hari");
            students[1] = new Student(2, "Vijay");
            students[2] = new Student(3, "Kumar");
        }
    }

15. What is String Methods?
    String methods are used to manipulate the string with the inbuilt methods.
    1. Length & Character: length(), charAt(int index).
    2. Comparison Methods: equals(String s), equalsIgnoreCase(String s), compareTo(String s).
    3. Searching Methods: indexOf(String s), lastIndexOf(String s), contains(CharSequence s).
    4. Substring Methods: substring(int startIndex), substring(int startIndex, int endIndex).
    5. Case Conversion Methods: toUpperCase(), toLowerCase().
    6. Trimming & Replacing: trim(), replace(old, new), replaceAll(regex, replacement).
    7. Splitting & Joining: split(String regex), join(delimiter, elements).
    8. Other useful methods: startsWith(), endsWith(), isEmpty(), concat().

16. What is OOPs concept?
    Object Oriented Programming is an programming approach concept using class and object instead of using function and logic.
    There are 4 main concept in OOPs concept.
        1. Encapsulation
        2. Inheritance
        3. Polymorphism
        4. Abstraction

17. What is Encapsulation?
    Encapsulation is a process of binding data and methods in a single class which restrict the direct access to it. Aslo called as Data hiding.
    class Student{
        private int mark;
        public void setMark(int a){
            mark = a;
        }
        public void getMark(){
            return mark;
        }
    }

18. What is Inheritance?
    Inheritance is a process of accquiring the properties and behaviours of another class.
    1. Single Inheritance - One child class inherits from parent class
    2. Multilevel Inheritance - It is a chain of inheritance. Grand Parent -> Parent -> Child.
    3. Hierarchical Inheritance - One parent class have multiple child class.
    4. Multiple Inheritance - Java doesn't support multiple inheritance to avoid ambiguity error. It is acheived using Interface. 

19. What is Polymorphism?
    Polymorphism means "Many forms". One method or objects behaves differently based on the situation. One name, multiple behaviours.
    1. Compile time polymorphism: Also called as method overloading or early binding or static binding. The method decide on the compile time based on numbers, types and order of the parameters. Example: Method overloading.
    2. Run time polymorphism: Also called as method overriding or late binding or dynamic binding. The method decide on the run time based on objects. Example: Method overriiding.

20. What is Abstraction?
    Abstraction is the process of hiding implementation details and showing necessary functionality for the users.
    It is acheived in two ways: Abstract class & Interface.
    1. Abstract class: It is declared using abstract keyword. It can have abstract classes with no body and concrete classes with body. It cannot create object for abstract class. Must be extended. Can have constructor and variables.
    2. Interface: It is declared using interface keyword. All methods are abstract by default. Cannot create object for interface. Class uses implements. Supports multiple inheritance.