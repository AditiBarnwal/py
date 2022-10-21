# py
FoR QuIck ReVisiOn
<h1>XML</h1>
<h1>Itertools</h1>
<h1>Magic functions</h1>
<h1>Error & Exceptions</h1>
<p>INCORRECT REGEX | HACKERRANK-get about regex here</p>
<h1>Built-ins</h1>
<p>about athlete sort   itemgetter</p>
<h1>Regex & Parsing</h1>
<h1>Random Numbers</h1>
<h5>Q.How do you select a random number in a list Python?</h5>
<p>Using random. randrange() to select random value from a list. random. randrange() method is used to generate a random number in a given range, we can specify the range to be 0 to the length of the list, and get the index, and then the corresponding value.</p>

<h5>Q.How do you pick a random number from a range in Python?</h5>
<p>Use a random. randint() function to get a random integer number from the inclusive range. For example, random. randint(0, 10) will return a random number from [0, 1, 2, 3, 4, 5, 6, 7, 8 ,9, 10]</p>
<h5>Q.How to generate random number using NumPy?</h5>
<p>Random integer values can be generated with the randint() function. This function takes two arguments: the start and the end of the range for the generated integer values. Random integers are generated within and including the start and end of range values, specifically in the interval [start, end].</p>
<p>Eg:</p>
                                                  <p>import numpy as np</p>
                                                  <p>random_n = np.random.randint(5, size=(8, 9))</p>
                                                  <p>print(random_n)</p>
                     
<h4>Q.How does NumPy generate random numbers?</h4>
<p>Numpy's random number routines produce pseudo random numbers using combinations of a BitGenerator to create sequences and a Generator to use those sequences to sample from different statistical distributions: BitGenerators: Objects that generate random numbers.</p>

<h4>Q.Why do we need random numbers in Python?</h4>
<p>There is a need to generate random numbers when studying a model or behavior of a program for different range of values. Python can generate such random numbers by using the random module.</p>
<br>
<h1>Variable Scope</h1>
<img align="left" alt="Application1" width="1000px" src="https://user-images.githubusercontent.com/90051406/194483117-aba47037-2426-4fbc-91cb-c54ebb3f7e90.png" />
 <p>Soon will add this</p>
<br>
<h1>Identifiers</h1>
 <h4>Q.what are reserved classes of Python Identifiers? </h4>
 <img align="left" alt="Application1" width="1000px" src="https://user-images.githubusercontent.com/90051406/194485410-2f396fad-6dc7-42aa-86a1-633d72fa179d.png" />
 <p></p>
<br>
<h1>Operator Overloading and Magic Methods</h1>
<p>In the programming world, operator overloading is also called Operator Ad-hoc Polymorphism.Indeed, it is a case of polymorphism where different operators have different implementations based on their arguments.</p>
<p>This is either defined by the programmer, by the programming language, or both.</p>
<p>one magic method- __init__() we know. But we can, in fact, define our own magic methods to implement operator overloading in Python.</p>
<p>Magic methods are special methods in python that have double underscores (dunder) on both sides of the method name. Magic methods are predominantly used for operator overloading.</p>
<h4>Q.How do you call a magic function in Python?</h4>
<p>Dunder or magic methods in Python are the methods having two prefix and suffix underscores in the method name. Dunder here means “Double Under (Underscores)”. These are commonly used for operator overloading. Few examples for magic methods are: __init__, __add__, __len__, __repr__ etc.</p>

                                                  need to add operator overloading in simplest way

<h1>Pickling & Unpickling</h1>
<p>“Pickling” is the process whereby a Python object hierarchy is converted into a byte stream, and “unpickling” is the inverse operation, whereby a byte stream (from a binary file or bytes-like object) is converted back into an object hierarchy.</p>


<h1>Shallow Copy vs Deep copy</h1>
<p> Shallow copy constructs a new compound object and then (to the extent possible) inserts references into it to the objects found in the original. A deep copy constructs a new compound object and then, recursively, inserts copies into it of the objects found in the original.</p>
<br>
<h1>Ternary Operator</h1>
<img align="left" alt="Application1" width="1000px" src="https://user-images.githubusercontent.com/90051406/194567974-b0996abf-c530-4eb8-9b15-cf2514d03c83.png" />
<p>Ternary operators in Python are terse conditional expressions.Python ternary operator is the conditional expression to evaluate the statement while programming. It performs the action based on whether the given condition is true or false. Therefore, the ternary operator in Python is widely used as it is helpful to make your code compact and maintain all the necessary conditions.

