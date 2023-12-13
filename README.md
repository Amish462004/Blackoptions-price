# Blackoptions-price
This project revolves around the Basics of Options Theory and one of the most elementary equation in it but the king "The Black Scholes" equation which has some inherent assumptions for volatility and risk-free interest rate, which makes it go a little haywire in modern day context, thus, here we will be using the power of Deep Learning and Neural Networks to get rid of these assumptions and constraints and build a much superior model out of it. We will certainly build MLP1,MLP2 and the LSTM model, which take 20-day historical volatility as an input, while the LSTM model takes in the latest 20 days of underlying price, allowing it to learn volatility. At the end of the learning phase the mentees, while doing the project would be able to extract the relevant data from the source and filter and prepare it for applying the relevant models on it.

A temporary dataset of an option chain is provided but this project involves the extraction of data directly by students and prepare it as per their use, they are thereby required to use https://www.nseindia.com/ for this task.

# Pre-requisites
No Nothing, just show enthusiasm and keep your hands open to gain something, we will feed you with the food but you have to eat it, your hunger will decide how much you nourish yourself with this project.

Basic knowledge of Options Pricing and Python would however be a cherry on the cake (though not necessary).

# Week Wise Plan
Hey guy, this will be our week wise plan for the project
Note: There may be slight changes in the plan if there is time constraint.
Happy Learning! :)
https://docs.google.com/document/d/1N-gFuRwzPCKVFpmua1iKdXhgZzzUM7lnpkhDQP9vQqo/edit?usp=sharing

# Python Basics!
For all those looking to learn python from scratch , you can begin with the material given below, while those of you who are already familiar with python and are just looking to revise can go through this notebook.

For the first week we will be covering some basic topics:

Getting Started
Introduction to Data Types and Data Structures in Python
Operators in Python
Conditions and Loops
Python Functions
Scope of Variables
Recursion
Python Modules and Packages
Some Standard libraries of python
Classes and Objects
File Handling (Optional)
Assignment 1
Then we'll go through some data science libraries.

Data Science Libraries!
Now, we will look at Applications of Python in Data Analysis fields and will cover various python libraries used for this namely :

Numpy
Pandas
Matplotlib
Seaborn
Scikit-learn
And Finally, we'll start with a basic introduction of Machine Learning

Getting Started With Machine Learning
The two main and the most time consuming steps(which include a bunch of substeps) of machine learning will be taken care of in this week namely :

Data Collection
Data Preparation
Assignment 2
Challenging Assignment(Hard)
Let's get this party started!

Python is the most diverse language with very varied applications in different fields such as Research, Machine Learning, Backend Web Development, Data Visualisation, Web Scraping and much more, and this is possible only because of the different libraries and frameworks available for Python.In subsequent weeks we will be covering some amazing applications of python. Let's get started!

Getting Started
Installation and Setup
Visit this link for a detailed guide on installing and setting up Python - Python Installation and Setup

Introduction to Jupyter Notebooks
Jupyter notebook is a web based notebook environment which is widely used for interactive programming, that is, code execution combined with rich markdown text and much more. The Jupyter notebook runs a local Ipython kernel on your machine and launches in your web browser. These notebooks are also called as Ipython notebooks, and have a '.ipynb' extension instead of traditional '.py' extension for Python files. All the assignments for this course are made in Jupyter notebooks and you are expected to complete them in the notebook itself. Hence, it is important for you to get aquainted with Jupyter notebooks.

Visit this link for installing and setting up a basic notebook - Setting up Jupyter Notebook. The link also teaches you to write and execute a basic Python code in a Notebook cell.

Google Colab
Google Colab is a platform provided by Google, which runs a Jupyter notebook in the cloud. While it is a convenient way to get set up, there are some caveats you would like to know before it. The setup is platform agnostic i.e. all you need is a browser. The recommended way to get started is first logging in to Google. Sign in > Head to the home page for Google Colab here > click on New Notebook. From this point, everything is basically the same as a Jupyter notebook.

Instructions on downloading and using notebooks
Open the respective .ipynb file on GitHub

In the upper right corner, there are several buttons and icons including the ones shown below. Click on the Raw Button.

