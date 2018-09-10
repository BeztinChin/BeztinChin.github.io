---
title: Exception in python.
excerpt: Introduce some common exception and some ways to haddle it.
tags: python exception
---


## common exception in python:

- ImportError
- IndexError
- NameError: *an unknow variable is used*
- SyntaxError
- TypeError: *when the function cant do with this kind of type*
- ValueError: *when the function cant do with this value( right type)*
- ZeroDivisionError
<br/>
*also some other bulit-in exception* <br/>*Third-party libraries often define their own exceptions*
<br/><br/>

## Syntax about exception in python:
```python
try:
  ...
except ZeroDivisionError:
  ...
except (ValueError,TypeError):
  ...
finally:
  ...
```
*when a exception happens in ''try'', the exception will be caught by the **first** matching ''except'' and then **jump** to ''finally''*

## get some exception:

- raise

```python
raise NameError('Invalid name!')

or write like following :
try:
  num=5/0
except:
  print("some error occurred")
  raise
  
>>>
some error occurred

ZeroDivisionError: devision by zero
>>>
```

- Assert

```python
temp= -10
assert(temp>10),'colder than absolute zero!'

>>>
AssertionError: colder than absolute zero!
>>>
```
*the **AssertionError** can also be caught by **except***
