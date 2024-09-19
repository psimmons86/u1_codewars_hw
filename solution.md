## Return Negative

```js
function makeNegative(num) {
  if (num < 0) {
    return num;
  } else {
    return num * -1;
  }
}
```

## Sum of Positive

```js
function positiveSum(arr) {
  let sum = 0;
  for (let i = 0; i < arr.length; i++)
    if (arr[i] > 0) {
      sum += arr[i];
    }
  return sum;
}
```

## Function 2

```js
// Write the "square"-function here
const square = (num) => {
  return num * num;
};
```

## Sum Arrays

```js
// referenced https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce
function sum(numbers) {
  "use strict";
  let sum = 0;
  const finalTotal = numbers.reduce(
    (accumulator, value) => accumulator + value,
    sum
  );
  return finalTotal;
}
```

## Reversed Strings

```js
function solution(str) {
  let strRev = "";
  for (let i = str.length - 1; i >= 0; i--) {
    strRev += str[i];
  }
  return strRev;
}
```
