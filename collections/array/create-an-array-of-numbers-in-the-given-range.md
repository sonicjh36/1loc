~~~ javascript
const range = (min, max) => Array(max - min + 1).fill(0).map((_, i) => max - min + i);
// range(5, 10) === [5, 6, 7, 8, 9, 10]
~~~