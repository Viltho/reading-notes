## Stack and Queue

- In computer programming, a stack is a data structure that allows for the storage and retrieval of data elements in a particular order. The most recently added item is always the first one to be removed, which follows the Last-In-First-Out (LIFO) principle.

- In Python, a stack can be implemented using a list. The append() method is used to add an element to the top of the stack, and the pop() method is used to remove the top element from the stack.

- Here's an example of how to implement a stack in Python:

        stack = []

        # Push items onto the stack
        stack.append('apple')
        stack.append('banana')
        stack.append('cherry')

        # Pop items from the stack
        top_item = stack.pop()   # 'cherry'
next_item = stack.pop()  # 'banana'

- In this example, the stack variable is initially an empty list. The append() method is used to push three items onto the stack, and then the pop() method is used to remove two items from the stack in reverse order (i.e., 'cherry' is removed first, followed by 'banana').

- In computer programming, a queue is a data structure that allows for the storage and retrieval of data elements in a particular order. The first item added to the queue is the first one to be removed, which follows the First-In-First-Out (FIFO) principle.

- In Python, a queue can be implemented using the queue module, which provides the Queue class. Alternatively, a queue can also be implemented using a list.

- Here's an example of how to implement a queue in Python using the queue module:

        import queue

        q = queue.Queue()

        # Add items to the queue
        q.put('apple')
        q.put('banana')
        q.put('cherry')

        # Remove items from the queue
        item1 = q.get()   # 'apple'
        item2 = q.get()   # 'banana'


- In this example, the queue.Queue() function is used to create an empty queue. The put() method is used to add three items to the queue, and then the get() method is used to remove two items from the queue in the order they were added (i.e., 'apple' is removed first, followed by 'banana').

- Here's an example of how to implement a queue in Python using a list:

        queue = []

        # Add items to the queue
        queue.append('apple')
        queue.append('banana')
        queue.append('cherry')

        # Remove items from the queue
        item1 = queue.pop(0)   # 'apple'
        item2 = queue.pop(0)   # 'banana'

- In this example, the queue variable is initially an empty list. The append() method is used to add three items to the queue, and then the pop(0) method is used to remove two items from the queue in the order they were added (i.e., 'apple' is removed first, followed by 'banana').
