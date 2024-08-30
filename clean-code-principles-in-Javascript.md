"Clean Code" in JavaScript refers to writing code that is easy to understand, maintain, and extend. It is a concept popularized by Robert C. Martin in his book Clean Code, and it can be applied to any programming language, including JavaScript. Here are some principles and practices to help you write clean JavaScript code:

1. Meaningful Names
Variables and functions should have descriptive names: Use meaningful and pronounceable names that convey the purpose of the variable or function.

```
// Bad 
const n = 5; 

// Good 
const numberOfItems = 5;
```

Avoid generic names: Names like data, obj, temp should be avoided unless they are truly representative.
```
// Bad 
function getData() { // ... } 

// Good 
function getUserDetails() { // ... }
```

2. Functions Should Do One Thing
