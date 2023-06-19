### Dunder and more

- One of the main purposes of dunder methods is to enable object-oriented programming in Python, by allowing you to define custom behavior for operations such as object initialization, string representation, comparison, indexing, iteration, and more. By implementing these methods in your classes, you can make your objects behave like built-in types or add functionality specific to your application.

- Here's an example of a commonly used dunder method in Python: __str__(). This method defines how an object should be represented as a string. By default, if you try to print an object, Python will display a memory address. However, by defining __str__() method, you can specify a custom string representation of the object.

        class Person:
            def __init__(self, name, age):
                self.name = name
                self.age = age
                
            def __str__(self):
                return f"{self.name} ({self.age})"
                
        person = Person("John", 30)
        print(person)

- The statistics module in Python is a built-in module that provides functions for mathematical statistics, such as calculating measures of central tendency, measures of dispersion, and probability distributions. The module can be used to perform various statistical operations on a given set of data, without having to manually write complex code for each operation.

Here's an example of a function within the statistics module that can be used to perform a common statistical operation:

        import statistics

        data = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

        # Mean (average) of data
        mean = statistics.mean(data)
        print(mean)  # Output: 5.5

        # Median of data
        median = statistics.median(data)
        print(median)  # Output: 5.5

        # Mode of data
        mode = statistics.mode(data)
        print(mode)

- There are many other functions in the statistics module that can be used to perform statistical operations such as variance, standard deviation, and more. These functions can save time and simplify statistical calculations in Python.

