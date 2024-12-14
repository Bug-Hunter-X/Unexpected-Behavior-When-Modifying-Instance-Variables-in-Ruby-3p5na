# Ruby Instance Variable Modification Bug

This repository demonstrates an uncommon bug related to instance variable modification in Ruby.  When you modify an instance variable directly (using `instance_variable_set`) and then try to assign a new value through the getter method (without a corresponding setter), the instance variable remains unchanged. This can be subtle and lead to unexpected behavior in your code.

The `bug.rb` file shows the problematic code, and `bugSolution.rb` shows how to solve it by defining a setter method.