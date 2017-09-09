
Fibonacci sequence is very familiar to everybody. We can write the following function in 20 seconds.

```js
var fibonacci = function(n) {
  return n < 2 ? n : fibonacci(n - 1) + fibonacci(n - 2);
}
```

```js
var fibonacci = (function() {
  var cache = [0, 1]; // cache the value at the n index
  return function(n) {
    if (cache[n] === undefined) {
      for (var i = cache.length; i <= n; ++i) {cache[i] = cache[i - 1] + cache[i - 2];}
    }
    return cache[n];
  }
})();

