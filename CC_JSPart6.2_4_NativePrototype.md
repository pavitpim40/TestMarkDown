# advance JS Part6.2(ForReact) : 3.Native Prototype

[1.Add method](https://docs.google.com/presentation/d/1Exa9wm8LqxPlLEIuhvcn4RPHGzEXmEID/edit#slide=id.p67)

- ให้เพิ่ม Method defer เข้าไปใน prototypes ของทุกฟังก์ชัน 
- โดย Method นี้จะทำหน้าที่ alert ข้อความออกมาหลังจากผ่านไป ms

```js
function f() {
  alert("Hello!");
}
// write your code below this line





// write your code above this line
f.defer(1000);
```


[2.Add method and return function](https://docs.google.com/presentation/d/1Exa9wm8LqxPlLEIuhvcn4RPHGzEXmEID/edit#slide=id.p68) Optional  

- ให้เพิ่ม Method defer เข้าไปใน prototypes ของทุกฟังก์ชัน  
- โดย Method นี้จะทำหน้าที่ return Function ให้ alert(a+b) เมื่อผ่านไป ms



```js
function f(a, b) {
  alert( a + b );
}
// write your code below this line





// write your code above this line

f.defer(1000)(1, 2); // แสดง 3 หลังจากผ่านไป 1 วินาที
```
