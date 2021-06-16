# Basic JS Part2 : 2.Loop (for,while)

[1.เลขที่ถูก alert เป็นลำดับสุดท้ายคือเลขอะไร
](https://docs.google.com/presentation/d/1c29n1gEZtH0YWYoxhFgKIi4D7bybkYH7e8sNNXwfseg/edit#slide=id.g7e5267d9ea_2_146)

```js
let i = 3;

while (i) {
  alert( i-- );
}
// write your answer in this line : 
```
[2.code ทั้งสองอันนี้จะแสดง alert ออกมาเหมือนกันทั้งหมดหรือไม่
](https://docs.google.com/presentation/d/1c29n1gEZtH0YWYoxhFgKIi4D7bybkYH7e8sNNXwfseg/edit#slide=id.g7e5267d9ea_2_159)

```js
//code1
let i = 0;
while (++i < 5) alert( i );

//code2
let i = 0;
while (i++ < 5) alert( i ); 

// write your answer in this line : 
```

[3.code ทั้งสองอันนี้จะแสดง alert ออกมาเหมือนกันทั้งหมดหรือไม่
](https://docs.google.com/presentation/d/1c29n1gEZtH0YWYoxhFgKIi4D7bybkYH7e8sNNXwfseg/edit#slide=id.g7e5267d9ea_2_170)

```js
//code1
for (let i = 0; i < 5; i++) alert( i );

//code2
for (let i = 0; i < 5; ++i) alert( i );

// write your answer in this line : 
```

[4.ให้เขียน loop ทั้งแสดงเลข 2 ถึง 10 ออกมา](https://docs.google.com/presentation/d/1c29n1gEZtH0YWYoxhFgKIi4D7bybkYH7e8sNNXwfseg/edit#slide=id.g7e5267d9ea_2_183)

```js
// Finish and Paste your solution here




```  
  
[5.เปลี่ยน code for loop ด้านล่างนี้ให้เป็น while loop โดยที่ผลลัพธ์ยังเหมือนเดิม](https://docs.google.com/presentation/d/1c29n1gEZtH0YWYoxhFgKIi4D7bybkYH7e8sNNXwfseg/edit#slide=id.g7e5267d9ea_2_183)

```js
for (let i = 0; i < 3; i++) {
  alert( `number ${i}!` );
}

// Finish and Paste your solution below this line : 


```

[6.ให้เขียนเกมส์ทายตัวเลขสำหรับเล่นสองคน](https://docs.google.com/presentation/d/1c29n1gEZtH0YWYoxhFgKIi4D7bybkYH7e8sNNXwfseg/edit#slide=id.g7e5267d9ea_2_200)

- ให้ผู้เล่นคนแรกพิมพ์เลขใส่ใน prompt ที่อยู่ระหว่าง 1 ถึง 100 โดยไม่ให้ผู้เล่นคนที่สองรู้ว่าตัวเลขเป็นอะไร
- และให้ผู้เล่นคนที่สองทายเลขโดยการพิมพ์เลขใส่ใน prompt จนกว่าจะถูก  
- ถ้าไม่ถูก จะต้องบอกด้วยว่าเลขที่ผู้เล่นคนที่สองพิมพ์เข้ามา มากกว่า หรือ น้อยกว่าคำตอบนั้น

```js
// Finish and Paste your solution here




```  