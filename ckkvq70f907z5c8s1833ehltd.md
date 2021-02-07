## Understanding Variables, Functions, and Scope in JavaScript




## Introduction
JavaScript is a programming language that makes web pages responsive. Thus, you’ll need to use some form of JavaScript to create a web page that goes beyond just displaying letters and pictures to being intuitive and user-friendly. We would discuss three concepts in JavaScript that are important for beginners to fully grasp to make their programming journey a little less chaotic.
 
### Variables 
Variables are a fundamental part of JavaScript and a very important concept for beginners to learn. It allows computers to store and manipulate information. This is done by using a unique name to point to a data rather than writing out the data each time you need it. In JavaScript, there are three keywords used to declare a variable — var, let, and const. These 3 variables have unique functions and achieve different results. 

- 
**Var** is a globally-scoped variable, it can be reassigned and redeclared.


![var.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1612735507177/kV87IdhsY.png)



- 
**Let** is a block-scoped, can be reassigned but cannot be redeclared 

![let.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1612735681915/nJJ5Ob7Hz.png)


- 
**Const**, which is short for constant, is block-scoped. It can neither be reassigned nor redeclared.


![Screenshot (146).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1612735735928/u2RN_itfO.png)

*Don’t worry if you don't understand how we arrived at the different city names, we’d talk about scopes shortly.
*
 ### Function
Functions can simply be defined as reusable code. You can call a function by using its name, followed by parentheses, like this: 
``` 
functionName(); 
``` 

![Screenshot (147).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1612736117393/aYi0cPRhB.png)

All of the code between the curly braces will be executed every time the function is called. This can vary from a one-line code to a ten-line code.

### Scope
Scope is a set of rules that determines where within a program you can access declared variables. Scope is not limited to variables but in most cases, you think of a variable when talking about scopes. Scope refers to the visibility of variables.

I’d be explaining two types of scope which are local and global.

- **Global variables**: When you start writing JavaScript in a document, you are already in the Global scope. A scope is global if it's defined outside of a function/block. This means they can be seen everywhere in your JavaScript code. Variables that are used without the var keyword are automatically created in the global scope. It is visible to always declare your variables.

![global scopes.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1612736263911/sM3nAWPq1.png)

- **Local variables** are those declared inside of a block or function.  That means they are only visible within that function.

![Screenshot (139).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1612736287233/viuJ-1OyW.png)

In the example above, you see that the scope of the variable local expired after the closing curly brace and it cannot be called or logged after it has expired.

It is also possible to have both local and global variables with the same name. When you do this, the local variable takes precedence over the global variable.
 
 
![global and local scop.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1612736307864/5XUNzuI0G.png)
 

## Conclusion

An easy way to understand this concept is to know that a variable is in scope in between the closest curly braces {}. Keep in mind that the variable will stay in scope as long as any scope it exists in still exists. If I declare a variable in an outer scope and modify a variable in an inner scope, that variable will survive as long as the outer scope does. It matters where the variable is declared.
 
 


> 
Never memorize something that you can look up.
-Albert Einstein

Cover photo credit: TechJuice.pk

