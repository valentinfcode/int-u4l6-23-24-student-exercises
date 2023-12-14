# Student README: Lesson 4.6 - Review

## Review
### Saving User Input
- Retrieve a user’s input using `.value`.
- Save it inside a variable.
- Display the input on a page.

### Example
- Typing in an input box on a website for login or sharing content.

### Steps to Store/Use User Input
1. **Create a Variable:** 
    - Use `let` to declare a variable to save user input.
    - Example: `let userInput;`
2. **Store the Input with `.value`:**
    - Use `.value` to get the value from an input field.
    - Example: `let userInput = document.querySelector("input").value;`
3. **Display on Page with `.innerHTML`:**
    - Use `.innerHTML` to show the user input on the webpage.
    - Example:
        ```javascript
        button.addEventListener("click", function() {
            let userInput = document.querySelector("input").value;
            document.querySelector("div").innerHTML = userInput;
        });
        ```

### Key Questions
- Why create a variable first?
    - To store the user input for later use.
- What gets saved in `userInput`?
    - Whatever the user types in the input field, like "coding is fun!"

## Recap: Saving User Input
- **Three Steps:** Create variable, store with `.value`, display with `.innerHTML`.
- **Console Usage:** Use `console.log()` to check the value stored in variables during development.

---

Happy coding! 😊