# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```let, var, or const

```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```A tool to have the program do something specific.

```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```Single Responisbility- SHould have one job
Open-closed-"open for extension, closed for modification"
Liskov Subsitiution-functions using references to classes should be able to use objects that came from the class without knowing it.
Interface segregation-make things work for individual clients and not just a one-shoe fits all situations.
Dependency Inversion- Depend on abstractions.

```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
position is 2. the first position always start on 0.
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```if(sugar is in it){
  don't eat it
}
Eat it

```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
iteration; you would use i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
document object model, the index.html is the first to access it.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
undefined, boolean, number, string, symbol, object, function, null
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
parameter is what is set outside (and often used inside) a function. When the parameter is called at the beginning of the function, in the parenthesis, it is called an argument.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
primitive are strings, symbols, numbers, boolean, undefined and null. A reference value is an object or an array.
```