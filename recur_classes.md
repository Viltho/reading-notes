# recursion and classes

Recursion is a programming technique where a function calls itself in order to solve a problem. In other words, a function that uses recursion solves a problem by breaking it down into smaller sub-problems of the same type, and then recursively solving each sub-problem until a base case is reached.

For example, consider the factorial function, which computes the factorial of a given integer:

> def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)
 

This function uses recursion to compute the factorial of n. It does this by breaking the problem down into smaller sub-problems: factorial(n-1), factorial(n-2), etc. until it reaches the base case of n == 0, at which point it returns 1.

Classes in Python are a way to define custom data types that can have attributes (variables) and methods (functions). A class is essentially a blueprint for creating objects, which are instances of the class.

Here's an example of a simple class in Python:
> class Rectangle:
    def __init__(self, width, height):
        self.width = width
        self.height = height
    
    def area(self):
        return self.width * self.height
 

This class defines a Rectangle object, which has a width attribute, a height attribute, and an area method. The init method is a special method that gets called when a new Rectangle object is created, and it initializes the width and height attributes.

Here's how you would use this class to create a Rectangle object and compute its area:

> r = Rectangle(3, 4)
  print(r.area()) # prints 12
 

This creates a new Rectangle object with width=3 and height=4, and then calls the area method to compute its area (which is width * height, or 3 * 4 = 12).
