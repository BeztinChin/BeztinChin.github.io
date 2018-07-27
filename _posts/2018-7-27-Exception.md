---

title: Exception in python.
excerpt：here will introduce some Exception in python and show how to caught and raise it.

---



{% include header.html %}
##Exception in python 


##common exception in python:

ImportError
IndexError
NameError: an unknow variable is used
SyntaxError
TypeError: * when the function cant do with this kind of type*
ValueError:* when the function cant do with this value( right type)*
ZeroDivisionError

*also some other bulit-in exception* *Third-party libraries often define their own exceptions*


##Syntax about exception in python:

try:
  ...
except ZeroDivisionError:
  ...
except (ValueError,TypeError):
  ...
finally:
  ...


##get some exception:

raise
raise NameError('Invalid name!')
try:
  num=5/0
except:
  print("some error occurred")
  raise
  
>>>
some error occurred

ZeroDivisionError: devision by zero
>>>
Assert
temp= -10
assert(temp>10),'colder than absolute zero!'

>>>
AssertionError: colder than absolute zero!
>>>
