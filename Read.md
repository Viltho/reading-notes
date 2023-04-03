## Things I want to know more about

#### From the text, the main challenges that beginners face when learning Python are:

- Mental challenges: Beginners need to think their way through problems that they had only heard about a few hours beforehand. They have to research for hours on end to flesh out the skeleton discussed in class, piling information on top of application so that they can reach their goals.

- Emotional challenges: Beginners constantly confront their own lack of understanding of a topic. They need to figure out how to collaborate with new people and deal with their (and their own) emotional quirks. They are constantly thrust far outside their comfort zone with the expectation that they will survive for the next push forward. They are dealing with uncertainty of what awaits them at the end of the 10 weeks, and whether or not they will make it.

### Two strategies to overcome these obstacles are:

- Seek help and collaborate: Beginners can join a Python community or a coding group to connect with other Python learners and developers. They can ask questions, share their experiences, and learn from others. This can help them overcome the emotional challenges of collaboration and uncertainty.

- Practice regularly: Beginners should practice coding regularly to improve their mental agility and problem-solving skills. They can start with simple projects and gradually move on to more complex ones. This can help them overcome the mental challenges of research and problem-solving.

### Big O Notation:

- Time complexity and space complexity are two key concepts in computer science that are used to analyze and measure the performance and resource usage of algorithms.

- Time complexity refers to the amount of time an algorithm takes to run as a function of the input size. It measures the number of basic operations or steps an algorithm requires to solve a problem. This can be expressed in terms of Big O notation, which describes the worst-case scenario for the algorithm's time complexity. For example, an algorithm with a time complexity of O(n) will take n steps to complete where n is the size of the input data.

- Space complexity, on the other hand, refers to the amount of memory or storage space an algorithm requires as a function of the input size. It measures the amount of memory an algorithm needs to store its variables and data structures while executing. Space complexity can also be expressed in terms of Big O notation, which describes the maximum amount of memory an algorithm requires. For example, an algorithm with a space complexity of O(n) will require a memory space proportional to the size of the input data.

- In general, algorithms that have lower time and space complexities are preferred as they are more efficient and use fewer resources. However, there may be trade-offs between time and space complexity depending on the problem being solved and the available hardware. Therefore, understanding time and space complexity is important when designing and analyzing algorithms, especially for large-scale applications.

### In Python, a variable can either hold mutable or immutable data types.

- Immutable data types are objects whose value cannot be modified once they are created. When we perform any operation on an immutable object, Python creates a new object instead of modifying the existing one. Examples of immutable data types in Python include integers, floats, strings, and tuples.

- On the other hand, mutable data types are objects whose value can be changed after they are created. When we perform any operation on a mutable object, it modifies the original object in place. Examples of mutable data types in Python include lists, dictionaries, and sets.

- The main difference between these two types is that when we modify an immutable object, Python creates a new object in memory, which can be inefficient if we are working with large amounts of data. With mutable objects, we can modify the original object directly, which can be more memory-efficient in some cases.

- It's important to note that while immutable objects cannot be modified, we can reassign a variable to a new immutable object with a different value. For example:
`x = 5`
- x is an immutable int object and 
`x = 10`
- x is now an immutable int object with a value of 10

- In contrast, with mutable objects, we can modify the values within the object without reassigning the variable. For example:
`my_list = [1, 2, 3]`
- my_list is a mutable list object and
`my_list.append(4)`   
- we modify the original object by adding a new item and 
`print(my_list)`
- output: [1, 2, 3, 4]
