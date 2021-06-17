# Advance JS Part6.2(ForReact) : 3. F.Prototype


[1.](https://docs.google.com/presentation/d/1Exa9wm8LqxPlLEIuhvcn4RPHGzEXmEID/edit#slide=id.p48)  

จากโค๊ดต่อไปนี้มีการสร้าง new Rabbit() ขึ้นมา
```js
function Rabbit() {}
Rabbit.prototype = {
  eats: true
};

let rabbit = new Rabbit();

alert( rabbit.eats ); // true
```

- ถ้ามีการ alert ในบรรทัดดังกล่าวจะได้อะไรออกมา

```js
function Rabbit() {}
Rabbit.prototype = {
  eats: true
};

let rabbit = new Rabbit();

Rabbit.prototype = {};

alert( rabbit.eats ); // write your answer here
```

```js
function Rabbit() {}
Rabbit.prototype = {
  eats: true
};

let rabbit = new Rabbit();

Rabbit.prototype.eats = false;

alert( rabbit.eats ); // write your answer here
```

```js
function Rabbit() {}
Rabbit.prototype = {
  eats: true
};

let rabbit = new Rabbit();

delete rabbit.eats;

alert( rabbit.eats ); // write your answer here
```

```js
function Rabbit() {}
Rabbit.prototype = {
  eats: true
};

let rabbit = new Rabbit();

delete Rabbit.prototype.eats;

alert( rabbit.eats ); // write your answer here
```

[2.ถ้าเราต้องการสร้างใช้ constructor ของ obj เราสามารถเขียนแบบนี้ได้ไหม](https://docs.google.com/presentation/d/1Exa9wm8LqxPlLEIuhvcn4RPHGzEXmEID/edit#slide=id.p53)

```js
let obj2 = new obj.constructor();

 // write your answer here
```