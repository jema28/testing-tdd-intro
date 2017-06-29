# Testing & Test-driven Development

## What is testing?

Testing in general is the process of executing your code to check it does what it's supposed to do. It demonstrates that your code meets the design requirements and can also provide a template for writing new code.

We're mostly concerned with automated unit testing for now, which involves writing code that will call your functions and tell you if they return what you expect. The idea is to test as many small "units" of code as you can, which will give you a good idea if the application as a whole is working.

It's very easy to create bugs in code, especially when you're editing an existing code base. A robust suite of automated tests gives you confidence to make changes, knowing that the tests will tell you if you introduce any bugs.