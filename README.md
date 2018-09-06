# javascript-bubblesort
Bubble sort with JavaScript, because why not?

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
