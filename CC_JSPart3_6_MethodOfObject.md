# Advance JS Part1 : 6.Method Of Object

[1.การทำงานของ code ดังกล่าวจะได้อะไรออกมา
](https://docs.google.com/presentation/d/155ujTF8dVcjw9J4wivPmyhnjsBkgXOHJ/edit#slide=id.p100)

```js
let user = {
  name: "John",
  go: function() { alert(this.name) }
}

(user.go)()

// write your answer in this line : 
```

[2.การทำงานของ code ดังกล่าวจะได้อะไรออกมา
](https://docs.google.com/presentation/d/155ujTF8dVcjw9J4wivPmyhnjsBkgXOHJ/edit#slide=id.p101)

```js
function makeUser() {
  return {
    name: "John",
    ref: this
  };
};

let user = makeUser();

alert( user.ref.name ); // What's the result?
// write your answer in this line : 
```


[3.สร้าง Method](https://docs.google.com/presentation/d/155ujTF8dVcjw9J4wivPmyhnjsBkgXOHJ/edit#slide=id.p102)  
- สร้าง object calculator จาก 3 methods นี้  
- read() ใช้ prompts สำหรับรับค่ามา 2 ค่าและเก็บเป็น object properties.  
- sum() คืนค่าผลบวกของ 2 ค่านั้น.  
- mul() คืนค่าผลคูณของ 2 ค่านั้น.


```js
let calculator = {
// write your answer below this line



};

calculator.read();
alert( calculator.sum() );
alert( calculator.mul() );
```

[4.Ladder](https://docs.google.com/presentation/d/155ujTF8dVcjw9J4wivPmyhnjsBkgXOHJ/edit#slide=id.p103)
- สร้าง Object ชื่อ ladder มี
- method ขึ้น และ ลง
- Object ชื่อ ladder สามารถเรียก function แบบนี้ได้

```js
ladder.up();
ladder.up();
ladder.down();
ladder.showStep(); // 1
```

```js
// write your answer below this line



```
[5.Ladder](https://docs.google.com/presentation/d/155ujTF8dVcjw9J4wivPmyhnjsBkgXOHJ/edit#slide=id.p105)
- ดัดแปลง Object ชื่อ ladder สามารถเรียก function แบบนี้ได้

```js
ladder.up().up().down().showStep(); // 1
```


```js
// write your answer below this line



```