This was made available since PEP 308 was approved and is available ever since version 2.4. This operator, if used properly, can reduce code size and enhance readability.</p>
<h5>Q.Does Python have a Ternary operator?</h5>
<p>Many programming languages support ternary operator, which basically define a conditional expression. Similarly the ternary operator in python is used to return a value based on the result of a binary condition.</p>
<h5>Q.How do you use a Python Ternary operator?</h5>
<p>Similarly the ternary operator in python is used to return a value based on the result of a binary condition. It takes binary value(condition) as an input, so it looks similar to an “if-else” condition block. However, it also returns a value so behaving similar to a function.</p>
<h5>Q.Are Python ternary operators readable?</h5>
<p> </p>
<h1>Namespace</h1>
<h5>Q.What is namespace and scope in Python?</h5>
<h5>Q.Why are namespace and scope used in Python?</h5>
<h5>Q.Give an example of Python namespace and scope?</h5>
<h5>Q.What is class namespace in Python?</h5>

<h1>Decision Making Statements</h1>
                                         yar understodable topic hiaaa

<h1>What is Python Utility Module</h1><p>
Python utilities contains many standard utility modules to solve common problems.
[insatll utility module for both python and anaconda environment-pip install utilities]</p>
<h1>List Comprehension</h1>
<p>Syntax of List Comprehension in Python</p>
<p>we use a for-statement on an iterable (a list, here). We’ll take an example</p>
<h5>Q.Is list comprehension a for loop?</h5>
<p>List comprehension is used for creating lists based on iterables. It can also be described as representing for and if loops with a simpler and more appealing syntax.</p>
<h5>Q.Is list comprehension faster than Numpy?</h5>
<p>Numpy is more the 61 times faster than list comprehension, but sometimes we need to use this value as a list. Even as a list, the method Numpy is at least 2,34 faster than other methods.</p>
<h5>Q.Difference between list comprehension and for loop.</h5> 
<p>The for loop is a common way to iterate through a list. List comprehension, on the other hand, is a more efficient way to iterate through a list because it requires fewer lines of code.</p>
<h5>Q. Does list comprehension work for tuples?</h5>
<p>We can perform comprehension to sequences such as lists, sets, dictionaries but not to tuples. For example, if we want to perform list comprehension, we use square brackets [ ]. We use curly braces { }, but we would have to use parentheses for the tuple for dictionary comprehension.</p>
<h1>List Comprehension vs Lambda Expression</h1>
 
<img align="center" alt="Application2" width="1000px" src="https://user-images.githubusercontent.com/90051406/194671169-d05404e7-3fe0-446e-901c-cf9f0bf07572.png" />

<h1>Functions</h1>
<h3>Decorators</h3>

<h1>Zip/Eval/repr/exec</h1>
 
<img align="center" alt="Application2" width="1000px" src="https://user-images.githubusercontent.com/90051406/194685178-27674f51-45d4-4d27-b2b5-834432726a91.png" />


<h5>Q.What is difference between zip () and enumerate () Explain with example?</h5>
<p>The enumerate() function returns indexes of all items in iterables (lists, dictionaries, sets, etc.) whereas the zip() function is used to aggregate, or combine, multiple iterables.</p>
<h5>Q.What does zip do in pandas?</h5>
<p>zip() function creates the objects and that can be used to produce single item at a time. This function can create pandans DataFrames by merging two lists. Above two lists can be merged by using list(zip()) function. Now, create the pandas DataFrame by calling pd.</p>
<h5>Q.What is the use of eval () function give example?</h5>
<p>Eval function is mostly used in situations or applications which need to evaluate mathematical expressions. Also if the user wants to evaluate the string into code then can use eval function, because eval function evaluates the string expression and returns the integer as a result.</p>
<h5>Q.What does exec () do Python?</h5>
<p>Image result for exec() function python</p>
<p>Python's built-in exec() function allows you to execute arbitrary Python code from a string or compiled code input. The exec() function can be handy when you need to run dynamically generated Python code, but it can be pretty dangerous if you use it carelessly.</p>
<h5>Q.What can I use instead of exec in Python?</h5>
<p>The globals() and locals() functions returns the current global and local dictionary, respectively, which may be useful to pass around for use by eval() or execfile().</p>

<h1>What are standard packages in Python?</h1><p>
The Python Standard Library is a collection of script modules accessible to a Python program to simplify the programming process 
and removing the need to rewrite commonly used commands.
can be used by calling /importing at the beginning of script.</p>

