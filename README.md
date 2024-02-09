# Java

learning java programming languege for my first time

\*_ In Java, you compile you code everytime in other to see the result of your work. and to compile you use the Command _ javac then the name fo the file you want to compile\*. and if the file successfully compiles you will get a .class file. thats the file that gets render to the terminal and you do so using the following Command line java Practice ( the name to the compiled file)

# VARIABLES IN JAVA

we have primitive data type used in declaring variable which are _init, boolen, double_
and they are built-in data types.

In Java, whole numbers are stored in the int primitive data type.

// int variable declaration
int yearJavaWasCreated;
// assignment
yearJavaWasCreated = 1996;
// declaration and assignment
int numberOfPrimitiveTypes = 8;

// doubles can have decimal places:
double price = 8.99;
// doubles can have values bigger than what an int could hold:
double gdp = 12237700000;

The char data type can hold any character, like a letter, space, or punctuation mark.

It must be surrounded by single quotes, '.

For example:

char grade = 'A';
char firstLetter = 'p';
char punctuation = '!';

\*\* Learn Java: Variables
String

So far, we have learned primitive data types, which are the simplest types of data with no built-in behavior. Our programs will also use Strings, which are objects, instead of primitives. Objects have built-in behavior.

Strings hold sequences of characters. We’ve already seen instances of a String, for example, when we printed out "Hello World". There are two ways to create a String object: using a String literal or calling the String class to create a new String object.

A String literal is any sequence of characters enclosed in double-quotes (""). Like primitive-type variables, we declare a String variable by specifying the type first:

String greeting = "Hello World";

We could also create a new String object by calling the String class when declaring a String like so:

String salutations = new String("Hello World");

There are subtle differences in behavior depending on whether you create a String using a String literal or a new String object. We’ll dive into those later, but for now, we’ll almost always be using String literals.

Keep Reading: AP Computer Science A Students

Certain symbols, known as escape sequences, have an alternative use in Java print statements. Escape sequences are interpreted differently by the compiler than other characters. Escape characters begin with the character \.

There are three escape sequences to be aware of for the AP exam.

The \" escape sequence allows us to add quotation marks " to a String value. :

System.out.println("\"Hello World\"");
// Prints: "Hello World"

If we didn’t use an escape sequence, then Java would think we’re using " to end the String!

Using the \\ escape sequence allows us to place backslashes in our String text:

System.out.println("This is the backslash symbol: \\");
// Prints: This is the backslash symbol: \

This is similar to the last example - just like ", \ usually has a special meaning. In this case, \ is used to start an escape sequence. Well, if we don’t want to start an escape sequence and just want a \ in our String, then we’ll use \\ — we’re using an escape sequence to say that we don’t want \ to be interpreted as the start of an escape sequence. It’s a little mind-bending!

Finally, if we place a \n escape sequence in a String, the compiler will output a new line of text:

System.out.println("Hello\nGoodbye");
/_
Prints:
Hello
Goodbye
_/

You can think of \n as the escape sequence for “newline”.
\*\*
