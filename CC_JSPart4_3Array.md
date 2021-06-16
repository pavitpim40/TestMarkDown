# Advance JS Part2 : 3.Array

[1.Find Length](https://docs.google.com/presentation/d/1jrkOP7nCQZN1H0v-77ohHYCdEs7wffdhtf7gQMfSfkw/edit#slide=id.g700e0f97b6_2_820) ผลลัพธ์ของความยาว array คืออะไร

```js
let fruits = ["Apples", "Pear", "Orange"];

let shoppingCart = fruits;
shoppingCart.push("Banana");

alert( fruits.length ); // answer here
```

[2.Work with element](https://docs.google.com/presentation/d/1jrkOP7nCQZN1H0v-77ohHYCdEs7wffdhtf7gQMfSfkw/edit#slide=id.g700e0f97b6_2_829) ให้ทำตามขั้นตอนต่อไปนี้  
- สร้าง array ชื่อ styles ที่มี items ชื่อ “Jazz” และ “Blues”
- เพิ่ม “Rock-n-Roll” ต่อท้าย
- นำค่า Classics ไปทับค่าตรงกลางของ Array
- นำ items ตัวแรกออกมาและลบ items ตัวนั้นออกจาก array
- เพิ่ม “Rap” และ “Reggae” ไปข้างหน้าของ Array



```js
// Write your answer below this line 




```

[3.เขียนฟังก์ชัน sumInput()](https://docs.google.com/presentation/d/1jrkOP7nCQZN1H0v-77ohHYCdEs7wffdhtf7gQMfSfkw/edit#slide=id.g700e0f97b6_2_845)  
- ใช้ propmt รับ value มาเก็บใน array
- หยุดถามเมื่อเจอค่าที่ไม่ใช่ ตัวเลข
- คำนวณผลรวมของตัวเลขทั้งหมดใน Array

```js
// Write your answer below this line 




```

[4.Maximal contiguous subarray (**Optional**)](https://docs.google.com/presentation/d/1jrkOP7nCQZN1H0v-77ohHYCdEs7wffdhtf7gQMfSfkw/edit#slide=id.g700e0f97b6_2_853)  
- ให้เขียนฟังก์ชัน getMaxSubSum(arr) ที่ return ผลรวมของ subarray ที่มากที่สุดที่ติดกัน

```js
// Write your answer below this line 




// Do not write your answer below this line 

getMaxSubSum([-1, 2, 3, -9]) // return 5 from sum of 2,3
getMaxSubSum([2, -1, 2, 3, -9])  //return 6 from sum of 2, -1, 2, 3
getMaxSubSum([-1, 2, 3, -9, 11]) // return 11
getMaxSubSum([-2, -1, 1, 2]) // return 3 from  sum of 1,2
getMaxSubSum([100, -9, 2, -3, 5]) // return 100
getMaxSubSum([1, 2, 3]) // return 6 from sum of all
```