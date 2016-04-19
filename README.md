# Interview a frontend developer

http://programmers.stackexchange.com/questions/251101/i-know-javascript-really-well-but-i-bomb-coding-interviews
http://www.sitepoint.com/5-typical-javascript-interview-exercises/

## Goal of this test:
- TODO

## Check the most important aspects of a frontend programmer

1. Knowledge of browser compatibility and debugging
2. Use and knowledge of tools
3. Can they implement a design and do they have a sense of design

## Questions to weed out the noobs

1. Can you tell me the difference between Java and Javascript
2. Can you tell me the difference between `==` and `===`
> `===` is called as strict equality operator which returns true when the two operands are having the same value without any type conversion.
3. What happens if you 'use strict';

## Advanced questions

4. (advanced) can you explain what hoisting is 
5. What will the code below output? Explain your answer.

```javascript
console.log(0.1 + 0.2);
console.log(0.1 + 0.2 == 0.3);
```

```shell
> 0.30000000000000004
> false
```

> This has to do with floating point implementation

6. What is a “closure” in JavaScript? Provide an example.

> A closure is an inner function that has access to the variables in the outer (enclosing) function’s scope chain. The closure has access to variables in three scopes; specifically: (1) variable in its own scope, (2) variables in the enclosing function’s scope, and (3) global variables.

7. What are global variables, how are they declared and which problems are associated with using them.

> The problems that are faced by using global variables are the clash of variable names of local and global scope. Also, it is difficult to debug and test the code that relies on global variables.

## Programming exercise:

1. You can write code. Many candidates with ten years professional experience in a language can't write any code at all, and this test is intended to reject those candidates.
2. You think about a problem before you write code. Many would jump to their keyboards, write tens of lines of code, then find that they misunderstood the original problem, because they didn't take time thinking about it.
3. You are able to adapt yourself when writing code. Say you found a solution, but when you started to implement it, it appeared that your first idea wasn't the best one; can you rapidly switch to a better one, eventually refactoring the code you wrote?


Progamming questions will consist of tests fix and refactoring. Main goal is to see how you work in a team and how your process is.
