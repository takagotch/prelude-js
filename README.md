### prelude-js
---
https://github.com/alanrsoares/prelude-js

```
npm install preludejs
npm test
```

```js
const add = curry((a, b) => a + b);
const inc = add(1);
inc(2);

const sum = (a, b) => a + b;
apply(sum, [2, 3]);

const invertedPower = flip(Math.pow);
invertedPower(2, 3);

fix((fib) => (n) => n <= 1
  ? 1
  : fib(n - 1) + fib(n - 2))(9);

cont memoF = memize(expensiveFunction);
memoF(2)
memoF(2)
```

```
```

