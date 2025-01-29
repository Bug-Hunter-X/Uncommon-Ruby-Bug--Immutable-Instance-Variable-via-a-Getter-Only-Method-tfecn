# Uncommon Ruby Bug: Immutable Instance Variable

This repository demonstrates a subtle bug in Ruby where an instance variable appears immutable due to the lack of a setter method, even though it may seem like one exists through a getter method.  The error is not immediately obvious to novice Ruby developers.

The `bug.rb` file shows the problematic code. The `bugSolution.rb` file provides the corrected code.

This demonstrates an important aspect of Ruby's object model, which is that methods are not implicitly setters and getters.
