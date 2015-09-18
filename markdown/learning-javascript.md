# Javascript

## Expressions 

An `expression` always evaluates to to s single value. Generally speaking, there are 
two types of `expressions`.

1. `Expression ` that assigns a value to a `var`. Example: var power = 'lightning"
2. `Expression ` that uses two or more values to return a single value. Example: var area = 5 * 3;

Expressions rely on **operators** to create a single value.

* Assignment operator `=`
* Math operator `*` `+` `/` `%`
* String operator 'Hey' `+` 'Worbs`.
* Comparison operator nope 1 `>` 2.
* Logical operators  And `&&`, Or `||`,  Not  `!`

-----------
## Functions and Methods
 
###  Method 
A `method` is the **same** as a `function`. It's just a `function` that's **created within** and **part of** an `object`. 

### Object
An `object` is made up of *name* and *value* pairs. The *values* can be `properties` or `methods`.

### Built-in objects 
The browser comes with a set of built-in `objects` that we can access and use.

### FUNCTION EXPRESSIONS
This is know as a **function expression** since the function was placed in the location where a *value* was expected.  Since it has no *name*, it's also know as an **anonymous function**
This is a **function expression**: 

    var worbs = function(x, y) {
      return x + y;
    };
    worbs(1, 2);
    // You can assign the value to a variable  and call the function in one line
    // var what = worbs(1, 2)

Remember in 

    var name = 'worbs';
`worbs` is the **expression**.

### FUNCTION DECLARTION
A **function declaration** is a function with a *name*.  They are also called **named functions**.  Since it has a name, you can call it (it must be called to be used) later in your code.  

This is a **function declaration**: 

    function worbs(x, y) {
      return x + y;
    }
    worbs(1, 2);
     // You can assign the value to a variable  and call the function in one line
     // var what = worbs(1, 2)


### IMMEDIATELY INVOKED FUNCTION EXPRESSION (IIFE)
A **IIFE** is a function **without** a *name*.  They are executed as soon as the interpreter comes across them. 

In this example, the variable called *worbs* will **hold the value returned from the function** rather than storing the function so it can be called later.

This is a **immediately invoked function expression (IIFE)**: 

    var worbs = (function() {
      var x = 4;
      var y = 17;
      return x + y;
    }());

The **last paired parentheses** (after the  closing `}` ) tell the interpreter to call the function *immediately* upon finding it. The  opening `(` before the keyword *function*  and  the closing `)` before the final `;` (called *grouping operators*) are there  to make sure the interpreter treats it like an *expression*. 


#TO DO

Write about when to use IIFE and Anonymous functions  
* * * *














