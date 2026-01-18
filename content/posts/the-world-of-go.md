+++
date = '2026-01-17T14:40:54+05:30'
draft = false
title = 'The World of Go'
+++

[Go](https://go.dev/) is a compiled language. Its toolchain is accessible through
a single command go, which has a number of sub-commands(run, build, ...)

It also handles Unicode natively, so it can process text in all the world's languages.

Go code is organized into packages, which consist of one or more `.go` files in 
a single directory.

Packages can be imported using the `import` statement which can take two forms:
```
import "fmt" // imports a single package
```

Or:

```
// Parenthesized List
import (
    "fmt"
    "os"
)
```

Finally, `package main` defines a standalone executable(and not a library).
Within `package main`, `func main` is where the execution of the program begins.