<h1>what packages are in the python standard library?</h1> 
<img align="center" alt="Application2" width="800px" src="https://user-images.githubusercontent.com/90051406/194235049-d6d298cf-c4a6-4195-8a58-59d9ccf090f7.png" />
                                                             
                                                              urrr Now you know which libraries to go for.                                                              
<h1>Waht is Monkey patching?</h1>                                                              
<p>Monkey patching is a technique used to dynamically update the behavior of a piece of code at run-time. A monkey patch is a way to extend or modify the runtime code of dynamic languages without altering the original source code.</p>
<h5>Q.Is monkey patching a good practice?</h5>
<p>But you should never consider this a standard technique and build monkey patch upon monkey patch. This is considered bad because it means that an object's definition does not completely or accurately describe how it actually behaves.</p>
<h1>Collections</h1>
<h4>what is need for collection</h4>
<p>provides useful container datatypes. Container datatypes allow us to store and access values in a convenient way.</p>
<br>
<h1>Modules</h1>
</h5>Q.How many types of modules are there in Python?</h5>
<p>The Python standard library contains well over 200 modules, although the exact number varies between distributions.</p>

<h5>Q.What is python collection modules?</h5><p>
Container that is used to store collections of data & was introduced to improve the funtionalities of the built in collection containers</p>
<p>for ex:tuple, dict, list & set.</p>
<h5>Q.What is Modular Programming?</h5>
<p>The process of breaking a large, unwieldy programming task into separate, smaller, more manageable subtasks or modules. Individual modules can then be cobbled together like building blocks to create a larger application.</p>
<br>
<h1>Examples</h1><p>
spotify Overall backend communication takes place with the use of ZeroMQ, an open networking framework written in Python and in C++.
</p>
<br>
<h1>Application of python</h1><p>
Web and Internet Development
Desktop GUI Applications
Science and Numeric
Software Development
Education
Database Access
Network Programming
Games and 3D Graphics<table>
<tr>
<td><img align="left" alt="Application1" width="500px" src="https://user-images.githubusercontent.com/90051406/194222279-41961556-91ed-404a-a6f7-ac6645d4194f.png" /></td>
<td><img align="right" alt="Application2" width="500px" src="https://user-images.githubusercontent.com/90051406/194222805-e2eb594a-46c6-4a84-b66d-309cdbffbfbb.png" />
</td></tr></table>
<h1>Basic Questions</h1>
<h5>Which sorting technique is used by sort() and sorted() functions of python?</h5>
<p>Python's default sort uses Tim Sort, which is a combination of both merge sort and insertion sort.
Abt Tim Sort </p>

<h5>Q.What is PEP8?</h5>
<p>PEP 8, sometimes spelled PEP8 or PEP-8, is a document that provides guidelines and best practices on how to write Python code. It was written in 2001 by Guido van Rossum, Barry Warsaw, and Nick Coghlan. The primary focus of PEP 8 is to improve the readability and consistency of Python code.
or
PEP 8 is a style guide for Python code. This document provides the coding conventions for writing code in Python. The coding conventions are about indentation, formatting, tabs, maximum line length, imports organization, line spacing etc.</p>

<h5>Q.What is PEP8 and Pylint?</h5>
<p>Pycodestyle (Formerly PEP8) is the official linter tool to check the python code against the style conventions of PEP8 python. Pylint is a python linter which checks the source code and also acts as a bug and quality checker. It has more verification checks and options than just PEP8(Python style guide).</p>
<h5>Q.Why do we use Pylint?</h5>
<p>Pylint analyses your code without actually running it. It checks for errors, enforces a coding standard, looks for code smells, and can make suggestions about how the code could be refactored. Pylint can infer actual values from your code using its internal code representation (astroid).</p>
<h5>Q.What does pep8 stand for?</h5>
<p>Python Enhancement Proposal 8</p>

