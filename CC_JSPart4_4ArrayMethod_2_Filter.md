# Advance JS Part2 : 4.Array Method

[2. .filter()](https://docs.google.com/presentation/d/1jrkOP7nCQZN1H0v-77ohHYCdEs7wffdhtf7gQMfSfkw/edit#slide=id.g700e0f97b6_2_1159)  

ให้สร้าง array2  จาก array1 ตามที่โจทย์กำหนด โดยใช้ฟังก์ชัน Array.filter()  
  
2.1 filter เลขที่มากกว่า 10

```
array1 = [1, 2, 30, 400] 
array2 = [30, 400]
```
```js
// Write your answer below this line



```  
2.2 filter เลขคี่

```
array1 = [1, 2, 3, 4]
array2 =  [1, 3]
```
```js
// Write your answer below this line



```  
2.3 filter เฉพาะตัวเลข

```
array1 = [1, "1", 2, {}] 
array2 = [1, 2]
```
```js
// Write your answer below this line



```
2.4 filter ตัวอักษร > 6

```
array1 = ["apple", "banana", "orange", "pineapple", "watermeon"]
array2 = ["pineapple", "watermeon"]

```
```js
// Write your answer below this line



```
2.5 filter age < 18

```
array1 = [
      { name: "apple", age: 14 },
      { name: "banana", age: 18 },
      { name: "watermelon", age: 32 },
      { name: "pineapple", age: 16 },
      { name: "peach", age: 24 },
    ]
    array2 = [
      { name: "apple", age: 14 },
      { name: "pineapple", age: 16 },
    ]
```
```js
// Write your answer below this line



```

2.6 filter ไม่เอาคนที่อายุ 32

```
array1 = [
      { name: "apple", age: 14 },
      { name: "banana", age: 18 },
      { name: "watermelon", age: 32 },
      { name: "pineapple", age: 16 },
      { name: "peach", age: 24 },
    ]
array2 = [
      { name: "apple", age: 14 },
      { name: "banana", age: 18 },
      { name: "pineapple", age: 16 },
      { name: "peach", age: 24 },
    ]
```
```js
// Write your answer below this line



```

2.7 filter เลขบวก

```
array1 = [1, -3, 2, 8, -4, 5]
array2 = [1, 2, 8, 5]
```
```js
// Write your answer below this line



```
2.8 filter เลขหาร 3 ลงตัว

```
array1 = [1,3,4,5,6,7,8]
array2 = [3, 6]
```
```js
// Write your answer below this line



```
2.9 filter string

```
array1 = ["peach", 1, -3, "2", {}, []]
array2 ["peach", "2"]
```
```js
// Write your answer below this line



```
2.10 filter คำที่เป็นอักษรใหญ่ทุกตัว

```
array1 = ["APPLE", "appLE", "PEACH", "PEach"]
array2 = ["APPLE", "PEACH"]
```
```js
// Write your answer below this line



```
2.11  filter คนเกิดเดือน 10

```
array1 = [
       { name: "apple", birth: "2001-01-01" },
       { name: "banana", birth: "1990-10-10" },
       { name: "watermelon", birth: "1985-12-30" },
       { name: "peach", birth: "2002-10-13" },
     ]
array2 = [
       { name: "banana", birth: "1990-10-10" },
         { name: "peach", birth: "2002-10-13" },
     ]
```
```js
// Write your answer below this line



```
2.12 filter คนเกิดก่อนปี 2000

```
array1 = [
       { name: "apple", birth: "2001-01-01" },
       { name: "banana", birth: "1990-10-10" },
       { name: "watermelon", birth: "1985-12-30" },
       { name: "peach", birth: "2002-10-13" },
     ]
array2 = [
       { name: "banana", birth: "1990-10-10" },
       { name: "watermelon", birth: "1985-12-30" },
     ]
```
```js
// Write your answer below this line



```