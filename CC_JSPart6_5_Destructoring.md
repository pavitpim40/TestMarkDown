# Advance JS Part6(ForReact) : Destructuring

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