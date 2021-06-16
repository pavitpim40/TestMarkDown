# Advance JS Part2 : 6.Map and Set

[1.Unique Item](https://docs.google.com/presentation/d/1jrkOP7nCQZN1H0v-77ohHYCdEs7wffdhtf7gQMfSfkw/edit#slide=id.g700e0f97b6_2_1494)
- ให้ arr เป็น Array
- สร้าง function ชื่อ unique(arr) ให้คืนค่าเป็น unique items ของ arr 


```js
function unique(arr) {
  /* your code */


}

let values = ["Hare", "Krishna", "Hare", "Krishna", "Krishna", "Krishna", "Hare", "Hare", ":-O" ];

alert( unique(values) ); // Hare, Krishna, :-O
```

[2.Anagram](https://docs.google.com/presentation/d/1jrkOP7nCQZN1H0v-77ohHYCdEs7wffdhtf7gQMfSfkw/edit#slide=id.g700e0f97b6_2_1503) (Optional)
Anagram เป็นตัวอักษรที่มีจำนวนตัวอักษรแต่ละตัวที่เท่ากัน แต่เรียงไม่เหมือนกัน
```
nap - pan
ear - are - era
cheaters - hectares - teachers
```

```js
let arr = ["nap", "teachers", "cheaters", "PAN", "ear", "era", "hectares"];
/* your code */




/* your code */
alert( aclean(arr) ); // "nap,teachers,ear" or "PAN,cheaters,era"
```

[3.Push](https://docs.google.com/presentation/d/1jrkOP7nCQZN1H0v-77ohHYCdEs7wffdhtf7gQMfSfkw/edit#slide=id.g700e0f97b6_2_1513)  
- เราได้ array จาก map.keys()  
- แต่ไม่สามารถใช้ push ได้  
- เราจะทำยังไงให้ keys.push สามารถทำงานได้


```js
let map = new Map();

map.set("name", "John");

let keys = map.keys();

// Error: keys.push is not a function
keys.push("more");

```

```js
// write your code here



```