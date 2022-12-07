### Goal: Write your own “documentation” for the higher order functions
**Your documentation should include:**
- A description of the purpose
- A description of the syntax
- An example
- An explanation of the example
- Any additional notes/details

---
Your documentation here: 

**Purpose**

Functions abstract the details 
Abstract away the details to think on a higher level

**Syntax**

**Example**

```js
const fellows = ['ethan', 'gabe', 'cas'];
const madFellows = [];
function addMadFellow(fellow) {
    madFellows.push(fellow.toUpperCase() + '!!!');
}
fellows.forEach(e => addMadFellow(e));
console.log(madFellows)
```

**Explanation of Example**

- The variable `fellows` is declared and initialized with the value of `['ethan', 'gabe', 'cas']`
- 

**Additional Notes/Details**
