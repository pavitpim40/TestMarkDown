# Basic JS Part2 : 6.ArrowFunction

[1.แปลง function ข้างล่างให้อยู่ในรูป arrow function
](https://docs.google.com/presentation/d/1c29n1gEZtH0YWYoxhFgKIi4D7bybkYH7e8sNNXwfseg/edit#slide=id.g7e6a95f2bd_7_86)

```js
function ask(question, yes, no) {
  if (confirm(question)) yes()
  else no();
}

ask(
  "Do you agree?",
  function() { alert("You agreed."); },
  function() { alert("You canceled the execution."); }
);
// Finish and Paste your solution below this line 

```