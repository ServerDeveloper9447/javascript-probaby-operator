# JavaScript Probably `?==` Operator

This is the project to create a "probably" operator which will return a `boolean` based on the **probabilty** of the two operands being the same.

## Examples:
1. Result returned based on datatypes
```js
const int = 9;
const float = 9.88;

int ?== float // returns true

// but...

float ?== int // returns false
```

2. Result returned based on value that **will** be assigned to the variable.
```js
let int;
let float;

int ?== float // returns true at this point
float ?== int // returns true at this point

int = 5
float = 5.4

// goes back to the two expressions and turns the first true and second false
```

3. Predicting results based on quantum computing future telling.
```js
/*
 Some quantum computing to predict future
*/

int ?== float // returns true based on predictions
```
---
## Warning
**THE RESULTS RETURNED BY THE OPERATOR ARE UNPREDICTABLE.**