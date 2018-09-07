# JavaScript Bubble Sort
Hey, you like JavaScript? And bubbles? How about sorting?

Oh friend, have I got a function for you!

```javascript
function bubbleSort(array) {
  let swapsMade = false;
  
  array.forEach(function(element, index) {
    if (index <= array.length - 2 && number > array[index + 1]) {
      let temp = number;
      array[index] = array[index + 1];
      array[index + 1] = temp;
    }
  }
  
  if (swapsMade) return bubbleSort(array);
  
  return array;
}
```

Inspired by [Sarah Drasner's Tweet](https://twitter.com/sarah_edo/status/1037774093875965952)
