# Advance JS Part2 : 1.String Method

[1.Capital Letter](https://docs.google.com/presentation/d/1jrkOP7nCQZN1H0v-77ohHYCdEs7wffdhtf7gQMfSfkw/edit#slide=id.g700e0f97b6_2_533)  
เขียนฟังก์ชัน ucFirst(string) โดยทำคืนค่าเป็น string เดิม แต่ตัวแรกของ string กลายเป็นพิมพ์ใหญ่


```js
// Write your answer below this line 



```

[2.String Check](https://docs.google.com/presentation/d/1jrkOP7nCQZN1H0v-77ohHYCdEs7wffdhtf7gQMfSfkw/edit#slide=id.g700e0f97b6_2_541)  
- เขียนฟังก์ชันที่ checkSpam 
- โดยถ้าข้อความดังกล่าวมีคำว่า “xxx” หรือ “viagra” ให้คืนค่าเป็น true  
- ถ้าไม่มีให้คืนค่าเป็น false

```js
// Write your answer below this line 



```

[3.Length Check](https://docs.google.com/presentation/d/1jrkOP7nCQZN1H0v-77ohHYCdEs7wffdhtf7gQMfSfkw/edit#slide=id.g700e0f97b6_2_549)

- เขียนฟังก์ชันที่ truncate(str, maxlength) 
- โดยฟังก์ชันดังกล่าวจะเช็คว่า string ที่ถูกส่งเข้ามามีความยาวเกิน maxlength ไหม 
- ถ้าเกินให้แทน ข้อความต่อจากนั้นด้วย “...”

```js
// Write your answer below this line 




// Do not write your answer below this line 

truncate("What I'd like to tell on this topic is:", 20) // "What I'd like to te…"
truncate("Hi everyone!", 20) // "Hi everyone!"
```

[4.Extract](https://docs.google.com/presentation/d/1jrkOP7nCQZN1H0v-77ohHYCdEs7wffdhtf7gQMfSfkw/edit#slide=id.g700e0f97b6_2_558)
- เขียนฟังก์ชันที่ extractCurrencyValue(string, rate) 
- โดยที่ฟังก์ชันดังกล่าวจะแปลง string ที่เป็นค่าเงิน dollar ให้เป็น number ที่มีค่าเป็นเงินบาทไทย  
- โดยอ้างอิง rate จาก parameters ตัวที่สองที่ส่งมาให้

```js
// Write your answer below this line 




// Do not write your answer below this line 

alert( extractCurrencyValue('$120', 30.5) === 3660 ); // true
```