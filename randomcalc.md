# Things I want to know more about

Based on the Rolling Dice Example, explain how you would simulate a dice roll using Python. Describe how you would use code to calculate the probability of rolling a specific number (e.g., the probability of rolling a 6) over a large number of trials.

the probability of rolling a dice and getting 6 is 1/6

if there are 100,000 trials it will follow the rule : 

  > (5/6)^n

- In Python, variable scope refers to the area of a program where a particular variable is accessible and can be referenced. Python has two main types of variable scope: local scope and global scope.

- Local scope: A variable declared inside a function or a code block has local scope, which means it can only be accessed within that function or code block. Once the function or code block completes execution, the local variable is destroyed, and it cannot be accessed from outside the function or code block.

      def print_name():
          name = "Alice"  # Local variable
          print("Name inside the function:", name)
      print_name()
      print("Name outside the function:", name)  # Raises NameError
