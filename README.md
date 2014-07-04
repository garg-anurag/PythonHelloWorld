PythonHelloWorld
================
This is a HELLO WORLD example in python language.

Python 2.0 print "Hello, World!"

Python 3.0 print("Hello, World!")

If you are using Python 3.0 or above, then print will be written like this as print is now a function (hence the parenthesis) instead of a statement.

Include the code
input('Press ENTER to exit')
so that your console won't close immediately.

In python 2.x, raw_input() returns a string and input() evaluates the input in the execution context in which it is called

>>> x = input()
"hello"
>>> y = input()
x + " world"
>>> y
'hello world'
In python 3.x, input has been scrapped and the function previously known as raw_input is now input. So you have to manually call compile and than eval if you want the old functionality.

python2.x                    python3.x

raw_input()   --------------> input()               
input()  -------------------> eval(input())     
In 3.x, the above session goes like this

>>> x = eval(input())
'hello'
>>> y = eval(input())
x + ' world'
>>> y
'hello world'
>>> 

python language start
