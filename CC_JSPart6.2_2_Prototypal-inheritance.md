# Advance JS Part6.2(ForReact) : 2.Prototypal inheritance


[1.ในบรรทัดที่มีเลข 1 2 และ 3 จะได้ค่าออกมาเป็นอะไร](https://docs.google.com/presentation/d/1Exa9wm8LqxPlLEIuhvcn4RPHGzEXmEID/edit#slide=id.p29) 


```js
let animal = {
  jumps: null
};

let rabbit = {
  __proto__: animal,
  jumps: true
};

alert( rabbit.jumps ); // ? (1)

delete rabbit.jumps;

alert( rabbit.jumps ); // ? (2)

delete animal.jumps;

alert( rabbit.jumps ); // ? (3)
```


[3.การเขียนโค๊ดแบบนี้ object ไหนจะเป็นคนได้ property full ไป ](https://docs.google.com/presentation/d/1Exa9wm8LqxPlLEIuhvcn4RPHGzEXmEID/edit#slide=id.p31)

```js
let animal = {
  eat() {
    this.full = true;
  }
};

let rabbit = {
  __proto__: animal
};

rabbit.eat();

// Write your answer in this line : 
```