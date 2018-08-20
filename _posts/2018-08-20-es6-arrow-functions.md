---
layout: single
author_profile: true
read_time: true
comments: false
share: false
related: false
title: ES6 Arrow Functions
---

I’m going through Wes Bos’ [JavaScript 30](https://javascript30.com) course to get myself re-amped up on the language getting into free agency. A topic I’ve found fascinating are clean ways to denote functions, specifically the arrow function in JavaScript ES6.

The way it works is instead of defining a brand new function and calling it to perform its... function, you do the following.

Say you want to calculate the sum of a couple variables. A long way would be to form a function and call it.

```
function findSum(a, b) {
  Return a + b
}

Var c = findSum(1, 2) // 3
```

 Instead, you can form the function inline like this.

```
var c = (1, 2) => { return 1 + 2 }
```

I think that’s pretty awesome. Clean, concise code that’s easily readable.
