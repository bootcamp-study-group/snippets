# snippets 📚

A collection of class-related code &amp; concepts.

<details><summary><i>Find some useful code while completing a challenge or project?</i></summary> 
  
- Fork this repository
- Add your snippet
- Tag the classwork (#module3, #challenge4, etc)
- Create a pull-request!
  
</details>

<details><summary><i>Have a question/request?</i></summary>
  
- Create an Issue
- Give details
- Submit!
  
</details>

- [snippets 📚](#snippets-)
  - [General](#general)
    - [Array Loop](#array-loop)
    - [Ternary Operator](#ternary-operator)
    - [Concatenate](#concatenate)

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

### Concatenate

```javascript
var java = "java";
var script = "script";

var javascript = java.concat("", script);
var blasphemy = script.concat(" with ", java);

console.log(javascript);
console.log(blasphemy);

// javascript
// script with java
```
`#concat #string #javascript #module3`

---

[Back to top 🔝](#snippets-)
