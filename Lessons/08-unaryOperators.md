## Unary Operators

### Unary Plus
If it is not a number, it returns a number.
```diff 
Console.log(+100); // returns 100
Console.log(+”100”); // returns 100
Console.log(+”-100”); // returns -100
Console.log(+”Houssam”); // returns NaN (Not a Number)
Console.log(+”15.5”); // returns 15.5
Console.log(+0xff); // returns 255
Console.log(+null); // returns 0
Console.log(+false);  // returns 0
Console.log(+true); // returns 1
```
### Unary Negation
If it is not a number, it returns a number and negates it.
```diff 
Console.log(-100); // returns -100
Console.log(-”100”); // returns -100
Console.log(-”-100”); // returns 100
Console.log(-”Houssam”); // returns NaN (Not a Number)
Console.log(-”15.5”); // returns -15.5
Console.log(-0xff); // returns -255
Console.log(-null); // returns -0
Console.log(-false);  // returns -0
Console.log(-true); // returns -1
```