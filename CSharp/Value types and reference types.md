There are two different types of 'base types' in C#. Value types and reference types. 

### Value types
Value types are variables that hold a value. For example `int x = 3;` This will allocate memory so that when you type `x` in your code the computer will look at the memory and see that the memory allocated fo `x` in your computer holds the value 3.

### Reference types
However, reference types does not hold values. They hold 'pointers' (references) to some other location in memory where the value is stored. 
Example:
`myClass c = new myClass();` 
Here c will be a pointer (or reference) to where the actual instance is in memory.

### C# always passes by value
When using parameters and arguments in C#, remember that C# **always passes by value** i.e., if you change the value of a parameter in a method, the actual, passed variable's value will not be modified. Instead, what's happening is that C# passes a copy of the value/variable as the parameter. 

To pass a parameter by reference use the `ref` keyword before the parameters type keyword. %%You can also use the `out` keyword but then you need to instantiate it or something like that <-- unsure%%


%%
I think structs works like classes, so to use one you need to instatiate it and the store it in a variable. 
%%
%%
No, a class has _Reference semantics_ which means, a variable of a class contains a reference to the instance itself, whereas structures copies the values and becomes an instance.
%%