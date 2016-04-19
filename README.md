# Interview a frontend developer

http://programmers.stackexchange.com/questions/251101/i-know-javascript-really-well-but-i-bomb-coding-interviews
http://www.sitepoint.com/5-typical-javascript-interview-exercises/
http://blog.sourcing.io/interview-questions
http://www.frontendjournal.com/most-common-technical-interview-question-for-frontend-developers/

## Goal of this test:
- TODO CSS & HTML

## Check the most important aspects of a frontend programmer

1. Knowledge of browser compatibility and debugging (this includes mobile browsers)
2. Use and knowledge of tools
3. Can they implement a design and do they have a sense of design

## Break the ice
Make the candidate feel a bit at ease. Try to explain what you are going to do and how you will go at it. Some nice starting questions are:

- What's a cool project that you've recently worked on?
- What are some things you like about the developer tools you use?
- Who inspires you in the front-end community?
- Do you have any pet projects? What kind?
- Which front-end related websites do you visit on a regular basis

## Starter questions

- Can you tell me the difference between Java and Javascript
- How do you test if your code is cross-browser compatible
- Can you tell me the difference between `==` and `===`

> `===` is called as strict equality operator which returns true when the two operands are having the same value without any type conversion.

- What happens if you `'use strict';`
- What are global variables, how are they declared and which problems are associated with using them.

> The problems that are faced by using global variables are the clash of variable names of local and global scope. Also, it is difficult to debug and test the code that relies on global variables.

## Advanced questions

### General
- Tell me about the hardest cross-browser compatibility issue you've ever dealt with.
- If a product owner says: "I have a bug with the application in IE8"; how would you go about solving this?
- what does git rebase do (only incase candidate works with Git)
- Name 3 ways to decrease page load (perceived or actual load time).
- How would you approach a project that has a requirement that it should be usable without javascript
- What does the term `SEO-friendly` mean?

### HTML
- Describe the difference between a cookie, sessionStorage and localStorage.
- Why is it generally a good idea to position CSS `<link>`s between `<head></head>` and JS `<script>`s just before `</body>`? Do you know any exceptions?

### CSS
- What is the difference between classes and IDs in CSS?
- Describe Floats and how they work.
- How do you optimize your webpages for print?
- What are the advantages/disadvantages of using CSS preprocessors? Describe what you like and dislike about the CSS preprocessors you have used.
- List as many values for the display property that you can remember.
- What's the difference between inline and inline-block?
- How is responsive design different from adaptive design?
- Have you ever worked with retina graphics? If so, when and what techniques did you use?

### Javascript
- Explain event delegation
- How do you organize your code? (module pattern, classical inheritance?)
- Explain Ajax in as much detail as possible.
- can you explain "closure", "arity", "hoisted", "scope", "inherited" mean.

 > Hoisting
 > The reason is that both variables and functions are hoisted (moved at the top of the function) but variables don’t retain any assigned value. So, at the time the variable a is printed, it exists in the function (it’s declared) but it’s still undefined. Stated in other words, the code above is equivalent to the following:
 
- What will the code below output? Explain your answer.

```javascript
console.log(0.1 + 0.2);
console.log(0.1 + 0.2 == 0.3);
```

```shell
> 0.30000000000000004
> false
```

> This has to do with floating point implementation

- What is a “closure” in JavaScript? Provide an example.

> A closure is an inner function that has access to the variables in the outer (enclosing) function’s scope chain. The closure has access to variables in three scopes; specifically: (1) variable in its own scope, (2) variables in the enclosing function’s scope, and (3) global variables.
- Describe event bubbling.
- What's the difference between an "attribute" and a "property"?

## Programming exercise:
Progamming questions will consist of tests fix and refactoring. Main goal is to see how you work in a team and how your process is.

> Refactoring
> Reusability
> Explain MVC?

- You can write code. Many candidates with ten years professional experience in a language can't write any code at all, and this test is intended to reject those candidates.
- You think about a problem before you write code. Many would jump to their keyboards, write tens of lines of code, then find that they misunderstood the original problem, because they didn't take time thinking about it.
- You are able to adapt yourself when writing code. Say you found a solution, but when you started to implement it, it appeared that your first idea wasn't the best one; can you rapidly switch to a better one, eventually refactoring the code you wrote?

###Exercises

- "create a function that checks whether a number is a prime number"
- Describe how you would create a simple slideshow page.
- duplicate([1,2,3,4,5]); // => [1,2,3,4,5,1,2,3,4,5]
- spacify('hello world') // => 'h e l l o  w o r l d'
- Create a for loop that iterates up to 100 while outputting "fizz" at multiples of 3, "buzz" at multiples of 5 and "fizzbuzz" at multiples of 3 and 5