+++
date = '2026-01-20T12:43:49+05:30'
draft = false
title = 'The for Loop'
tags = ['golang', 'forloop']
+++

The [go](https://go.dev) `for` loop is phenomenal. It is the only looping construct
available in the language.

Its can take various forms:

```
for initialization; condition; post {
    // A traditional for loop
}
```

It can also `emulate` a while loop:
```
// the while loop
for condition {
    // loops `WHILE` the condition is true
    ...
}
```

And finally, when used with `range`:
```
for i, arg := range(os.Args[1:]) {
    // arg is the element at index i
}
```