Raw	Blame
The python notebook opens as raw text in browser. Right click->Save as OR just press CTRL + S. Save the notebook, open it using Jupyter Notebook you just installed and start learning!

Introduction to Data Types and Data Structures in Python
Once you have set up the environment for writing your code, we now begin with coding in Python. Let's get started.

Head over to this link - Introduction to Python Data Types and start with the topics in the 'Learn the Basics' sections one by one (till 'Basic String Operations'). These are official tutorials from the Python organisation which are well curated for beginners and contain an inbuilt Ipython shell for writing and executing your code there itself.

If you are not of the reading kind, checkout this Youtube playlist for step-by-step tutorials on Python basics (Tutorials #1 - #11 except #6, #7, #9). But make sure that you are following alongside with the video, otherwise things won't make sense later in the course.

You can also read these concepts from GeeksForGeeks. They explain each concept in good detail along with examples.

Irrespective of where you choose to read/watch from, you should be familiar with the following topics:

Strings
Lists
Tuples
Sets
Dictionary
Arrays
Operators in Python
Now that you have a basic idea about different variable data types and data structures, let us now explore how you can work with multiple variables at once in order to get your desired output. This is done using Operators.

Operators in a programming language mean the same thing as operators in maths (almost), so the only thing you need to be concerned about is the syntax of working with operators.

Head over to this link - Python Operators for a detailed description of different operators in Python. Then check out the tabs in the navigation bar on the left and read about all the operators one by one. These are extremely important as some of the concepts explained here will be used to define other concepts later on, and to understand any piece of code analytically, you should know what each line of code is doing. You can also checkout this video tutorial based on the book Automate the Boring Stuff with python. You should be familiar with the following Python operators:

Arithmetic Operators
Relational Operators
Logical Operators
Bitwise Operators
Assignment Operators
Identity Operators
Membership Operators
Conditions And Loops
Conditions and Loops are a core part of any program written in any programming language. You use loops whenever you want to perform a particular task repeatedly over many iterations, given a condition is satisfied. Conditions are also used without loops, as if-else conditions.

Checkout this link for a detailed article on Conditions and Loops - Conditions and Loops You can also refer to this link from GeeksForGeeks - Conditions and Loops (Checkout all the tabs in the navigation bar on the left) Again, if you prefer videos instead, refer to this Youtube Playlist's Tutorial #6, #7 and #9.

Make sure you have covered the following topics -

For loop
while loop
break statement
continue statement
If-else condition ( normal, nested, if-elif)
Functions
Functions are the named blocks of code that are designed to do one specific job. When you want to perform a particular task that you’ve defined in a function, you call the name of that function responsible for it. If you need to perform that task multiple times throughout your program, you don't need to type all the code for the same task again and again; you just call the function dedicated to handling that task, and the call tells Python to run the code inside the function. You’ll find that using functions makes your programs easier to write, read, test, and fix. You can see this notebook which covers some details about the functions.
If you prefer to watch videos to learn you can head over to this link.

Scope of a Variable
The location where we can find a variable and also access it if required is called the scope of a variable. Variables that are defined inside a function body have a local scope, and those defined outside have a global scope. This means that local variables can be accessed only inside the function in which they are declared, whereas global variables can be accessed throughout the program body by all functions.

If you want to learn more about functions and scope you can visit this link.

Recursion
Python also accepts function recursion, which means a defined function can call itself. Recursion is a common mathematical and programming concept. It means that a function calls itself. This has the benefit of meaning that you can loop through data to reach a result.

The developer should be very careful with recursion as it can be quite easy to slip into writing a function which never terminates, or one that uses excess amount of memory or processor power. However, when written correctly, recursion can be a very efficient and mathematically-elegant approach to programming. You can go through this link to learn about recursion and see some implementations of recursion.

If you prefer to watch videos you can go through this video.

Python Modules and Packages
One advantage of functions is the way they separate blocks of code from your main program. By using descriptive names for your functions, your main program will be much easier to follow. You can go a step further by storing your functions in a separate file called a module and then importing that module into your main program. Storing your functions in a separate file allows you to hide the details of your program’s code and focus on its higher-level logic. It also allows you to re-use functions in many different programs. When you store your functions in separate files, you can share those files with other programmers without having to share your entire program. Knowing how to import functions also allows you to use libraries of functions that other programmers have written.

You can go through this notebook to learn about modules and packages.

Iterators
Iterator in python is any python type that can be used with a ‘for in loop’. Python lists, tuples, dicts and sets are all examples of inbuilt iterators. These types are iterators because they implement following methods.In fact, any object that wants to be an iterator must implement following methods.

__ iter__ method that is called on initialization of an iterator. This should return an object that has a next or __ next__ (in Python 3) method.

next ( __ next__ in Python 3) The iterator next method should return the next value for the iterable. When an iterator is used with a ‘for in’ loop, the for loop implicitly calls next() on the iterator object. This method should raise a StopIteration to signal the end of the iteration.

To read more about Iterators refer this

Some Standard libraries of python
In python, a collection of predefined modules and packages is called a library. There are a lot of useful and interesting libraries available in python. Using such libraries often helps in reducing the effort and saves time in a number of places. Here, we will learn about some of the standard library modules:

Note: Don’t forget to first import the module using statements like “import math” which was covered in modules and packages!!!!

The math Library: Python has a built-in module that you can use for mathematical tasks.The math module has a set of methods and constants. Some of these methods often come in handy. You go to this link to learn about the methods and constants in the math module. It's beneficial to know about some of the basic trigonometric, exponential, logarithmic functions and some numeric ones like factorial, fabs, floor, ceil etc. They are used quite frequently.
The random library: This module implements pseudo-random number generators for various distributions. Some of the functions that you should be familiar with are seed(), randrange(), randint(), choice(), choices(), sample(), random(), uniform(). You head over to this link to learn about this library.
The time library: This module provides various time-related functions. You should know about the terms epoch, seconds since epoch, local time, UTC, struct_time and also about functions used in conversions from struct_time to seconds since epoch etc. You can head over to this link and learn about these.
The datetime library: The datetime module supplies classes for manipulating dates and times.You should have a basic idea about creating a date and datetime objects and know about some of the methods. You can head over to this link to learn about them.
Important thing to note here is you don’t really need to remember all of these functions/methods. Instead you should just be familiar with the module, know about what kind of methods and constants are there in it. Whenever you are working and need to use any function/method from a module but don’t remember the exact syntax you can just head over to that module’s documentation.

Classes and Objects
Object-oriented programming is one of the most effective approaches to writing software. In object-oriented programming you write classes that represent real-world things and situations, and you create objects based on these classes. You can think of a class as a collection of many different functions and attributes (variables) that can be accessed by an object of that class. These methods inside a class are defined almost in the same way normal Python functions are defined, with a major difference being the 'self' argument and some special methods only found in a class body, for example:- the '__init__' method, '__add__' method, etc.

When you write a class, you define the general behavior that a whole category of objects can have. When you create individual objects from the class, each object is automatically equipped with this general behavior; you can then give each object whatever unique traits you desire.

Making an object from a class is called instantiation, and you work with instances of a class. You’ll specify the kind of information that can be stored in instances, and you’ll define the actions that can be taken with these instances.

You can visit this notebook to learn about classes and objects.
You can also go through this video.

File Handling (Optional)
Since we have covered a good number of topics , we are keeping File Handling as optional.Those who are interested in learning this can go through the article below.

Files are named locations on disk to store related information. They are used to permanently store data in a non-volatile memory (e.g. hard disk). Since Random Access Memory (RAM) is volatile (which loses its data when the computer is turned off), we use files for future use of the data by permanently storing them. When we want to read from or write to a file, we need to open it first. When we are done, it needs to be closed so that the resources that are tied with the file are freed.

Hence, in Python, a file operation takes place in the following order:

Open a file
Read or write (perform operation)
Close the file
To read more about File Handling refer this

This brings us to the end of this week's material. By now you should be familiar with the basics of python. You should have a good enough idea about concepts like data types, loops, operators, iterators, functions, modules and packages, classes in python. Do go through the assignment after finishing the reading material. It will give you a chance to apply these concepts and practice your skills. Next week we will learn to use python in the field of data analysis.
