## Spread & Rest Operator

 #### Spread Operator: 
* Spread operator consists of three dots.
* Allows us to spread out elements of an iterable object like array, map or set.

```javascript
1) Constructing array literal
The spread operator allows you to insert another array into the initialized array when you construct an array using the literal form. See the following example:

let initialChars = ['A', 'B'];
let chars = [...initialChars, 'C', 'D'];
console.log(chars); // ["A", "B", "C", "D"]

```

```javascript
2) Concatenating arrays
Also, you can use the spread operator to concatenate two or more arrays:

let numbers = [1, 2];
let moreNumbers = [3, 4];
let allNumbers = [...numbers, ...moreNumbers];
console.log(allNumbers); // [1, 2, 3, 4]

```

```javascript
let chars = ['A', ...'BC', 'D'];
console.log(chars); // ["A", "B", "C", "D"]

```
 ---------------------------------------