# Ruby Instance Variable Modification Bug

This repository demonstrates a subtle bug in Ruby related to how instance variables are modified indirectly through methods.

The `bug.rb` file shows a class with a method (`value`) that accesses an instance variable (`@value`). Assigning a new value to the method (`my_object.value = 30`) does not change the instance variable's value, which is a common error. `bugSolution.rb` illustrates the correct way to modify the instance variable.  This is a critical issue for developers new to Ruby's instance variable handling.