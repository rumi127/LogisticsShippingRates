# LogisticsShippingRates
# Contribution Guidelines

Thank you for considering contributing to this project! This document outlines the guidelines for contributing code, reporting issues, and submitting pull requests to keep the project consistent and high-quality.

## 1. Code Style
- Follow the coding style consistent with the project.
- Use **[Prettier](https://prettier.io/)** or another formatter to ensure consistency.
- Make sure your code is clean, well-organized, and easy to read.
- Ensure that all variables, functions, classes, and files have meaningful names.
- Use **camelCase** for JavaScript variables and functions.
- Use **PascalCase** for React components and classes.
- Always use **const** or **let** for variable declarations (never **var**).

### Example:
```js
// Good example
const userName = "John Doe";
function getUserName() {
    return userName;
}

// Bad example
var user_name = 'John Doe';
function GetUserName() {
    return user_name;
}
