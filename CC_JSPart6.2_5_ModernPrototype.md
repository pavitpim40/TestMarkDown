# Advance JS Part6.2(ForReact) : 5.Modern Prototype

[1.](https://docs.google.com/presentation/d/1Exa9wm8LqxPlLEIuhvcn4RPHGzEXmEID/edit#slide=id.p76)
- มี Object Dictionary ที่สร้างจาก Object.create(null) เพื่อเก็บ key/value pairs
- ให้เพิ่ม Method dictionary.toString() และคืนค่าเป็น key ทั้งหมดออกมาที่คั้นด้วย comma

```js 
let dictionary = Object.create(null);

// your code to add dictionary.toString method
// Finish and write your answer here






// add some data
dictionary.apple = "Apple";
dictionary.__proto__ = "test"; // __proto__ is a regular property key here

// only apple and __proto__ are in the loop
for(let key in dictionary) {
  alert(key); // "apple", then "__proto__"
}

// your toString in action
alert(dictionary); // "apple,__proto__"
```

[2.](https://docs.google.com/presentation/d/1Exa9wm8LqxPlLEIuhvcn4RPHGzEXmEID/edit#slide=id.p78)

- สร้าง object rabbit ด้วย new keyword

```js
function Rabbit(name) {
  this.name = name;
}
Rabbit.prototype.sayHi = function() {
  alert(this.name);
};

let rabbit = new Rabbit("Rabbit");
```

- คำสั่งทั้งหมดนี้ทำงานเหมือนกันหรือไม่
```js
rabbit.sayHi(); 
Rabbit.prototype.sayHi();
Object.getPrototypeOf(rabbit).sayHi();
rabbit.__proto__.sayHi();

// write your answer below this line




```