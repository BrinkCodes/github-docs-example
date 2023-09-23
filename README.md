# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to copy, paste, share code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

- In order to create codeblocks in markdown you need to use three backticks (`)
- Not to be confused with quotation (')
```
function factorial(n) {
  if (n === 0 || n === 1) {
    return 1;
  } else {
    return n * factorial(n - 1);
  }
}

// Test the factorial function
const num = 5;
const result = factorial(num);
console.log(`The factorial of ${num} is ${result}`);
```

- When you can you should attempt to apply syntax highlighting to your codeblocks

```javascript
function factorial(n) {
  if (n === 0 || n === 1) {
    return 1;
  } else {
    return n * factorial(n - 1);
  }
}

// Test the factorial function
const num = 5;
const result = factorial(num);
console.log(`The factorial of ${num} is ${result}`);
```
