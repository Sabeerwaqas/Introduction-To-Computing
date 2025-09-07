# Intro to Computing 07 - Library Functions, Variables, Intro to Errors

In this lecture, we introduced with the following:

* ```math``` library in Python.
* variables
* errors

## ```math``` library:

He introduced us with ```math``` library of Python. In this library, we can import general math functions like ```sqrt()```, ```pow()``` etc. In Python, we can import math functions via following 2 approaches.

1. ```import math```

In the above approach, we requested Python to bring all the available maths function from the ```math``` library. Through this approach, we can call any available math function for our use like ```math.sqrt``` or ```math.pow``` etc. 

2. ```from math import sqrt```

In the above approach, we requested Python to bring only specific math funtion from library like ```sqrt```.

## Variables:

If we take an example of mathematics, we have variables in our equations. 

For example: ```2x² - 7x - 15 = 0```

In the above equation, we have variable ```x```. Now, this variable remains same in the whole equation. Like, we would not assign ```boolean, string``` or any other type of value in the solution later.

But, in programming, we have a special variable which can be assinged later with different values. Think of it like a container whose value can vary according to situation.

For Example:

```
gpa = 3.0

print gpa

gpa = 3.5

print gpa

```

In the above code, we can see that our variable value varies differently according to our use case.

## Errors

In this section, we introduced with some errors and he emphasized on understanding the errors. 

For Example:

If we type, ```printing gpa```, Python will through us an error ```command not found```. Now, we can easily understand that Python is trying us to say that the given command is not recognized by Python.

