---
title: A better Hello World
tags: [Software Development]
style: fill
color: dark
language: 🇺🇸 
image: https://www.terraform.io/assets/images/og-image-large-e60c82fe.png
description: A different “hello world” to demonstrate language features better.
---

Source: [RICO STA. CRUZ](https://ricostacruz.com/til/a-better-hello-world)

The “Hello world” program is usually the first introduction to any programming language. It looks like this in the C programming language:

```c
/* hello.c */
#import <stdio.h>

int main(int argc, char *argv[]) {
  printf("Hello, world!");
  return 0;
}
```

It demonstrates the minimum amount you need to write a C program. In more modern languages however, this example isn’t as useful anymore. Here’s the same example in Python:

```python
# hello.py
print "Hello, world!"
```

## A better hello world

In today’s world of more succint programming languages, we need a different “hello world” to demonstrate language features better. Here’s what I propose:

```
// hello.js
function getGreeting (name) {
  return `Hello, ${name}!`
}

const message = getGreeting('world')
console.log(message)
```

This simple example demonstrates a few more things than printing strings:

- How to write a function with an argument
- Returning values from functions
- How to use variables
- The naming convention for functions (camelCase versus snake_case)
- String concatenation
- Comments