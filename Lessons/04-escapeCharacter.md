##Escape Character
Because strings must be written within quotes, JavaScript will misunderstand this string:

```
let text = "We are the so-called "Vikings" from the north.";
```

The string will be chopped to "We are the so-called ".

The solution to avoid this problem, is to use the backslash escape character. The backslash (\\) escape character turns special characters into string characters:

```
let text = "We are the so-called \"Vikings\" from the north.";
let text= 'It\'s alright.';
```
