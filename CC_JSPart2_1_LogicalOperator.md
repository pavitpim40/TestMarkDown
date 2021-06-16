# Basic JS Part2 : 1.ตัวดำเนินการแบบตรรกะ

[1.คำสั่งต่อไปนี้จะแสดงค่าเป็นอะไร
](https://docs.google.com/presentation/d/1c29n1gEZtH0YWYoxhFgKIi4D7bybkYH7e8sNNXwfseg/edit#slide=id.g7e4f968bee_0_224)

```js
//เขียนคำตอบเป็นคอมเมนท์ต่อท้ายแต่ละบรรทัด

alert( null || 2 || undefined );
alert( alert(1) || 2 || alert(3) );
alert( 1 && null && 2 );
alert( alert(1) && alert(2) );
alert( null || 2 && 3 || 4 );
```

[2.เขียนคำสั่ง if ที่เช็คอายุว่าอยู่ระหว่าง 18 - 60
](https://docs.google.com/presentation/d/1c29n1gEZtH0YWYoxhFgKIi4D7bybkYH7e8sNNXwfseg/edit#slide=id.g7e4f968bee_0_240)

```js
// Finish and Paste your solution here




```


[3.เขียนคำสั่ง if ที่เช็คอายุว่าไม่อยู่ระหว่าง 18 - 60
](https://docs.google.com/presentation/d/1c29n1gEZtH0YWYoxhFgKIi4D7bybkYH7e8sNNXwfseg/edit#slide=id.g7e4f968bee_0_240)
```js
// Finish and Paste your solution here




```

[4.คำสั่ง alert ไหนที่จะถูกรันบ้าง](https://docs.google.com/presentation/d/1c29n1gEZtH0YWYoxhFgKIi4D7bybkYH7e8sNNXwfseg/edit#slide=id.g7e4f968bee_0_248)

```js
//เขียนคำตอบเป็นคอมเมนท์ต่อท้ายแต่ละบรรทัด 

if (-1 || 0) alert( 'first' );
if (-1 && 0) alert( 'second' );
if (null || -1 && 0) alert( 'third' );
```

[5.ให้เขียนระบบ login (WorkShop)](https://docs.google.com/presentation/d/1c29n1gEZtH0YWYoxhFgKIi4D7bybkYH7e8sNNXwfseg/edit#slide=id.g7e4f968bee_0_259)
- ให้ใช้ prompt ในการถามใครเป็นคน login  
- ถ้าผู้ใช้กรอกว่า “Admin” ให้ใช้ prompt ถาม password  
- วิธีเช็ค Password  
    - ถ้า string นั้นเป็น “codecamp” ให้ alert “ยินดีต้อนรับ”  
    - ถ้า string เป็นอย่างอื่นให้ alert เป็น “Wrong password”  
- ถ้าผู้ใช้กรอกอย่างอื่นที่ไม่ใช่ “Admin” ให้ alert ว่า “ผมไม่รู้จักคุณ”  
- ถ้าผู้ใช้กรอก input เป็น string ว่าง หรือกด Esc ให้ alert ว่า “ยกเลิก”
```js
// Finish and Paste your solution here




```
