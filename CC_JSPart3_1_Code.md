# Advance JS Part1 : 1.Code

[1.แก้ไขการเขียนโค้ดต่อไปนี้](https://docs.google.com/presentation/d/155ujTF8dVcjw9J4wivPmyhnjsBkgXOHJ/edit#slide=id.p24)

```js
function pow(x,n)
{
  let result=1;
  for(let i=0;i<n;i++) {result*=x;}
  return result;
}
let x=prompt("x?",''), n=prompt("n?",'')
if (n<=0)
{
  alert(`Power ${n} is not supported, please enter an integer number greater than zero`);
}
else
{
  alert(pow(x,n))
}

```

```js
// Finish and Paste your solution here



```