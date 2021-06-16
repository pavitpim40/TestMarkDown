# Advance JS Part1 : 4.Object

[1.สร้าง Object](https://docs.google.com/presentation/d/155ujTF8dVcjw9J4wivPmyhnjsBkgXOHJ/edit#slide=id.p53)  
  
ให้สร้าง Object แบบ Object Literal โดยให้กำหนดตัวแปรชื่อ human โดยมี Properties ทั้ง 5 อย่าง
- ชื่อของผู้เรียน เป็น String
- อายุของผู้เรียนเป็น number
- บ้านของตัวเองเป็น String
- โสดหรือไม่โสดเป็น boolean
- คะแนนความฉลาดของตัวเองเป็น number (เต็ม 10)  
  
  
```js
// Finish and Paste your solution here



```

[2.Computed Property ข้อ1](https://docs.google.com/presentation/d/155ujTF8dVcjw9J4wivPmyhnjsBkgXOHJ/edit#slide=id.p56)  
  
- ให้เขียนโปรแกรมที่รับค่า key และ value ของ Properties ของ Object หนึ่ง จนกว่าจะเจอคำว่า stop  
- และนำค่าเหล่านั้นมาสร้าง Object  
- หลังจากนั้น console.log() object นั้นออกมา

```js
// Finish and Paste your solution here



```

[3.Computed Property ข้อ2](https://docs.google.com/presentation/d/155ujTF8dVcjw9J4wivPmyhnjsBkgXOHJ/edit#slide=id.p57)  

- ให้เขียนโปรแกรมที่รับค่า key และ value ของ Properties ของ Object หนึ่ง  
- โดยให้ key เป็นชื่อของผลไม้ และ value เป็นจำนวนของผลไม้ (number)   
- ถ้า ผลไม้ชนิดไหนที่มีมากกว่า 1 ผล ให้เติม s ไปหลัง key นั้นด้วย

```js
// Finish and Paste your solution here



```



[5.แก้ไข property](https://docs.google.com/presentation/d/155ujTF8dVcjw9J4wivPmyhnjsBkgXOHJ/edit#slide=id.p78)

- สร้าง Object เปล่าขึ้นมา
- เพิ่ม properties name เข้าไปและให้ value เป็น “Sonter”
- เพิ่ม properties surname เข้าไปและให้ value เป็น “Pakorn”
- เปลี่ยน properties name เป็น “Boy”
- ลบ properties name ออกจาก Object

```js
// Finish and Paste your solution here



```

[6.ตรวจสอบ property](https://docs.google.com/presentation/d/155ujTF8dVcjw9J4wivPmyhnjsBkgXOHJ/edit#slide=id.p79)  
  
  
  ให้เขียนฟังก์ชันชื่อ isEmpty(obj) โดยจะมี parameters เป็น obj และ ฟังก์ชันนี้จะเช็คว่า obj นี้มี properties ไหม ถ้ามีให้คืนค่า __true__ ถ้าไม่มีให้คืนค่า __false__
```js
// Finish and Paste your solution here



```

[7.การเขียนข้างล่างต่อไปนี้ Error  ไหม](https://docs.google.com/presentation/d/155ujTF8dVcjw9J4wivPmyhnjsBkgXOHJ/edit#slide=id.p80)

```js
const user = {
  name: "John"
};

// does it work?
user.name = "Pete";

// write your answer in this line : 
```

[8.Object with function](https://docs.google.com/presentation/d/155ujTF8dVcjw9J4wivPmyhnjsBkgXOHJ/edit#slide=id.p81https://docs.google.com/presentation/d/155ujTF8dVcjw9J4wivPmyhnjsBkgXOHJ/edit#slide=id.p81)  

- จงเขียนฟังก์ชัน sum(obj) ที่รับ obj ที่เก็บ properties โดยมี key เป็นชื่อพนักงานและมี value เป็นเงินเดือน  
- ให้ฟังก์ชันคืนค่าเป็นผลรวมของเงินเดือนพนักงานทั้งหมด


```js
let salaries = {
  John: 100,
  Ann: 160,
  Pete: 130
}

// Finish and Paste your solution below this line



```

[9.Object with function](https://docs.google.com/presentation/d/155ujTF8dVcjw9J4wivPmyhnjsBkgXOHJ/edit#slide=id.p82)  

- จงเขียนฟังก์ชัน multiplyNumeric(obj, times)   
- โดยถ้า properties นั้นมี value เป็น number ให้คูณ value นั้นด้วย times   
- ถ้าข้อมูลเป็นอย่างอื่นไม่ต้องทำอะไร

```js
// before the call
let menu = {
  width: 200,
  height: 300,
  title: "My menu"
};

multiplyNumeric(menu, 2);

// after the call
menu = {
  width: 400,
  height: 600,
  title: "My menu"
};
```

```js
// Finish and Paste your solution here



```