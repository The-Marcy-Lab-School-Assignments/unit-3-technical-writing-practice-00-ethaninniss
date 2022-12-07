### Goal: Write your own “documentation” for the higher order functions
**Your documentation should include:**
- A description of the purpose
- A description of the syntax
- An example
- An explanation of the example
- Any additional notes/details

---
Your documentation here: 

# Higher Order Functions

### Purpose

Functions abstract the details 
Abstract away the details to think on a higher level

### Syntax

### Example

```js
const fellows = ['ethan', 'gabe', 'cas'];
const madFellows = [];
function addMadFellow(fellow) {
    madFellows.push(fellow.toUpperCase() + '!!!');
}
fellows.forEach(addMadFellow);
console.log(madFellows)
```

### Explanation of Example

- The variable `fellows` is declared and initialized with the value of `['ethan', 'gabe', 'cas']`
- The variable `madFellows` is declared and initialized with the value of `[]`
- The function `addMadFellow` is created and takes in one parameter which is a string
- The code inside `addMadFellow` takes the parameter and uppercases it and adds 3 exclamation points to the end
    ```js
    fellow.toUpperCase() + '!!!'
    ```
- Then it takes that value and pushes it into the array of `madFellows`
    ```js
    madFellows.push(fellow.toUpperCase() + '!!!');
    ```
- Then we use `forEach` to loop through fellows
- Then inside the parenthesis’s we are telling the code what we want to do to each element
- Inside the parenthesis we are calling the function `addMadFellow` which takes the element and uses it as a parameter for the function
- 

### Additional Notes/Details

