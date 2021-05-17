# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
Let, var and const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
a function is a sub program designed to perform a particular task.
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single responsibility
Open closed 
Liskov substitution
Interface segregation 
Dependency inversion
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
[2], arrays are indexed starting at zero left to right
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
array.prototype.push.apply(you,them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```if(   bool   statement)
  else (   then   ){
    do this
  }
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
incrementor, ++ would increment by 1 each loop
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
document object model, html file is accessed first (doc type)
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
primitives : undefined, bool, number, string, bigint, symbol, null, Strucural: object, function. 
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
params are supplied with the def of the function as place holders for the arguments that are supplied later when the function is envoked.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
primitive values are immutable values that cant be changed. reference values are objects that are possibly referenced by identifiers.
```