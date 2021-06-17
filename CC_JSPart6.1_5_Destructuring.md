# Advance JS Part6.1(ForReact) : Destructuring

[1.Destructuring](https://docs.google.com/presentation/d/1hvv6JOhOGVyWeNRkjeeRFfd_0wj8lUre/edit#slide=id.p100)  
ให้เขียน Destructuring assignment โดย  
- property ที่ชื่อ name ไปอยู่ในตัวแปร name
- property ที่ชื่อ years ไปอยู่ในตัวแปร age
- property ที่ชื่อ isAdmin ไปอยู่ในตัวแปร isAdmin (ให้เป็น false ถ้าไม่มีค่าให้กำหนด)


```js
let user = {
    name: "John",
    years: 30
};
// write your code below this line 



```
[2.](https://docs.google.com/presentation/d/1hvv6JOhOGVyWeNRkjeeRFfd_0wj8lUre/edit#slide=id.p101)  

ให้สร้าง function topSalary(salaries) ที่คืนค่าชื่อคนที่มีเงินเดือนสูงสุด
- ถ้า salaries ไม่มีข้อมูลให้คืนค่าเป็น null
- ถ้าสูงสุดมีหลายคน ก็ให้คืนใครก็ได้สักคน

```js
let salaries = {
    "John": 100,
    "Pete": 300,
    "Mary": 250
};
// write your code below this line



```
[3.การเขียนโค๊ดแบบนี้ object ไหนจะเป็นคนได้ property full ไป](https://docs.google.com/presentation/d/1Exa9wm8LqxPlLEIuhvcn4RPHGzEXmEID/edit#slide=id.p31)

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

// write your answer in this line : 
```  

[4.โค้ดดังกล่าวจะทำให้ property กระเพราะถูกแชร์กัน จะแก้ไขยังไงดี](https://docs.google.com/presentation/d/1Exa9wm8LqxPlLEIuhvcn4RPHGzEXmEID/edit#slide=id.p32)

```js
let hamster = {
  stomach: [],

  eat(food) {
    this.stomach.push(food);
  }
};


let speedy = {
  __proto__: hamster
};

let lazy = {
  __proto__: hamster
};

// This one found the food
speedy.eat("apple");
alert( speedy.stomach ); // apple

// This one also has it, why? fix please.
alert( lazy.stomach ); // apple
```

```js
// write your code below this line





```