<h5>Q.Is Python runtime or compile time?</h5>
<p>Compile time is the period when the programming code (such as C#, Java, C, Python) is converted to the machine code (i.e. binary code). Runtime is the period of time when a program is running and generally occurs after compile time.</p>
<h5>Q.What is difference between compiler and interpreter?</h5>
<p>Interpreter translates just one statement of the program at a time into machine code. Compiler scans the entire program and translates the whole of it into machine code at once. An interpreter takes very less time to analyze the source code. However, the overall time to execute the process is much slower.</p>
<h5>Q.Which language Python is written?</h5>
<em>C</em>
<p>Python is written in C (actually the default implementation is called CPython).</p>
<h5>Q.What is source code in Python?</h5>
<p>In simple we can say source code is a set of instructions/commands and statements which is written by a programmer by using a computer programming language like C, C++, Java, Python, Assembly language etc. So statements written in any programming language is termed as source code.</p>

<h5>Q.Which one is faster compiler or interpreter?</h5>
<p>Interpreters usually take less amount of time to analyze the source code. However, the overall execution time is comparatively slower than compilers. Compilers usually take a large amount of time to analyze the source code. However, the overall execution time is comparatively faster than interpreters.</p>

<h5>Q.Why compiler is faster than interpreter?</h5>
A compiled program is faster to run than an interpreted program, but it takes more time to compile and run a program than to just interpret it. A compiler indeed produces faster programs. It happens fundamentally because it must analyze each statement just once, while an interpreter must analyze it each time.

<h5>Q.Which language is known as the machine code?</h5>
<p>Machine code, also known as machine language, is the elemental language of computers. It is read by the computer's central processing unit (CPU), is composed of digital binary numbers and looks like a very long sequence of zeros and ones.</p>

<h5>Q.Why source code is important?</h5>
<p>Source code serves the needs of companies who have procedures in place that they want to retain regardless of the software installed. Some companies consider source code as a way to guarantee that the software changes as their company's needs change in the future.</p>
<h5>Q.What are the types of source code?</h5>
<p>The types of source code are:</p>
~Compiled source code.
~Interpreted source code.
~Computer (or operating system) source code.
~Software program source code.
~Software feature source code.
<h5>Q.How is memory managed in Python interview questions?<h5>
<p>Python memory is managed by Python private heap space. All Python objects and data structures are located in a private heap. The programmer does not have access to this private heap and the interpreter takes care of this Python private heap.</p>
<h5>Q.What is mutable and immutable in Python with example?</h5>
<p></p>
<h5>Q.How to Invoke the Python Interpreter?</h5>
<p>On your machine, you can find your interpreter at an address like:
<em>C:\Python36</em>
Or it may reside on the location you selected at the time of installation.</p>
<h3>string literal-- a complete sentence       string- a letter[simply to remember]</h3>
<h5>Q.How Does Python Interpreter Works?</h5>
<p>Well, internally, four things happen in a REPL:</p>
<p>i. Lexing- The lexer breaks the line of code into tokens.</p>
<p>ii. Parsing- The parser uses these tokens to generate a structure, here, an Abstract Syntax Tree, to depict the relationship between these tokens.</p>
<p>iii. Compiling- The compiler turns this AST into code object(s).</p>
<p>iv. Interpreting- The interpreter executes each code object</p>
<h5>Q.Which operators cannot be overloaded?'</h5>
<p>Dot (.) operator can't be overloaded, so it will generate an error.</p>
<h5>Q.Can you use switch case in Python?</h5>
<p>From version 3.10 upwards, Python has implemented a switch case feature called “structural pattern matching”. You can implement this feature with the match and case keywords.</p>
<h5>What does .format do in Python?</h5>
<p>The format() method formats the specified value(s) and insert them inside the string's placeholder. The placeholder is defined using curly brackets: {}. Read more about the placeholders in the Placeholder section below. The format() method returns the formatted string.</p>
<h5>Q.What are the two Limitation of switch statement?</h5>
<p>Disadvantages of switch statements</p>

<p>float constant cannot be used in the switch as well as in the case. You can not use the variable expression in case. You cannot use the same constant in two different cases. We cannot use the relational expression in case.</p>
<p>The switch statement doesn't accept arguments of type long, float, double,boolean or any object besides String.</p>
<h1>Basic Points</h1>
<h4><class ‘NoneType’>
Well, since the function does not return anything, we get an object of class ‘NoneType’.</h4>
<h1>Behavioral Interview Quesion</h1>

<h5>Q.Tell me about your experience with python</h5>
<h5>Q.What method do you use for task prioritization?</h5>
<h5>Q.What startegy or approach do you use if you're unclear about what a project requires?</h5>
<h5>Q.What approach do you use to begin working on a new project?</h5>
<h5>Q.Have you ever made a mistake with python.</h5>
<h5>Q.Name a few errors you would try to avoid.</h5>
<h5>Q.For how long you used python.</h5>
<h5>Q.How do you stay organized when carrying out a project in python?</h5>

<br>
<h1>Competition</h1>
 <p><a href="https://pyweek.org/">💡 pyweek - Gaming Competition</a></p>
 <p><a href="https://www.instagram.com/python4coding/">💡 python OPP easy explanation</a></p>
 <p><a href="https://www.dorscodingschool.com/cs50python">💡 DorscodingSchool-CS50python Solution</a>(Do it)</p>
