## Variables

Variables are containers for storing data (storing data values). Creating a variable in JavaScript is called "declaring" a variable. In this example, x, y, and z, are variables, declared with the var keyword:

```
var x = 5;
var y = 6;
var z = x + y;
```

####Var vs Let vs Const

| &ensp;                   | var       | let   | const |
| ------------------------ | --------- | ----- | ----- |
| Redeclare                | Yes       | No    | No    |
| Accessing Before Declare | Undefined | Error | Error |
| Block Scope              | No        | Yes   | Yes   |

#####Block Scope:
Variables declared inside a { } block cannot be accessed from outside the block; Example:

```
{
Let x =2;
}
// x can NOT be used here
```

Variables declared with the var keyword can NOT have block scope. Example:

```
{
  var x = 2;
}
// x CAN be used here
```

##### Local Scope:

Variables declared within a JavaScript function, become LOCAL to the function. Example:

```
// code here can NOT use carName
function myFunction() {
  let carName = "Volvo";
  // code here CAN use carName
}
// code here can NOT use carName
```

Local variables have Function Scope: They can only be accessed from within the function.

##### Function Scope:
JavaScript has function scope: Each function creates a new scope.
Variables defined inside a function are not accessible (visible) from outside the function.
