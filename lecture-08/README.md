## Intro to Computing 08 - Defining New Functions, Frames, and Scope

In this lecture, we learned how to define functions in Python.  
A special thing about Python functions is that their body is defined using **indentation (4 spaces)** rather than braces `{}` like in C or Java.

For example, in C:

```c
float square(float x) {
    return x * x;
}
```
Here, the code inside {} is executed when the function is called.

In Python, indentation defines the function body:

```py
def square(x: float) -> float:
    return x * x
```