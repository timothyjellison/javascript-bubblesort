# JavaScript Bubble Sort
Hey, you like JavaScript? And bubbles? How about sorting?

Oh friend, have I got a function for you!

```javascript
function bubbleSort(array) {
  let swapsMade = false;
  
  array.forEach(function(element, index) {
    if (index <= array.length - 2 && element > array[index + 1]) {
      let temp = element;
      array[index] = array[index + 1];
      array[index + 1] = temp;
    }
  }
  
  if (swapsMade) return bubbleSort(array);
  
  return array;
}
```

Inspired by [Sarah Drasner's Tweet](https://twitter.com/sarah_edo/status/1037774093875965952)
<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Ok want a dev life hack for real? As soon as you understand a concept, make a reduced example of it. As simple as you can make it. Then you can refer to it later when you inevitably forget. Bonus points if you open source it.</p>&mdash; Sarah Drasner honeymoonin’ (@sarah_edo) <a href="https://twitter.com/sarah_edo/status/1037774093875965952?ref_src=twsrc%5Etfw">September 6, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
