## Template Literals - String Templates

Suppose we have these variables and we need to print them

```diff
let a = “We Love”;
let b = “JavaScript”;
let c = “And”;
let d = “Programming”;
```

Instead of writing:

```diff
console.log(a + “ ” + b + “ ” +
“\n” + c + “ ” + d);

```

We can write:

```diff
console.log(`${a} ${b}
${c} ${d}`);
```
