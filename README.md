# snippets
A collection of class-related code &amp; concepts.

- [snippets](#snippets)
  - [General](#general)
    - [Array Loop](#array-loop)
    - [Ternary Operator](#ternary-operator)

## General

### Array Loop

```javascript
var myArray = ["beep", "bop", "boop"];

myArray.forEach((item, index) => {
    console.log(index);
console.log(item);
});

// beep
// boop
// bop
```
`#array #forEach #javascript`


### Ternary Operator

```javascript
var isCool = true;
var message = isCool ? "😎" : "🤓";
console.log(message);

// 😎
```
`#ternary #conditional #javascript`